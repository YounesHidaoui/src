<template>

            <li class="nav-item py-8 ">
                        <ul>
                                    <!-- Accuiler Link  -->
                                    <li class="nav-item">
                                        <NuxtLink to="/apps/Accueil" class="group" @click="toggleMobileMenu">
                                            <div class="flex items-center">
                                                <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                        <path d="M12.0266 3.78672L4.83996 9.38672C3.63996 10.3201 2.66663 12.3067 2.66663 13.8134V23.6934C2.66663 26.7867 5.18663 29.3201 8.27996 29.3201H23.72C26.8133 29.3201 29.3333 26.7867 29.3333 23.7067V14.0001C29.3333 12.3867 28.2533 10.3201 26.9333 9.40005L18.6933 3.62672C16.8266 2.32005 13.8266 2.38672 12.0266 3.78672Z" stroke="#B16F4A" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>      
                                                        <path d="M16 23.9866V19.9866" stroke="#B16F4A" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                                                </svg>


                                                <span class=" span text-black ltr:pl-3 rtl:pr-3 dark:text-[#506690] dark:group-hover:text-white-dark">{{
                                                    $t('Accueil')
                                                }}</span>
                                            </div>
                                        </NuxtLink>
                                    </li>  
                                     <!-- Dossier  -->
                                    <li class="nav-item">
                                        <NuxtLink to="/apps/Dossier" class="group" @click="toggleMobileMenu">
                                            <div class="flex items-center">
                                                <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                    <path d="M29.3333 14.6667V22.6667C29.3333 28.0001 28 29.3334 22.6666 29.3334H9.33329C3.99996 29.3334 2.66663 28.0001 2.66663 22.6667V9.33341C2.66663 4.00008 3.99996 2.66675 9.33329 2.66675H11.3333C13.3333 2.66675 13.7733 3.25341 14.5333 4.26675L16.5333 6.93341C17.04 7.60008 17.3333 8.00008 18.6666 8.00008H22.6666C28 8.00008 29.3333 9.33341 29.3333 14.6667Z" stroke="#B16F4A" stroke-width="2.5" stroke-miterlimit="10"/>
                                                    <path d="M10.6666 2.66675H22.6666C25.3333 2.66675 26.6666 4.00008 26.6666 6.66675V8.50675" stroke="#B16F4A" stroke-width="2.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                                    </svg>
                                                <span class="span text-black ltr:pl-3 rtl:pr-3 dark:text-[#506690] dark:group-hover:text-white-dark">{{
                                                    $t('Dossiers')
                                                }}</span>
                                            </div>
                                        </NuxtLink>
                                    </li>   
                                    <!-- Clients  -->
                                    <li class="nav-item">
                                        <NuxtLink to="/apps/Client" class="group" @click="toggleMobileMenu">
                                            <div class="flex items-center">
                                                <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                    <path d="M23.9999 9.54675C23.9199 9.53342 23.8266 9.53342 23.7466 9.54675C21.9066 9.48009 20.4399 7.97342 20.4399 6.10675C20.4399 4.20008 21.9733 2.66675 23.8799 2.66675C25.7866 2.66675 27.3199 4.21342 27.3199 6.10675C27.3066 7.97342 25.8399 9.48009 23.9999 9.54675Z" stroke="#B16F4A" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                                                    <path d="M22.6266 19.2534C24.4532 19.5601 26.4666 19.2401 27.8799 18.2934C29.7599 17.0401 29.7599 14.9867 27.8799 13.7334C26.4532 12.7867 24.4132 12.4667 22.5865 12.7867" stroke="#B16F4A" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                                                    <path d="M7.96002 9.54675C8.04002 9.53342 8.13335 9.53342 8.21335 9.54675C10.0533 9.48009 11.52 7.97342 11.52 6.10675C11.52 4.20008 9.98668 2.66675 8.08002 2.66675C6.17335 2.66675 4.64001 4.21342 4.64001 6.10675C4.65335 7.97342 6.12002 9.48009 7.96002 9.54675Z" stroke="#B16F4A" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                                                    <path d="M9.33337 19.2534C7.50671 19.5601 5.49338 19.2401 4.08004 18.2934C2.20004 17.0401 2.20004 14.9867 4.08004 13.7334C5.50671 12.7867 7.54671 12.4667 9.37337 12.7867" stroke="#B16F4A" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                                                    <path d="M15.9999 19.5067C15.9199 19.4934 15.8266 19.4934 15.7466 19.5067C13.9066 19.44 12.4399 17.9334 12.4399 16.0667C12.4399 14.16 13.9733 12.6267 15.8799 12.6267C17.7866 12.6267 19.3199 14.1734 19.3199 16.0667C19.3066 17.9334 17.8399 19.4534 15.9999 19.5067Z" stroke="#B16F4A" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                                                    <path d="M12.12 23.7067C10.24 24.9601 10.24 27.0134 12.12 28.2667C14.2533 29.6934 17.7466 29.6934 19.88 28.2667C21.76 27.0134 21.76 24.9601 19.88 23.7067C17.76 22.2934 14.2533 22.2934 12.12 23.7067Z" stroke="#B16F4A" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                                                    </svg>

                                                <span class=" span text-black ltr:pl-3 rtl:pr-3 dark:text-[#506690] dark:group-hover:text-white-dark">{{
                                                    $t('Clients')
                                                }}</span>
                                            </div>
                                        </NuxtLink>
                                    </li>    
                                    <!-- Factures -->
                                    <li class="nav-item">
                                        
                                        <NuxtLink to="/apps/Factures" class="group" @click="toggleMobileMenu">
                                            <div class="flex items-center">
                                                <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                    <path d="M4.89331 3.33325V19.2933C4.89331 20.5999 5.50664 21.8399 6.55998 22.6266L13.5066 27.8266C14.9866 28.9332 17.0266 28.9332 18.5066 27.8266L25.4533 22.6266C26.5066 21.8399 27.12 20.5999 27.12 19.2933V3.33325H4.89331Z" stroke="#B16F4A" stroke-width="2.5" stroke-miterlimit="10"/>
                                                    <path d="M2.66663 3.33325H29.3333" stroke="#B16F4A" stroke-width="2.5" stroke-miterlimit="10" stroke-linecap="round"/>
                                                    <path d="M10.6666 10.6667H21.3333" stroke="#B16F4A" stroke-width="2.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                                    <path d="M10.6666 17.3333H21.3333" stroke="#B16F4A" stroke-width="2.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                                    </svg>
                                                <span class="span text-black ltr:pl-3 rtl:pr-3 dark:text-[#506690] dark:group-hover:text-white-dark">{{
                                                    $t('Factures')
                                                }}</span>
                                            </div>
                                        </NuxtLink>
                                    </li>     
                                    <!-- rendez-vous -->
                                    <li class="nav-item ">
                                        <NuxtLink to="/apps/rendez-vous" class="group" @click="toggleMobileMenu">
                                            <div class="flex items-center">
                                                <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <mask id="mask0_317_3288" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="32" height="32">
                                                <rect width="32" height="32" fill="#D9D9D9"/>
                                                </mask>
                                                <g mask="url(#mask0_317_3288)">
                                                <path d="M10.6667 18.6667C10.2889 18.6667 9.97222 18.539 9.71667 18.2834C9.46111 18.0279 9.33333 17.7112 9.33333 17.3334C9.33333 16.9556 9.46111 16.639 9.71667 16.3834C9.97222 16.1279 10.2889 16.0001 10.6667 16.0001C11.0444 16.0001 11.3611 16.1279 11.6167 16.3834C11.8722 16.639 12 16.9556 12 17.3334C12 17.7112 11.8722 18.0279 11.6167 18.2834C11.3611 18.539 11.0444 18.6667 10.6667 18.6667ZM16 18.6667C15.6222 18.6667 15.3056 18.539 15.05 18.2834C14.7944 18.0279 14.6667 17.7112 14.6667 17.3334C14.6667 16.9556 14.7944 16.639 15.05 16.3834C15.3056 16.1279 15.6222 16.0001 16 16.0001C16.3778 16.0001 16.6944 16.1279 16.95 16.3834C17.2056 16.639 17.3333 16.9556 17.3333 17.3334C17.3333 17.7112 17.2056 18.0279 16.95 18.2834C16.6944 18.539 16.3778 18.6667 16 18.6667ZM21.3333 18.6667C20.9556 18.6667 20.6389 18.539 20.3833 18.2834C20.1278 18.0279 20 17.7112 20 17.3334C20 16.9556 20.1278 16.639 20.3833 16.3834C20.6389 16.1279 20.9556 16.0001 21.3333 16.0001C21.7111 16.0001 22.0278 16.1279 22.2833 16.3834C22.5389 16.639 22.6667 16.9556 22.6667 17.3334C22.6667 17.7112 22.5389 18.0279 22.2833 18.2834C22.0278 18.539 21.7111 18.6667 21.3333 18.6667ZM6.66667 29.3334C5.93333 29.3334 5.30556 29.0723 4.78333 28.5501C4.26111 28.0279 4 27.4001 4 26.6667V8.00008C4 7.26675 4.26111 6.63897 4.78333 6.11675C5.30556 5.59453 5.93333 5.33341 6.66667 5.33341H8V2.66675H10.6667V5.33341H21.3333V2.66675H24V5.33341H25.3333C26.0667 5.33341 26.6944 5.59453 27.2167 6.11675C27.7389 6.63897 28 7.26675 28 8.00008V26.6667C28 27.4001 27.7389 28.0279 27.2167 28.5501C26.6944 29.0723 26.0667 29.3334 25.3333 29.3334H6.66667ZM6.66667 26.6667H25.3333V13.3334H6.66667V26.6667ZM6.66667 10.6667H25.3333V8.00008H6.66667V10.6667Z" fill="#B16F4A"/>
                                                </g>
                                                </svg>


                                                <span class=" span  text-black ltr:pl-3 rtl:pr-3 dark:text-[#506690] dark:group-hover:text-white-dark">{{
                                                    $t('rendez-vous')
                                                }}</span>
                                            </div>
                                        </NuxtLink>
                                    </li>     
                                     <!--Parametres  -->
                                    <li class="nav-item">
                                        <NuxtLink to="/apps/Parametres" class="group" @click="toggleMobileMenu">
                                            <div class="flex items-center">
                                                <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                    <path d="M16 20C18.2091 20 20 18.2091 20 16C20 13.7909 18.2091 12 16 12C13.7909 12 12 13.7909 12 16C12 18.2091 13.7909 20 16 20Z" stroke="#B16F4A" stroke-width="2.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                                    <path d="M2.66663 17.1733V14.8267C2.66663 13.44 3.79996 12.2933 5.19996 12.2933C7.61329 12.2933 8.59996 10.5867 7.38663 8.49333C6.69329 7.29333 7.10663 5.73333 8.31996 5.04L10.6266 3.72C11.68 3.09333 13.04 3.46666 13.6666 4.52L13.8133 4.77333C15.0133 6.86666 16.9866 6.86666 18.2 4.77333L18.3466 4.52C18.9733 3.46666 20.3333 3.09333 21.3866 3.72L23.6933 5.04C24.9066 5.73333 25.32 7.29333 24.6266 8.49333C23.4133 10.5867 24.4 12.2933 26.8133 12.2933C28.2 12.2933 29.3466 13.4267 29.3466 14.8267V17.1733C29.3466 18.56 28.2133 19.7067 26.8133 19.7067C24.4 19.7067 23.4133 21.4133 24.6266 23.5067C25.32 24.72 24.9066 26.2667 23.6933 26.96L21.3866 28.28C20.3333 28.9067 18.9733 28.5333 18.3466 27.48L18.2 27.2267C17 25.1333 15.0266 25.1333 13.8133 27.2267L13.6666 27.48C13.04 28.5333 11.68 28.9067 10.6266 28.28L8.31996 26.96C7.10663 26.2667 6.69329 24.7067 7.38663 23.5067C8.59996 21.4133 7.61329 19.7067 5.19996 19.7067C3.79996 19.7067 2.66663 18.56 2.66663 17.1733Z" stroke="#B16F4A" stroke-width="2.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                                </svg>

                                                <span class="span text-black ltr:pl-3 rtl:pr-3 dark:text-[#506690] dark:group-hover:text-white-dark">{{
                                                    $t('Parametres')
                                                }}</span>
                                            </div>
                                        </NuxtLink>
                                    </li>          
                        </ul>
            </li>
</template>





<script setup>
const toggleMobileMenu = () => {
        if (window.innerWidth < 1024) {
            store.toggleSidebar();
        }
    };


</script>
<style>

.span {
    font-family: Outfit;
font-size: 19px;
font-weight: 530;
line-height: 30px;
letter-spacing: 0em;
text-align: left;
color: #0D0D0D;

}


</style>