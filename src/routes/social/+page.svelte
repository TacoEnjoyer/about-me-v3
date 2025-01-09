<script>
    import Navbar from "../navbar.svelte";
</script>
<Navbar />
<body class="bg-gradient-to-r from-stone-700 to-stone-500 font-serif antialiased text-white">
    <div class="pt-24 md:px-16 px-6">
        <h1 class="text-center text-3xl font-thin">Here are some of my Social media.</h1>
    </div>
    <div class="flex justify-center gap-6 pt-10 md:px-16 px-6 text-xl font-thin flex-wrap">
            <!-- svelte-ignore a11y_consider_explicit_label -->
            <a href="https://www.facebook.com/owhdoheidbekshkwhskbdksbdodboe" target="_blank" class="p-5 items-center flex rounded-xl bg-blue-600 hover:brightness-110 transition-all duration-200">
                <i class="pi pi-facebook text-5xl"></i>
            </a>
            <!-- svelte-ignore a11y_consider_explicit_label -->
            <a href="https://x.com/IbuyCocacola" target="_blank" class="p-5 items-center flex rounded-xl bg-black hover:brightness-110 transition-all duration-200">
                <i class="pi pi-twitter text-5xl"></i>
            </a>
            <!-- svelte-ignore a11y_consider_explicit_label -->
            <a href="https://www.youtube.com/@vradient-yes" target="_blank" class="p-5 items-center flex rounded-xl bg-[#FF0000] hover:brightness-110 transition-all duration-200">
                <i class="pi pi-youtube text-5xl"></i>
            </a>
            <!-- svelte-ignore a11y_consider_explicit_label -->
            <a href="https://www.tiktok.com/@vradient?is_from_webapp=1&sender_device=pc" target="_blank" class="p-5 items-center flex rounded-xl bg-black hover:brightness-110 transition-all duration-200">
                <i class="pi pi-tiktok text-5xl"></i>
            </a>
            <!-- svelte-ignore a11y_consider_explicit_label -->
            <a href="https://github.com/TacoEnjoyer" target="_blank" class="p-5 items-center flex rounded-xl bg-purple-600 hover:brightness-110 transition-all duration-200">
                <i class="pi pi-github text-5xl"></i>
            </a>
    </div>
</body>