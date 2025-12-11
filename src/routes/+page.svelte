<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-imos-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-imos-primary)]"></span>
                        <span class="text-white text-sm font-medium">AI-Powered</span>
                        <span class="text-gray-400 text-sm">Instant Valuations</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Property valuations in seconds, not days.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        IMOS delivers instant property valuations through AI-powered comparative market analysis and real-time data integration. Built for property managers who need accurate valuations without the wait.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Get started
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            See how it works
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 - Property Valuation -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500">Property Value</div>
                                <div class="px-3 py-1.5 bg-[var(--color-imos-primary)]/20 rounded-lg text-[var(--color-imos-primary)] text-sm flex items-center justify-center font-bold">$2.4M</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-32 bg-gradient-to-br from-gray-100 to-gray-200 rounded-lg w-full flex items-center justify-center">
                                    <svg class="w-12 h-12 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg>
                                </div>
                                <div class="text-sm font-medium text-gray-900">123 Main Street, Apt 4B</div>
                                <div class="text-xs text-gray-500">2 bed • 2 bath • 1,200 sq ft</div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - Comparative Analysis -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-gradient-to-br from-[var(--color-imos-primary)] to-cyan-600 p-6">
                                <div class="flex justify-between items-center text-white">
                                    <div class="text-sm font-semibold">Market Analysis</div>
                                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path></svg>
                                </div>
                            </div>
                            <div class="p-6 flex-grow space-y-4">
                                <div class="flex justify-between items-center">
                                    <span class="text-xs text-gray-500">Comparable Properties</span>
                                    <span class="text-sm font-bold text-gray-900">24 found</span>
                                </div>
                                <div class="space-y-2">
                                    <div class="flex items-center gap-2">
                                        <div class="w-2 h-2 rounded-full bg-green-500"></div>
                                        <div class="h-2 flex-grow bg-gray-100 rounded"></div>
                                        <span class="text-xs text-gray-600">$2.5M</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <div class="w-2 h-2 rounded-full bg-[var(--color-imos-primary)]"></div>
                                        <div class="h-2 flex-grow bg-gray-100 rounded"></div>
                                        <span class="text-xs text-gray-600">$2.4M</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <div class="w-2 h-2 rounded-full bg-blue-500"></div>
                                        <div class="h-2 flex-grow bg-gray-100 rounded"></div>
                                        <span class="text-xs text-gray-600">$2.3M</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 - Real-time Data -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500">Market Trends</div>
                                <div class="px-2 py-1 bg-green-100 rounded text-green-700 text-xs font-semibold">↑ 12%</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-32 bg-gray-50 rounded-lg w-full flex items-end gap-1 p-4">
                                    {#each [40, 45, 42, 55, 60, 58, 70, 75] as height}
                                        <div class="flex-1 bg-gradient-to-t from-[var(--color-imos-primary)] to-cyan-400 rounded-t" style="height: {height}%"></div>
                                    {/each}
                                </div>
                                <div class="text-xs text-gray-500">Last updated: 2 minutes ago</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by property managers across the country</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-50 grayscale">
                    <!-- Property Management Companies -->
                    <div class="h-6 md:h-8 text-white font-bold text-xl">GREYSTAR</div>
                    <div class="h-6 md:h-8 text-white font-bold text-xl">AVALON</div>
                    <div class="h-6 md:h-8 text-white font-bold text-xl">EQUITY</div>
                    <div class="h-6 md:h-8 text-white font-bold text-xl">CAMDEN</div>
                    <div class="h-6 md:h-8 text-white font-bold text-xl">BOZZUTO</div>
                </div>
            </div>
        </section>

        <!-- IMOS Platform Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-imos-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">IMOS Platform</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Property valuation.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Powered by AI.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Teal Card -->
                    <div class="bg-gradient-to-br from-cyan-600 to-teal-700 rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Property Card -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="absolute top-0 right-0 p-4 opacity-30">
                                    <svg class="w-16 h-16 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg>
                                </div>
                                <div class="space-y-3 relative z-10">
                                    <div class="text-white/60 text-xs uppercase tracking-wider font-medium">Estimated Value</div>
                                    <div class="text-white font-bold text-3xl">$2,450,000</div>
                                    <div class="flex items-center gap-2 text-white/80 text-sm">
                                        <svg class="w-4 h-4 text-green-300" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M12 7a1 1 0 110-2h5a1 1 0 011 1v5a1 1 0 11-2 0V8.414l-4.293 4.293a1 1 0 01-1.414 0L8 10.414l-4.293 4.293a1 1 0 01-1.414-1.414l5-5a1 1 0 011.414 0L11 10.586 14.586 7H12z" clip-rule="evenodd"></path></svg>
                                        <span>12% vs last quarter</span>
                                    </div>
                                </div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-cyan-100 flex items-center justify-center text-cyan-600">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"></path><path fill-rule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm9.707 5.707a1 1 0 00-1.414-1.414L9 12.586l-1.293-1.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                                    </div>
                                    Instant valuations
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-teal-500/30 flex items-center justify-center text-teal-200">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M2 11a1 1 0 011-1h2a1 1 0 011 1v5a1 1 0 01-1 1H3a1 1 0 01-1-1v-5zM8 7a1 1 0 011-1h2a1 1 0 011 1v9a1 1 0 01-1 1H9a1 1 0 01-1-1V7zM14 4a1 1 0 011-1h2a1 1 0 011 1v12a1 1 0 01-1 1h-2a1 1 0 01-1-1V4z"></path></svg>
                                    </div>
                                    Market analysis
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Scale with automation.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Property values change constantly. IMOS provides real-time valuations powered by AI and market data, helping you make informed decisions instantly without waiting for traditional appraisals.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">IMOS Features</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Everything you need to manage properties.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">All in one place.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Explore our platform
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-imos-primary)]"></span>
                                AI Valuations
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Market Analysis</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Property Showcase</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Tenant Communication</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Real-Time Data</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Mobile Tools</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="AI Valuations" 
                            description="Get instant property values. IMOS uses AI-powered comparative market analysis to deliver accurate property valuations in seconds, not days."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Market Analysis" 
                            description="Real-time market insights. Access comprehensive market data and trends to make informed decisions about your properties and portfolio."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Property Showcase" 
                            description="Mobile-first property tools. Simple, beautiful property showcase tools that help you present properties professionally without technical expertise."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Tenant Communication" 
                            description="Centralized messaging hub. Streamline tenant communications with a unified platform that keeps all conversations organized and accessible."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Real-Time Data" 
                            description="Always up-to-date information. Integration with real-time data sources ensures your property valuations and market insights are always current."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Mobile Tools" 
                            description="Manage on the go. Access all IMOS features from your mobile device with our intuitive mobile-first interface designed for property managers."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- Scale Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-cyan-100 to-teal-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-cyan-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Scale from 50 to 50,000 properties with automation expertise built in.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        See how we scale
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by property managers nationwide. See how they use IMOS.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Card (Large) -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">GREYSTAR</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-imos-primary)] flex items-center justify-center text-black font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
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
                                    </div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-4 max-w-md">
                                    How Greystar reduced valuation time from weeks to seconds with IMOS
                                </h3>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-end">
                                <div class="absolute inset-0 bg-gradient-to-br from-cyan-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white/80 text-sm mb-4">"IMOS transformed how we value properties. What used to take 2-3 weeks now happens instantly."</p>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors ml-auto">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-end">
                                <div class="absolute inset-0 bg-gradient-to-br from-teal-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white/80 text-sm mb-4">"Simple mobile tools that our entire team adopted in days, not months."</p>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors ml-auto">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-cyan-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-teal-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Manage properties smarter. <span class="text-[var(--color-imos-primary)]">Scale faster.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Built for property managers who need powerful tools without the complexity. Simple mobile-first design that your team will actually use.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path></svg>
                            Learn More
                        </div>
                    </div>
                </div>

                <!-- Integrations -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        MLS data. Property records.<br>
                        Market analytics. <span class="text-gray-400">All your data sources,<br>seamlessly integrated.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        Explore all integrations
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['MLS', 'Zillow', 'Redfin', 'CoreLogic', 'RealPage', 'Yardi', 'CoStar', 'Rentometer'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl uppercase tracking-wider">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn more about property management.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-cyan-100 to-teal-200 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <svg class="w-24 h-24 text-cyan-600 opacity-50" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Industry Insights</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-cyan-600 transition-colors">How AI is transforming property valuations in multifamily real estate</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-cyan-400 blur-xl opacity-80"></div>
                                    <div class="w-20 h-20 rounded-full bg-teal-400 blur-xl opacity-80"></div>
                                    <div class="w-12 h-12 rounded-full bg-blue-400 blur-xl opacity-80"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Best Practices</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-cyan-600 transition-colors">The complete guide to scaling property management operations</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

