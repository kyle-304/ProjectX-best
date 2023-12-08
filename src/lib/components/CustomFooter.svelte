<script lang="ts">
    import {Facebook, Twitter} from 'lucide-svelte'
</script>

<footer>
    <div class="container px-5 py-8 mx-auto flex items-center sm:flex-row flex-col">
        <a class=" flex title-font font-medium items-center md:justify-start justify-center" href="/">
            <!-- you can put the logo here -->
            <span class="ml-3 text-lg"> PROJECT X</span>
        </a>
        <p class="text-sm text-gray-400 sm:ml-4 sm:pl-4 sm:border-l-2 sm:border-gray-800 sm:py-2 sm:mt-0 mt-4">© 2023 PROJECT X Driving School —
            <a href="/" class="text-gray-500 ml-1" target="_blank" rel="noopener noreferrer">@socialmedia</a>
        </p>
        <!-- social media -->
        <span class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start">
            <a href="/" class="px-2">
                <Facebook strokeWidth = {1}/>
            </a>
            <a href="/" class="px-2">
                <Twitter strokeWidth = {1}/>
            </a>
        </span>

    </div>
</footer>