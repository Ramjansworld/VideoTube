<template>
     <div class="flex flex-col items-start justify-start h-screen w-full scroll-smooth overflow-auto w-[200px]">  
        <ul class="list-none mt-[10px] border-b-2 border-solid py-[10px]">
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/home">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                </svg>

            </NuxtLink>
            <p class="pr-[100px] hover:pl-[38px] ">Home</p>
        </li>
        
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/shorts">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M13.19 8.688a4.5 4.5 0 011.242 7.244l-4.5 4.5a4.5 4.5 0 01-6.364-6.364l1.757-1.757m13.35-.622l1.757-1.757a4.5 4.5 0 00-6.364-6.364l-4.5 4.5a4.5 4.5 0 001.242 7.244" />
                </svg>
            </NuxtLink> 
            <p class="pr-[100px] hover:pl-[35px]">Shorts</p>
        </li>
        
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px]  bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/subscriptions">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 16.875h3.375m0 0h3.375m-3.375 0V13.5m0 3.375v3.375M6 10.5h2.25a2.25 2.25 0 002.25-2.25V6a2.25 2.25 0 00-2.25-2.25H6A2.25 2.25 0 003.75 6v2.25A2.25 2.25 0 006 10.5zm0 9.75h2.25A2.25 2.25 0 0010.5 18v-2.25a2.25 2.25 0 00-2.25-2.25H6a2.25 2.25 0 00-2.25 2.25V18A2.25 2.25 0 006 20.25zm9.75-9.75H18a2.25 2.25 0 002.25-2.25V6A2.25 2.25 0 0018 3.75h-2.25A2.25 2.25 0 0013.5 6v2.25a2.25 2.25 0 002.25 2.25z" />
                </svg>
            </NuxtLink> 
            <p class="pr-[50px] hover:pl-[30px]">Subscriptions</p>
        </li>
        </ul>

        <ul class="list-none mt-[10px] w-[200px] border-b-2 border-solid py-[10px]">
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/library">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 21v-8.25M15.75 21v-8.25M8.25 21v-8.25M3 9l9-6 9 6m-1.5 12V10.332A48.36 48.36 0 0012 9.75c-2.551 0-5.056.2-7.5.582V21M3 21h18M12 6.75h.008v.008H12V6.75z" />
                </svg>
            </NuxtLink>
            <p class="pr-[100px]">Library</p>
        </li>
        
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/history">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99" />
                </svg>
            </NuxtLink> 
            <p class="pr-[100px]">History</p>
        </li>
        
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px]  bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/watch">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
            </NuxtLink> 
            <p class="pr-[65px]">Watch Later</p>
        </li>
        
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/like">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6.633 10.5c.806 0 1.533-.446 2.031-1.08a9.041 9.041 0 012.861-2.4c.723-.384 1.35-.956 1.653-1.715a4.498 4.498 0 00.322-1.672V3a.75.75 0 01.75-.75A2.25 2.25 0 0116.5 4.5c0 1.152-.26 2.243-.723 3.218-.266.558.107 1.282.725 1.282h3.126c1.026 0 1.945.694 2.054 1.715.045.422.068.85.068 1.285a11.95 11.95 0 01-2.649 7.521c-.388.482-.987.729-1.605.729H13.48c-.483 0-.964-.078-1.423-.23l-3.114-1.04a4.501 4.501 0 00-1.423-.23H5.904M14.25 9h2.25M5.904 18.75c.083.205.173.405.27.602.197.4-.078.898-.523.898h-.908c-.889 0-1.713-.518-1.972-1.368a12 12 0 01-.521-3.507c0-1.553.295-3.036.831-4.398C3.387 10.203 4.167 9.75 5 9.75h1.053c.472 0 .745.556.5.96a8.958 8.958 0 00-1.302 4.665c0 1.194.232 2.333.654 3.375z" />
                </svg>
            </NuxtLink> 
            <p class="pr-[60px]">Liked Videos</p>
        </li>

        </ul>
        <h1 class="pl-[30px] text-xl font-light border-b-2 border-solid py-[10px]">Subscriptions</h1>
        <br>
        <h1 class="pl-[30px] text-xl font-light">Explore</h1>
        <ul class="list-none w-[200px] border-b-2 border-solid py-[10px]">
            <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/trending">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
          s      <path stroke-linecap="round" stroke-linejoin="round" d="M15.362 5.214A8.252 8.252 0 0112 21 8.25 8.25 0 016.038 7.048 8.287 8.287 0 009 9.6a8.983 8.983 0 013.361-6.867 8.21 8.21 0 003 2.48z" />
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 18a3.75 3.75 0 00.495-7.467 5.99 5.99 0 00-1.925 3.546 5.974 5.974 0 01-2.133-1A3.75 3.75 0 0012 18z" />
                </svg>

            </NuxtLink> 
            <p class="pr-[90px]">Trending</p>
        </li>
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/trending">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M9 9l10.5-3m0 6.553v3.75a2.25 2.25 0 01-1.632 2.163l-1.32.377a1.803 1.803 0 11-.99-3.467l2.31-.66a2.25 2.25 0 001.632-2.163zm0 0V2.25L9 5.25v10.303m0 0v3.75a2.25 2.25 0 01-1.632 2.163l-1.32.377a1.803 1.803 0 01-.99-3.467l2.31-.66A2.25 2.25 0 009 15.553z" />
                </svg>
            </NuxtLink> 
            <p class="pr-[110px]">Music</p>
        </li>
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/trending">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M14.25 6.087c0-.355.186-.676.401-.959.221-.29.349-.634.349-1.003 0-1.036-1.007-1.875-2.25-1.875s-2.25.84-2.25 1.875c0 .369.128.713.349 1.003.215.283.401.604.401.959v0a.64.64 0 01-.657.643 48.39 48.39 0 01-4.163-.3c.186 1.613.293 3.25.315 4.907a.656.656 0 01-.658.663v0c-.355 0-.676-.186-.959-.401a1.647 1.647 0 00-1.003-.349c-1.036 0-1.875 1.007-1.875 2.25s.84 2.25 1.875 2.25c.369 0 .713-.128 1.003-.349.283-.215.604-.401.959-.401v0c.31 0 .555.26.532.57a48.039 48.039 0 01-.642 5.056c1.518.19 3.058.309 4.616.354a.64.64 0 00.657-.643v0c0-.355-.186-.676-.401-.959a1.647 1.647 0 01-.349-1.003c0-1.035 1.008-1.875 2.25-1.875 1.243 0 2.25.84 2.25 1.875 0 .369-.128.713-.349 1.003-.215.283-.4.604-.4.959v0c0 .333.277.599.61.58a48.1 48.1 0 005.427-.63 48.05 48.05 0 00.582-4.717.532.532 0 00-.533-.57v0c-.355 0-.676.186-.959.401-.29.221-.634.349-1.003.349-1.035 0-1.875-1.007-1.875-2.25s.84-2.25 1.875-2.25c.37 0 .713.128 1.003.349.283.215.604.401.96.401v0a.656.656 0 00.658-.663 48.422 48.422 0 00-.37-5.36c-1.886.342-3.81.574-5.766.689a.578.578 0 01-.61-.58v0z" />
                </svg>
            </NuxtLink> 
            <p class="pr-[100px]">Gaming</p>
        </li>
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/trending">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 013 3h-15a3 3 0 013-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 01-.982-3.172M9.497 14.25a7.454 7.454 0 00.981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 007.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 002.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 012.916.52 6.003 6.003 0 01-5.395 4.972m0 0a6.726 6.726 0 01-2.749 1.35m0 0a6.772 6.772 0 01-3.044 0" />
                </svg>
            </NuxtLink> 
            <p class="pr-[110px]">Sports</p>
        </li>
        </ul>
        <br>
        <h1 class="pl-[30px] text-lg font-light w-auto border-b-2 border-solid py-[10px]">More From VideoTube</h1>
    <ul class="list-none w-[200px] border-b-2 border-solid py-[10px]">
        <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/settings">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                 <path stroke-linecap="round" stroke-linejoin="round" d="M9.594 3.94c.09-.542.56-.94 1.11-.94h2.593c.55 0 1.02.398 1.11.94l.213 1.281c.063.374.313.686.645.87.074.04.147.083.22.127.324.196.72.257 1.075.124l1.217-.456a1.125 1.125 0 011.37.49l1.296 2.247a1.125 1.125 0 01-.26 1.431l-1.003.827c-.293.24-.438.613-.431.992a6.759 6.759 0 010 .255c-.007.378.138.75.43.99l1.005.828c.424.35.534.954.26 1.43l-1.298 2.247a1.125 1.125 0 01-1.369.491l-1.217-.456c-.355-.133-.75-.072-1.076.124a6.57 6.57 0 01-.22.128c-.331.183-.581.495-.644.869l-.213 1.28c-.09.543-.56.941-1.11.941h-2.594c-.55 0-1.02-.398-1.11-.94l-.213-1.281c-.062-.374-.312-.686-.644-.87a6.52 6.52 0 01-.22-.127c-.325-.196-.72-.257-1.076-.124l-1.217.456a1.125 1.125 0 01-1.369-.49l-1.297-2.247a1.125 1.125 0 01.26-1.431l1.004-.827c.292-.24.437-.613.43-.992a6.932 6.932 0 010-.255c.007-.378-.138-.75-.43-.99l-1.004-.828a1.125 1.125 0 01-.26-1.43l1.297-2.247a1.125 1.125 0 011.37-.491l1.216.456c.356.133.751.072 1.076-.124.072-.044.146-.087.22-.128.332-.183.582-.495.644-.869l.214-1.281z" />
                 <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                </svg>
            </NuxtLink> 
            <p class="pr-[95px]">Settings</p>
         </li>
         <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/report">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M3 3v1.5M3 21v-6m0 0l2.77-.693a9 9 0 016.208.682l.108.054a9 9 0 006.086.71l3.114-.732a48.524 48.524 0 01-.005-10.499l-3.11.732a9 9 0 01-6.085-.711l-.108-.054a9 9 0 00-6.208-.682L3 4.5M3 15V4.5" />
                </svg>
            </NuxtLink> 
            <p class="pr-[50px]">Report History</p>
         </li>
         <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/help">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M12 9v6m3-3H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
            </NuxtLink> 
            <p class="pr-[118px]">Help</p>
         </li>
         <li class="flex flex-row justify-between ml-[25px] items-start h-[40px] bg-white hover:bg-gray-300 hover:h-[40px] items-center rounded-lg w-[200px] hover:ml-[15px] hover:pl-[10px]">
            <NuxtLink to="/feedback">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M9.879 7.519c1.171-1.025 3.071-1.025 4.242 0 1.172 1.025 1.172 2.687 0 3.712-.203.179-.43.326-.67.442-.745.361-1.45.999-1.45 1.827v.75M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-9 5.25h.008v.008H12v-.008z" />
                </svg>
            </NuxtLink> 
            <p class="pr-[45px]">Send Feedback</p>
         </li>
    </ul>
    <ul class="flex flex-row justify-between list-none cursor-pointer w-[200px] ml-[20px] pr-[35px] py-[5px]">
        <li>About</li>
        <li>Press</li>
        <li>Copyright</li>
      </ul>

      <ul class="flex flex-row justify-between ml-[20px] pr-[45px] list-none cursor-pointer w-[200px]">
        <li>Contact Us</li>
        <li>Creators</li>
      </ul>
  
      <ul class="flex flex-row justify-between list-none cursor-pointer ml-[20px] pr-[45px] w-[200px]">
        <li>Advertise</li>
        <li>Developers</li>
      </ul>
      <br/>
      <ul class="flex flex-row justify-between list-none cursor-pointer ml-[20px] w-[200px]">
        <li>Terms</li>
        <li>Privacy</li>
        <li>Policy & Safety</li>
      </ul>
      <h2 class="ml-[20px] w-[200px]">How VideoTube Works?</h2>
      <h2 class="ml-[20px] w-[200px]">Test New Features</h2>
      <br/>
      <p class="ml-[20px]">©2023 Microsoft LLC</p>
      <br/>
      <br/>
      <br/>
</div>
</template>