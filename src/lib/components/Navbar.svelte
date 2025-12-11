<script>
    import { onMount } from 'svelte';

    let isScrolled = false;

    onMount(() => {
        const handleScroll = () => {
            isScrolled = window.scrollY > 20;
        };
        window.addEventListener('scroll', handleScroll);
        return () => window.removeEventListener('scroll', handleScroll);
    });
</script>

<nav class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 {isScrolled ? 'bg-black/80 backdrop-blur-md py-4' : 'bg-transparent py-6'}">
    <div class="container mx-auto px-6 flex items-center justify-between">
        <!-- Logo -->
        <a href="/" class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M17.2235 12.5566C17.2235 15.0114 15.2335 17.0015 12.7787 17.0015C10.3239 17.0015 8.33384 15.0114 8.33384 12.5566H4.77795C4.77795 16.9753 8.36002 20.5574 12.7787 20.5574C17.1974 20.5574 20.7794 16.9753 20.7794 12.5566C20.7794 8.13797 17.1974 4.55591 12.7787 4.55591V8.11179C15.2335 8.11179 17.2235 10.1018 17.2235 12.5566Z"
                    fill="currentColor"
                />
                <path
                    opacity="0.5"
                    d="M7.44485 2.77795C7.44485 5.23278 5.45483 7.22281 3 7.22281V10.7787C7.41869 10.7787 11.0007 7.19663 11.0007 2.77795H7.44485Z"
                    fill="currentColor"
                />
            </svg>
            IMOS
        </a>

        <!-- Links -->
        <div class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-300">
            <a href="#" class="hover:text-white transition-colors">Platform</a>
            <a href="#" class="hover:text-white transition-colors">Solutions</a>
            <a href="#" class="hover:text-white transition-colors">Property Managers</a>
            <a href="#" class="hover:text-white transition-colors">Resources</a>
            <a href="#" class="hover:text-white transition-colors">About</a>
        </div>

        <!-- CTA -->
        <a href="#" class="hidden md:flex items-center gap-1 text-sm font-medium text-white hover:text-[var(--color-imos-primary)] transition-colors">
            Get Started
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <path d="M5 12h14M12 5l7 7-7 7"/>
            </svg>
        </a>
        
        <!-- Mobile Menu Button -->
        <button class="md:hidden text-white">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <line x1="3" y1="12" x2="21" y2="12"></line>
                <line x1="3" y1="6" x2="21" y2="6"></line>
                <line x1="3" y1="18" x2="21" y2="18"></line>
            </svg>
        </button>
    </div>
</nav>
