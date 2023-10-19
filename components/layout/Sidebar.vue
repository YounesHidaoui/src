<template>
    <div :class="{ 'dark text-white-dark': store.semidark }">
        <nav class="sidebar fixed top-0 bottom-0 z-50 h-full min-h-screen w-[260px] shadow-[5px_0_25px_0_rgba(94,92,154,0.1)] transition-all duration-300">
            <div class="h-full bg-white dark:bg-[#0e1726]">
             <Logo/>
                <client-only>
                    
                        <ul class="relative space-y-0.5 p-4 py-0 font-semibold">
                            <MenuList/>
                           
                        </ul>
                  
                </client-only>
            </div>
        </nav>
    </div>
</template>

<script lang="ts" setup>

    import { ref, onMounted } from 'vue';
    import Logo from './Logo.vue'
    import MenuList from './MenuList.vue'
    
    import { useAppStore } from '@/stores/index';
    import VueCollapsible from 'vue-height-collapsible/vue3';
    const store = useAppStore();
    const activeDropdown: any = ref('');
    const subActive: any = ref('');

    onMounted(() => {
        setTimeout(() => {
            const selector = document.querySelector('.sidebar ul a[href="' + window.location.pathname + '"]');

            if (selector) {
                selector.classList.add('active');
                const ul: any = selector.closest('ul.sub-menu');
                if (ul) {
                    let ele: any = ul.closest('li.menu').querySelectorAll('.nav-link') || [];

                    if (ele.length) {
                        ele = ele[0];
                        setTimeout(() => {
                            ele.click();
                        });
                    }
                }
            }
        });
    });

    
</script>
