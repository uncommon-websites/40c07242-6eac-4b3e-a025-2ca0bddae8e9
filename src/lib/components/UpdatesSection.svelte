<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-16">
			
			<!-- Left Column: CTA & Visual -->
			<div class="flex flex-col h-full">
				<div class="mb-8">
					<p class="font-mono text-xs text-muted mb-4">Jetzt Termin sichern</p>
					<h2 class="text-2xl font-medium mb-4">Ihr regionaler Profi für Autoglas</h2>
					<p class="text-muted font-light mb-8 text-sm leading-relaxed max-w-md">
						Autoglas Stach bietet schnelle Steinschlag-Reparatur, professionellen Scheibenwechsel und hochwertige Scheibentönung. Ihr Fahrzeug in besten Händen – flexibel vor Ort oder in unserer Werkstatt, auf Wunsch mit Direktabwicklung über die Versicherung.
					</p>
					<div class="flex gap-3 mb-12">
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							TERMIN VEREINBAREN
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">T</span>
						</button>
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							JETZT KONTAKTIEREN
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">K</span>
						</button>
					</div>
				</div>
				
				<!-- Barcode Visual -->
				<div class="mt-auto w-full h-48 bg-black relative overflow-hidden flex items-center justify-center">
					{#each Array(100) as _, i}
						<div 
							class="h-full bg-white absolute" 
							style="
								left: {i}%; 
								width: {Math.random() * 2}%; 
								opacity: {Math.random()};
							"
						></div>
					{/each}
					<div class="absolute inset-0 flex items-center justify-center">
						<div class="bg-black text-white font-mono text-[10px] px-2 py-1 z-10">
							autoglas-stach.de
						</div>
					</div>
				</div>
			</div>

			<!-- Right Column: Updates -->
			<div>
				<p class="font-mono text-xs text-muted mb-8">Neues bei uns</p>
				
				<div class="space-y-12">
					<!-- Update 1 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">April 8</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Unsere mobile Steinschlag-Reparatur ist jetzt verfügbar</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Keine Zeit für die Werkstatt? Wir reparieren Steinschläge jetzt auch direkt bei Ihnen vor Ort! Schnell, unkompliziert und mit hochwertigen Materialien – damit Sie schnell wieder sicher unterwegs sind.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Produkt-Update</span>
						</div>
					</div>

					<!-- Update 2 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">März 26</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Neu: Scheibentönung für besseren Schutz</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Ab sofort bieten wir professionelle Scheibentönung an – für Hitzeschutz, Blickschutz und mehr Sicherheit im Straßenverkehr. Wählen Sie aus verschiedenen Tönungsgraden, optimal angepasst auf Ihr Fahrzeug und Ihre Wünsche.
							</p>
							<div class="flex gap-2">
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Produkt-Update</span>
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Service</span>
							</div>
						</div>
					</div>

					<!-- Update 3 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">März 12</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Direkte Versicherungsabwicklung</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Noch einfacher für Sie: Auf Wunsch wickeln wir die Reparaturkosten direkt mit Ihrer Versicherung ab – ganz ohne Aufwand für Sie. Fragen Sie uns gerne bei der Terminvereinbarung.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Service</span>
						</div>
					</div>

					<!-- Update 4 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">Februar 28</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Wir sind für Sie in Franken unterwegs</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Autoglas Stach ist Ihr regionaler Autoglas-Partner für Nürnberg, Bamberg, Haßfurt und Umgebung. Verlassen Sie sich auf schnellen, zuverlässigen und freundlichen Service – vom Steinschlag bis zum kompletten Scheibentausch.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">News</span>
						</div>
					</div>
				</div>
			</div>

		</div>
	</div>
</section>
