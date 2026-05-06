<script lang="ts">
	import FeatureBlock from './FeatureBlock.svelte';
</script>

<!-- Block 1: Autoglas-Service für Ihr Fahrzeug -->
<FeatureBlock 
	title="Autoglas-Service für Ihr Fahrzeug" 
	description="Professionelle Reparatur bei Steinschlag und schneller Scheibentausch – zuverlässig, präzise und regional für Sie da."
	buttons={[
		{ text: "JETZT TERMIN VEREINBAREN", icon: true },
		{ text: "MEHR ERFAHREN" }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-4 font-mono text-xs">
		<div class="flex items-center gap-2 border-b border-border pb-2 mb-4">
			<span class="text-accent">></span>
			<span class="text-muted">Stach-Team</span>
			<span class="w-2 h-4 bg-accent animate-pulse"></span>
		</div>
		<div class="space-y-2 opacity-50">
			<div class="h-2 bg-gray-100 w-3/4 rounded"></div>
			<div class="h-2 bg-gray-100 w-1/2 rounded"></div>
			<div class="h-2 bg-gray-100 w-5/6 rounded"></div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 2: Schnelle und exakte Reparatur -->
<FeatureBlock 
	title="Schnelle und exakte Reparatur" 
	description="Wir beheben Steinschlagschäden gründlich, tauschen Ihre Scheiben fachgerecht – bequem und effizient zum fairen Preis."
	buttons={[
		{ text: "ANGEBOT ANFORDERN", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full max-w-md bg-white border border-border rounded shadow-sm p-6 flex flex-col gap-4">
		<div class="flex items-center gap-2 text-xs font-mono text-muted">
			<div class="w-4 h-4 border border-current rounded-sm flex items-center justify-center">
				<div class="w-2 h-2 bg-current rounded-[1px]"></div>
			</div>
			Scheibenprüfung läuft ...
		</div>
		<div class="w-full bg-gray-100 h-1.5 rounded-full overflow-hidden">
			<div class="bg-accent h-full w-2/3"></div>
		</div>
		<div class="flex gap-1">
			{#each Array(20) as _}
				<div class="w-1 h-3 bg-gray-200"></div>
			{/each}
		</div>
		<div class="mt-2 flex items-center gap-2 text-[10px] text-muted font-mono uppercase">
			<span class="w-3 h-3 border border-current rounded-full flex items-center justify-center">i</span>
			IN BEARBEITUNG
		</div>
	</div>
</FeatureBlock>

<!-- Block 3: Scheiben-Tönung und Schutzfolien -->
<FeatureBlock 
	title="Scheiben-Tönung und Schutzfolien" 
	description="Individuelle Tönungsfolien und effektive Schutzlösungen für Ihr Fahrzeug – Qualität und Optik aus einer Hand."
	buttons={[
		{ text: "JETZT ANFRAGEN", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px]">
		<div class="grid grid-cols-4 gap-2 p-2 border-b border-border bg-gray-50 text-muted">
			<div>NR</div>
			<div>FAHRZEUG</div>
			<div>TÖNUNG</div>
			<div>FOLIENSCHUTZ</div>
		</div>
		{#each [1, 2, 3, 4, 5, 6] as i}
			<div class="grid grid-cols-4 gap-2 p-2 border-b border-border/50 items-center">
				<div class="text-muted">{i}</div>
				<div class="flex items-center gap-2">
					<div class="w-3 h-3 rounded-full bg-blue-400/20"></div>
					<span class="text-blue-600">Fahrzeug {i}</span>
				</div>
				<div class="h-1.5 w-8 bg-gray-100 rounded"></div>
				<div class="h-1.5 w-8 bg-gray-100 rounded"></div>
			</div>
		{/each}
	</div>
</FeatureBlock>

<!-- Block 4: Reparatur, Austausch & Versicherungsservice -->
<FeatureBlock 
	title="Reparatur, Austausch & Versicherungsservice" 
	description="Wir übernehmen die komplette Kommunikation mit Ihrer Versicherung: Einfach, schnell und für Sie bequem."
	buttons={[
		{ text: "JETZT KONTAKTIEREN", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px]">
		<div class="grid grid-cols-4 gap-2 p-2 border-b border-border bg-gray-50 text-muted">
			<div>NR</div>
			<div>KUNDE</div>
			<div>SCHADEN GEMELDET</div>
			<div>VERSICHERT</div>
		</div>
		{#each [1, 2, 3, 4, 5, 6] as i}
			<div class="grid grid-cols-4 gap-2 p-2 border-b border-border/50 items-center">
				<div class="text-muted">{i}</div>
				<div class="flex items-center gap-2">
					<div class="w-3 h-3 rounded-full bg-indigo-400/20"></div>
					<span class="text-indigo-600">Kunde {i}</span>
				</div>
				<div class="h-1.5 w-12 bg-gray-200 rounded animate-pulse"></div>
				<div class="h-1.5 w-8 bg-gray-200 rounded animate-pulse"></div>
			</div>
		{/each}
	</div>
</FeatureBlock>

<!-- Block 5: Ihre Mobilität, unser Service -->
<FeatureBlock 
	title="Ihre Mobilität, unser Service" 
	description="Ob vor Ort oder mobil: Wir halten Sie in Franken flexibel – mit schnellen Reparaturen und zuverlässiger Betreuung."
	buttons={[
		{ text: "MOBILEN SERVICE BUCHEN", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-4 flex flex-col gap-4">
		<div class="flex items-center justify-between border-b border-border pb-2">
			<div class="text-[10px] font-mono text-muted flex items-center gap-2">
				<span class="w-2 h-2 bg-green-500 rounded-full"></span>
				Schnelle Hilfe bei Glasschaden
			</div>
		</div>
		
		<!-- Calendar/Grid visual -->
		<div class="grid grid-cols-12 gap-1">
			{#each Array(48) as _, i}
				<div class="aspect-square rounded-[1px] {i === 42 ? 'bg-accent' : (Math.random() > 0.8 ? 'bg-blue-200' : 'bg-gray-50')}"></div>
			{/each}
		</div>

		<div class="mt-auto space-y-2">
			<div class="flex items-center gap-2 text-[10px] text-muted font-mono">
				<span class="w-3 h-3 border border-current rounded-full flex items-center justify-center text-[8px]">!</span>
				Kein Termin frei?
			</div>
			<div class="bg-gray-50 p-2 rounded border border-border flex gap-2 items-center">
				<div class="w-4 h-4 bg-gray-200 rounded"></div>
				<div class="h-1.5 w-24 bg-gray-200 rounded"></div>
			</div>
		</div>
	</div>
</FeatureBlock>
