<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="flex flex-col md:flex-row justify-between items-start mb-16 gap-8">
			<div>
				<h2 class="text-3xl font-medium mb-2">Maximale Qualität zu jedem Preis</h2>
				<p class="text-xl text-muted font-light">Erstklassige Ergebnisse bei jedem Auftrag</p>
			</div>
			<div class="max-w-xs text-[10px] text-muted leading-relaxed border-l border-border pl-4">
				<strong class="text-foreground block mb-1">Über diesen Vergleich</strong>
				Dieser Vergleich basiert auf 2.500 Service-Fällen, die von Fachleuten in unterschiedlichen Bereichen (z.B. Steinschlagreparatur, Scheibentausch, Tönung) bewertet wurden. Jede Service-Leistung wurde nach Qualität, Schnelligkeit und Kundenzufriedenheit geprüft und ist eindeutig nachvollziehbar dokumentiert. Die Ergebnisse spiegeln einen Querschnitt aus 100 ausgewählten Aufträgen wider. Mehr dazu in unserem <a href="#" class="underline">aktuellen Blog</a>.
			</div>
		</div>

		<div class="relative w-full h-[500px] border border-border bg-primary-50/30 p-8 font-mono text-xs">
			<!-- Chart Grid -->
			<div class="absolute inset-0 p-8 grid grid-rows-6 grid-cols-1">
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
			</div>
			
			<!-- Y Axis Label -->
			<div class="absolute left-2 top-1/2 -translate-y-1/2 -rotate-90 text-muted origin-center whitespace-nowrap">
				QUALITÄT (%)
			</div>

			<!-- X Axis Label -->
			<div class="absolute bottom-2 left-1/2 -translate-x-1/2 text-muted">
				PREIS (EUR)
			</div>

			<!-- Top Left Legend -->
			<div class="absolute top-4 left-4 flex gap-4 text-[10px] text-muted">
				<span class="bg-gray-200 px-1 rounded text-foreground">Steinschlag</span>
				<span>Kompletter Austausch</span>
				<span>Tönung</span>
				<span>Schutzfolien</span>
				<span>Kundenzufriedenheit</span>
			</div>

			<!-- Data Points -->
			
			<!-- Autoglas stach (The Winner) -->
			<div class="absolute top-[15%] left-[15%] flex flex-col items-center group cursor-pointer z-10">
				<div class="flex items-center gap-2 mb-1">
					<span class="text-accent font-bold">AUTOGLAS STACH</span>
				</div>
				<div class="w-3 h-3 bg-accent rounded-full shadow-[0_0_0_4px_rgba(255,68,0,0.2)]"></div>
				<div class="mt-1 text-[10px] text-accent">97% / 100€</div>
			</div>

			<!-- OpenAI GPT-4 -->
			<div class="absolute top-[25%] left-[45%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-0 group-hover:opacity-100 transition-opacity">
					<span class="font-bold">GLASKETTE</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">92% / 170€</div>
			</div>

			<!-- Perplexity -->
			<div class="absolute top-[55%] left-[35%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">MOBILGLAS</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">75% / 120€</div>
			</div>

			<!-- ERA -->
			<div class="absolute top-[65%] left-[40%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">AUTOGLAS PRO</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">68% / 135€</div>
			</div>

			<!-- TAVILY -->
			<div class="absolute top-[80%] right-[20%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px]">GLASFIX</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">62% / 210€</div>
			</div>

			<!-- Bottom Right Legend -->
			<div class="absolute bottom-4 right-4 flex items-center gap-4 text-[10px]">
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 bg-accent rounded-full"></div>
					<span class="text-accent font-bold">AUTOGLAS STACH</span>
				</div>
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 bg-black rounded-full"></div>
					<span class="text-muted">ANDERE</span>
				</div>
			</div>
		</div>
	</div>
</section>
