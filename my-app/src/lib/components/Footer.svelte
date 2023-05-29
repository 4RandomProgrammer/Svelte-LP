<footer class="py-20 bg-gray-100">
    <div class="max-w-screen-xl mx-auto flex justify-between">
        <div class="flex flex-col space-y-6 w-1/4">
            <img src="/images/screeno-footer.svg" width={98} height={13} alt="Screeno logo">
            <p>Streaming and Video Platform</p>
            <div class="flex space-x-4">
                <img src="/icons/facebook.svg" alt="facebook logo">
                <img src="/icons/instagram.svg" alt="facebook logo">
            </div>
        </div>
        <div class="w-1/4 flex flex-col space-y-6">
            <h6 class="font-semibold font-heading">Contact Info</h6>
            <div class="flex  items-start space-x-2">
                <img src="/icons/location.svg" alt="Location Icons">
                <p>2715 Ash Dr. San Jose, South Dakota 83475</p>
            </div>
            <div class="flex items-start space-x-2">
                <img src="/icons/phone.svg" alt="Location Icons">
                <p>(219) 555-0114</p>
            </div>
            <div class="flex items-start space-x-2">
                <img src="/icons/email-blue.svg" alt="Location Icons">
                <p>info@screeno.com</p>
            </div>
        </div>
        <div class="w-1/2 flex flex-col space-y-6">
            <h6 class="font-heading font-semibold">Get in touch</h6>
            <form class="flex flex-col space-y-6" action="">
                <input type="text" name="" placeholder="Your Name">
                <input type="text" name="" placeholder="Your Email">
                <textarea placeholder="Your Message" rows={5}></textarea>
                <div class="">
                    <button class="primary font-heading font-semibold px-8">Send</button>
                </div>
            </form>
        </div>
    </div>
</footer>
<div class="border-t-[1px] border-neutral-500 text-center">
    <p>©2022 Screeno Ltd, All rights reserved</p>
</div>

<style lang="postcss">
    input,textarea {
        @apply text-neutral-700 py-3 px-4 outline-none rounded-xl border-[1px] border-white focus:border-primary transition duration-300;
    }
</style>