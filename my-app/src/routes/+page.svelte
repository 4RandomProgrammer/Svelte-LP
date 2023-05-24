<script>
    import { each } from "svelte/internal";

    const features = [
        {
            title:'Upload & Organize',
            icon:'upload',
            description:'Upload in bulk, organize content in categories, add custom filters & upload extras.'
        },
        {
            title:'Stream On-Demand',
            icon:'record',
            description:'Showcase your content in a beautiful on-demand video catalog.'
        },
        {
            title:'Stream Live',
            icon:'stream',
            description:'Schedule events in advance & build excitement with a countdown overlay .'
        },
        {
            title:'Monetization',
            icon:'monetization',
            description:'Offer subscriptions or one-time purchases. Accept credit cards & PayPal.'
        },
        {
            title:'Analytics',
            icon:'analytic',
            description:'Know what your audience likes & how your content is performing..'
        },
        {
            title:'For all devices',
            icon:'device',
            description:'Get organized on all devices'
        },
    ]
</script>

<section class="bg-black text-white py-20">
    <div class="max-w-screen-xl mx-auto">
        <div class="flex items-center space-x-24">
            <div class="flex flex-col w-1/2">
                <div class="flex flex-col space-y-4">
                    <h1 class="text-5xl font-heading font-bold">Reach more people in real time</h1>
                    <p>
                        The Screeno ecosystem is designed to help you generate profit. Set up complete sales and marketing funnels with ease using the Screeno
                    </p>
                </div>
                <div class="flex space-x-3 mt-12">
                    <button class="primary w-1/3">
                        Start Free Trial
                    </button>
                    <button class="outline w-1/3">
                        Login
                    </button>
                </div>
            </div>
            <div class="relative w-1/2">
                <img src="/images/hero-image-desktop.png" alt="Hero" class="w-full h-full">
                <img src="/images/hero-image-mobile.png" alt="Hero" class="absolute -bottom-4 left-3 ">
            </div>
        </div>
        <div class="flex justify-between mt-24 space-x-24">
            <img src="/images/apple-tv.svg" alt="Apple TV">
            <img src="/images/android-tv.svg" alt="Apple TV">
            <img src="/images/apple-watch.svg" alt="Apple TV">
            <img src="/images/iphone.svg" alt="Apple TV">
            <img src="/images/android.svg" alt="Apple TV">
        </div>
    </div>
</section>

<section class="py-20">
    <div class="max-w-screen-lg mx-auto">
        <div class="flex flex-col justify-center text-center">
            <div class="flex flex-col space-y-3">
                <h2 class="text-4xl font-bold font-heading">All-in-one platform</h2>
                <p>You take care of the video quality and we take care of everythig else</p>
            </div>
            <div class="flex justify-center space-x-8 mt-4">    
                <button class="w-1/6 primary">Start Free Trial</button>
                <button class="w-1/6 outline-black">Login</button>
            </div>
            <div class="grid grid-cols-3 gap-12 mt-20">
                {#each features as feature}
                    <div class="flex flex-col space-y-3 p-4">
                        <div class="flex space-x-3">
                            <img src={`/icons/${feature.icon}.svg`} alt="{feature.title}">
                            <h5 class="font-heading font-bold">{feature.title}</h5>
                        </div>
                        <p> {feature.description}</p>
                    </div>
                {/each}
            </div>
        </div>
    </div>
</section>

<section class="py-20 bg-black text-white">
    <div class="flex flex-col space-y-32 max-w-screen-xl mx-auto">
        <div class="flex flex-col justify-center">
            <h2 class="text-4xl font-heading font-bold text-center">We help you grow</h2>
        </div>
        <div class="flex space-x-24">
            <div class="flex flex-col justify-center w-1/2 space-y-6">
                <h5 class="font-semibold text-3xl">Monetize your way</h5>
                <p>
                    Set up subscriptions, rentals, or one-time buys for access to your VOD and live streams. Create exclusive experiences for your subscribers with coupons and promotions. One predictable fee, transparent pricing, and same-day setup.
                </p>
                <div class="flex space-x-3">
                    <p class="font-heading">Get started</p>
                    <img src="/icons/arrow.svg" alt="Arrow Icon">
                </div>
            </div>
            <div class="relative w-1/2">
                <img src="/images/monetization.png" alt="Monetize your way" class="w-full h-full">
                <div class="px-9 py-8 bg-white rounded-3xl absolute -top-4 -left-6 text-black flex flex-col space-y-3">
                    <div class="flex w-full justify-between py-4 px-3 space-x-16 font-semibold font-heading bg-gray-100 rounded-xl hover:bg-blue-200 hover:text-primary transition duration-300 transform hover:-translate-y-1 hover:translate-x-1 hover:shadow-xl">
                        <p>Donate</p>
                        <p>$45</p>
                    </div>
                    <div class="flex w-full justify-between py-4 px-3 space-x-16 font-semibold font-heading bg-gray-100 rounded-xl hover:bg-blue-200 hover:text-primary transition duration-300 transform hover:-translate-y-1 hover:translate-x-1 hover:shadow-xl">
                        <p>Donate</p>
                        <p>$75</p>
                    </div>
                    <div class="flex w-full justify-between py-4 px-3 space-x-16 font-semibold font-heading bg-gray-100 rounded-xl hover:bg-blue-200 hover:text-primary transition duration-300 transform hover:-translate-y-1 hover:translate-x-1 hover:shadow-xl">
                        <p>Donate</p>
                        <p>$15</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="flex space-x-24">
            <div class="flex w-1/2 relative">
                <img src="/images/optimized.png" alt="Optimized for Growth" class="w-full h-full">
                <div class="px-4 py-3 bg-white absolute -top-4 -right-4 rounded-2xl">
                    <div class="relative">
                        <img src="/icons/email-black.svg" alt="Email Icon" class="w-8 h-6">
                        <span class="absolute -top-2 -right-2 bg-primary rounded-full text-xs px-[6px] py-[1px] font-heading font-bold">1</span>
                    </div>
                </div>
            </div>
            <div class="flex flex-col justify-center w-1/2 space-y-6">
                <h5 class="font-semibold text-3xl">Optimized for Growth</h5>
                <p>
                    Set up subscriptions, rentals, or one-time buys for access to your VOD and live streams. Create exclusive experiences for your subscribers with coupons and promotions. One predictable fee, transparent pricing, and same-day setup.
                </p>
                <div class="flex space-x-3">
                    <p class="font-heading">Get started</p>
                    <img src="/icons/arrow.svg" alt="Arrow Icon">
                </div>
            </div>
        </div>
    </div>
</section>

