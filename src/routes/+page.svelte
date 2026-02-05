<script lang="ts">
	// Data for Platform Capabilities
	const capabilities = [
		{
			title: "Simulated Worlds",
			desc: "High-fidelity virtual environments that accurately model real-world physics, interactions, and edge cases. Train agents on diverse scenarios without the cost and constraints of physical infrastructure."
		},
		{
			title: "Real-World Challenges",
			desc: "Task-based evaluations that test agent performance against actual work requirements. Validate capabilities before deployment with benchmarks that matter."
		},
		{
			title: "Embodied Agent Training",
			desc: "Purpose-built for AI systems that take actions and interact with environments. From robotic manipulation to complex multi-agent coordination, Fleet provides the training gyms agents need to master real tasks."
		}
	];

	// Data for Customer Segments
	const segments = [
		{
			title: "Frontier Labs",
			desc: "Leading AI research organizations use Fleet to scale their training infrastructure. Access diverse environments without building simulation pipelines from scratch.",
			icon: "🔬"
		},
		{
			title: "Hyperscalers",
			desc: "Major cloud providers integrate Fleet's simulation environments to offer AI training capabilities at scale. Production-ready infrastructure for enterprise customers.",
			icon: "☁️"
		},
		{
			title: "Enterprises",
			desc: "Organizations deploying embodied AI use Fleet to train and validate agents for specific operational contexts. Reduce deployment risk with realistic pre-training.",
			icon: "🏢"
		}
	];

	// Data for Value Propositions
	const values = [
		{
			title: "High-Fidelity Simulation",
			desc: "Overcome simulation fidelity concerns with environments validated against real-world benchmarks. Our training gyms accurately model the complexity agents will face in deployment."
		},
		{
			title: "Diverse Training Data",
			desc: "Access a wide range of scenarios and edge cases without waiting for real-world data collection. Scale your training across environments that would be impractical or impossible to build physically."
		},
		{
			title: "Rapid Environment Creation",
			desc: "Spin up new training scenarios in hours, not months. Fleet's infrastructure lets researchers focus on model development instead of simulation engineering."
		},
		{
			title: "Production Infrastructure",
			desc: "Built for reliability and scale. Fleet runs production systems that frontier labs and enterprises depend on daily. All systems operational, monitored 24/7."
		}
	];

	// Data for Getting Started
	const steps = [
		{
			number: "01",
			title: "Book a Demo",
			desc: "Schedule a technical walkthrough with our team. We'll discuss your training requirements and show how Fleet's environments can accelerate your research."
		},
		{
			number: "02",
			title: "Pilot Environment",
			desc: "Start with a focused pilot on your specific use case. We'll work with you to configure environments that match your agent's operational context."
		},
		{
			number: "03",
			title: "Scale Training",
			desc: "Expand to full production training infrastructure. Fleet scales with your needs, from initial experiments to training runs across thousands of parallel environments."
		},
		{
			number: "04",
			title: "Continuous Evaluation",
			desc: "Use Fleet's real-world challenges to continuously validate agent performance. Track progress against benchmarks that matter for deployment."
		}
	];
</script>

<div class="min-h-screen bg-[#fafaf8] text-[#475569] font-sans selection:bg-sky-500 selection:text-white">
	<!-- Header -->
	<header class="px-4 md:px-6 py-6 max-w-[1920px] mx-auto flex justify-between items-center">
		<a href="/" class="flex items-center gap-2 text-black hover:text-sky-600 transition-colors">
			<span class="text-2xl font-bold tracking-tight">Fleet</span>
		</a>
		<nav class="hidden md:flex items-center gap-8 text-sm font-medium">
			<a href="#platform" class="hover:text-black transition-colors">Platform</a>
			<a href="#customers" class="hover:text-black transition-colors">Customers</a>
			<a href="https://docs.fleetai.com" class="hover:text-black transition-colors">Docs</a>
			<a href="https://status.fleetai.com" class="hover:text-black transition-colors">Status</a>
		</nav>
	</header>

	<!-- Hero Section - ALREADY CUSTOMIZED, DO NOT MODIFY -->
	<main class="w-full px-4 md:px-6 py-6 max-w-[1920px] mx-auto">
		<!-- Typography Section -->
		<div class="flex flex-col mb-12 md:mb-16">
			<!-- Main Heading -->
			<h1 class="text-[15.5vw] leading-[0.8] font-bold tracking-tighter text-black -ml-[0.05em]">
				Fleets
			</h1>
			
			<!-- Subheading -->
			<div class="flex justify-end mt-8 md:mt-10">
				<div class="w-full md:w-1/2 pl-1">
					<p class="text-2xl md:text-3xl lg:text-4xl font-medium leading-tight tracking-tight max-w-2xl text-[#64748b]">
						High-fidelity simulated environments enabling AI agent to master real-world tasks at scale.
					</p>
				</div>
			</div>
		</div>

		<!-- Hero Image Section -->
		<div class="relative w-full h-[50vh] md:h-[75vh] overflow-hidden">
			<img src="/generated/image-abstract-red-rothko-painting-with-deep-c-1770241671132-0.webp" alt="Abstract red Rothko painting" class="w-full h-full object-fill object-center">
			
			<!-- Floating Action Button -->
			<div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 z-10">
				<button class="bg-white text-[#0ea5e9] border border-[#0ea5e9] px-8 py-3 rounded-full text-sm md:text-base font-medium hover:bg-gray-50 transition-colors duration-200">
					Book a Demo
				</button>
			</div>
		</div>
	</main>

	<!-- Introduction -->
	<section class="px-4 md:px-6 py-24 max-w-7xl mx-auto">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
			<div>
				<h2 class="text-4xl md:text-6xl font-bold tracking-tight mb-8 leading-tight text-black">
					The scale out of environments
				</h2>
				<p class="text-lg md:text-xl leading-relaxed mb-6">
					Fleet builds high-fidelity virtual environments where embodied AI agents can safely learn, test, and evolve.
				</p>
				<p class="text-base leading-relaxed text-gray-600 mb-8">
					Real-world performance starts in simulation. Fleet gives researchers the environments they need to teach agents real tasks—without waiting for real world data.
				</p>
				<div class="flex flex-wrap gap-4 items-center text-sm text-gray-500">
					<span class="font-medium text-black">Backed by</span>
					<span>Sequoia Capital</span>
					<span>•</span>
					<span>Menlo Ventures</span>
					<span>•</span>
					<span>SV Angel</span>
				</div>
			</div>
			<div class="aspect-[4/3] overflow-hidden rounded-lg">
				<img 
					src="/generated/image-advanced-virtual-reality-simulation-envi-1770236909180-0.webp" 
					alt="High-fidelity simulation environment" 
					class="w-full h-full object-cover"
				/>
			</div>
		</div>
	</section>

	<!-- Platform Capabilities -->
	<section id="platform" class="px-4 md:px-6 py-24 max-w-7xl mx-auto">
		<h2 class="text-3xl md:text-5xl font-bold tracking-tight mb-16 text-black">Platform Capabilities</h2>
		<div class="grid grid-cols-1 md:grid-cols-3 gap-8 md:gap-12">
			{#each capabilities as capability}
				<div class="space-y-4">
					<h3 class="text-xl md:text-2xl font-bold text-black">{capability.title}</h3>
					<p class="text-sm md:text-base leading-relaxed text-gray-600">{capability.desc}</p>
				</div>
			{/each}
		</div>
	</section>

	<!-- Feature Showcase -->
	<section class="px-4 md:px-6 py-24 max-w-7xl mx-auto">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center mb-24">
			<div class="order-2 lg:order-1">
				<h3 class="text-3xl md:text-4xl font-bold tracking-tight mb-6 text-black">
					Embodied agents that learn by doing
				</h3>
				<p class="text-base md:text-lg leading-relaxed text-gray-600 mb-6">
					Train AI systems to perform complex physical tasks in high-fidelity virtual environments. From robotic manipulation to multi-agent coordination, Fleet provides the realistic training gyms your agents need.
				</p>
				<p class="text-sm leading-relaxed text-gray-500">
					Our environments accurately model real-world physics, edge cases, and the complexity agents will face in deployment. Validated against real-world benchmarks.
				</p>
			</div>
			<div class="aspect-[4/3] overflow-hidden rounded-lg order-1 lg:order-2">
				<img 
					src="/generated/image-robotic-arm-performing-precise-task-in-a-1770236913747-2.webp" 
					alt="AI agent training in simulated environment" 
					class="w-full h-full object-cover"
				/>
			</div>
		</div>

		<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
			<div class="aspect-[4/3] overflow-hidden rounded-lg">
				<img 
					src="/generated/image-ai-researcher-working-with-multiple-moni-1770236911798-1.webp" 
					alt="AI researcher monitoring training progress" 
					class="w-full h-full object-cover"
				/>
			</div>
			<div>
				<h3 class="text-3xl md:text-4xl font-bold tracking-tight mb-6 text-black">
					Built for AI researchers
				</h3>
				<p class="text-base md:text-lg leading-relaxed text-gray-600 mb-6">
					Focus on model development, not simulation engineering. Fleet's infrastructure lets you spin up new training scenarios in hours, not months.
				</p>
				<p class="text-sm leading-relaxed text-gray-500">
					Access diverse environments without building simulation pipelines from scratch. Scale your training across scenarios that would be impractical to build physically.
				</p>
			</div>
		</div>
	</section>

	<!-- Value Propositions -->
	<section class="px-4 md:px-6 py-24 max-w-7xl mx-auto bg-gray-50/50 rounded-2xl">
		<h2 class="text-3xl md:text-5xl font-bold tracking-tight mb-16 text-black text-center">
			Why Fleet
		</h2>
		<div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-16">
			{#each values as value}
				<div class="space-y-4">
					<h3 class="text-xl md:text-2xl font-bold text-black">{value.title}</h3>
					<p class="text-sm md:text-base leading-relaxed text-gray-600">{value.desc}</p>
				</div>
			{/each}
		</div>
	</section>

	<!-- Full Width Image -->
	<section class="w-full h-[50vh] md:h-[60vh] my-24 overflow-hidden">
		<img 
			src="/generated/image-modern-tech-office-with-collaborative-wo-1770236915727-3.webp" 
			alt="Fleet applied research lab" 
			class="w-full h-full object-cover"
		/>
	</section>

	<!-- Customer Segments -->
	<section id="customers" class="px-4 md:px-6 py-24 max-w-7xl mx-auto">
		<h2 class="text-3xl md:text-5xl font-bold tracking-tight mb-6 text-black">
			Trusted by leaders in AI
		</h2>
		<p class="text-lg md:text-xl text-gray-600 mb-16 max-w-3xl">
			From frontier labs pushing the boundaries of AI research to enterprises deploying embodied agents at scale.
		</p>
		<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
			{#each segments as segment}
				<div class="border border-gray-200 rounded-lg p-8 hover:border-sky-500 transition-colors">
					<div class="text-4xl mb-4">{segment.icon}</div>
					<h3 class="text-xl font-bold mb-4 text-black">{segment.title}</h3>
					<p class="text-sm leading-relaxed text-gray-600">{segment.desc}</p>
				</div>
			{/each}
		</div>
	</section>

	<!-- Team/Culture Image -->
	<section class="px-4 md:px-6 py-24 max-w-7xl mx-auto">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
			<div class="aspect-[3/4] overflow-hidden rounded-lg">
				<img 
					src="/generated/image-diverse-team-of-ai-engineers-and-researc-1770236917668-4.webp" 
					alt="Fleet team collaborating" 
					class="w-full h-full object-cover"
				/>
			</div>
			<div class="space-y-6">
				<h2 class="text-3xl md:text-4xl font-bold tracking-tight text-black">
					An applied research lab
				</h2>
				<p class="text-base md:text-lg leading-relaxed text-gray-600">
					Fleet positions itself as an applied research lab rather than a traditional software company. We focus on fundamental research and development in simulation environments and agent evaluation.
				</p>
				<p class="text-sm leading-relaxed text-gray-500">
					We believe the codification of human goals for agents in evals and environments represents the highest leverage human activity in the build up to ASI. This is critical infrastructure for the AI future.
				</p>
				<div class="pt-4">
					<a href="https://github.com/fleetai" class="inline-flex items-center gap-2 text-sky-600 hover:text-sky-700 font-medium">
						<svg class="w-5 h-5" viewBox="0 0 24 24" fill="currentColor">
							<path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
						</svg>
						View on GitHub
					</a>
				</div>
			</div>
		</div>
	</section>

	<!-- Platform Status & Trust -->
	<section class="px-4 md:px-6 py-24 max-w-7xl mx-auto">
		<div class="bg-gradient-to-br from-sky-50 to-blue-50 rounded-2xl p-8 md:p-12 text-center">
			<div class="inline-flex items-center gap-2 bg-green-100 text-green-800 px-4 py-2 rounded-full text-sm font-medium mb-6">
				<div class="w-2 h-2 bg-green-500 rounded-full animate-pulse"></div>
				All Systems Operational
			</div>
			<h2 class="text-3xl md:text-4xl font-bold tracking-tight mb-4 text-black">
				Production-ready infrastructure
			</h2>
			<p class="text-base md:text-lg text-gray-600 max-w-2xl mx-auto mb-8">
				Fleet runs production systems that frontier labs and enterprises depend on daily. Monitored 24/7 with 99.9% uptime SLA.
			</p>
			<div class="flex flex-wrap justify-center gap-6 text-sm">
				<a href="https://status.fleetai.com" class="text-sky-600 hover:text-sky-700 font-medium flex items-center gap-1">
					View Status Page
					<svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
						<path d="M7 17L17 7M17 7H7M17 7V17"/>
					</svg>
				</a>
				<a href="https://docs.fleetai.com" class="text-sky-600 hover:text-sky-700 font-medium flex items-center gap-1">
					Read Documentation
					<svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
						<path d="M7 17L17 7M17 7H7M17 7V17"/>
					</svg>
				</a>
			</div>
		</div>
	</section>

	<!-- Getting Started -->
	<section class="px-4 md:px-6 py-24 max-w-7xl mx-auto">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-16">
			<!-- Left: Sticky Title + Image -->
			<div class="relative lg:sticky lg:top-12 h-fit self-start">
				<h2 class="text-4xl md:text-6xl font-bold tracking-tight mb-8 leading-tight text-black">Getting Started</h2>
				<div class="aspect-[4/3] relative overflow-hidden rounded-lg">
					<img 
						src="/generated/image-close-up-of-hands-typing-code-on-laptop--1770236920006-5.webp" 
						alt="Developer working with Fleet platform" 
						class="w-full h-full object-cover"
					/>
				</div>
				<p class="mt-6 text-sm text-gray-500">
					Join AI researchers at frontier labs who are already using Fleet to accelerate their training infrastructure.
				</p>
			</div>

			<!-- Right: Steps List -->
			<div class="space-y-12 lg:pt-32">
				<div class="mb-8">
					<h3 class="font-bold text-xl mb-4 text-black">From demo to production</h3>
					<p class="text-sm leading-relaxed text-gray-600">
						Fleet's onboarding process is designed for AI researchers who need to move quickly. From initial demo to production training infrastructure in weeks, not months.
					</p>
				</div>

				{#each steps as step}
					<div class="flex gap-6 border-t border-gray-200 pt-8 first:border-0 first:pt-0">
						<div class="flex-shrink-0 w-10 h-10 rounded-full border-2 border-sky-500 flex items-center justify-center font-bold text-sm bg-white text-sky-600">
							{step.number}
						</div>
						<div>
							<h4 class="font-bold text-lg mb-2 text-black">{step.title}</h4>
							<p class="text-sm leading-relaxed text-gray-600">{step.desc}</p>
						</div>
					</div>
				{/each}

				<div class="pt-8">
					<button class="bg-sky-500 text-white rounded-full px-8 py-3 text-sm font-medium hover:bg-sky-600 transition-colors">
						Book a Demo
					</button>
				</div>
			</div>
		</div>
	</section>

	<!-- CTA Section -->
	<section class="px-4 md:px-6 py-24 max-w-7xl mx-auto">
		<div class="bg-black text-white rounded-2xl p-12 md:p-16 text-center">
			<h2 class="text-3xl md:text-5xl font-bold tracking-tight mb-6">
				Ready to scale your AI training?
			</h2>
			<p class="text-lg md:text-xl text-gray-300 mb-12 max-w-2xl mx-auto">
				Join frontier labs and enterprises using Fleet to build the next generation of embodied AI agents.
			</p>
			<div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
				<button class="bg-white text-black rounded-full px-8 py-4 text-base font-medium hover:bg-gray-100 transition-colors w-full sm:w-auto">
					Book a Demo
				</button>
				<a href="https://docs.fleetai.com" class="border border-white text-white rounded-full px-8 py-4 text-base font-medium hover:bg-white/10 transition-colors w-full sm:w-auto inline-block">
					Read Documentation
				</a>
			</div>
			<p class="mt-8 text-sm text-gray-400">
				Questions? Email us at <a href="mailto:hello@fleetai.com" class="underline hover:text-white">hello@fleetai.com</a>
			</p>
		</div>
	</section>

	<!-- Footer -->
	<footer class="px-4 md:px-6 py-12 border-t border-gray-200 max-w-[1920px] mx-auto">
		<div class="max-w-7xl mx-auto">
			<div class="grid grid-cols-1 md:grid-cols-4 gap-12 mb-12">
				<!-- Brand Column -->
				<div class="md:col-span-2">
					<div class="flex items-center gap-2 mb-4">
						<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-8 h-8 text-black">
							<path
								fill-rule="evenodd"
								clip-rule="evenodd"
								d="M6.99251 12.196C6.85314 12.5757 6.62925 12.9208 6.33682 13.2067H6.33835C6.00191 13.5351 5.58566 13.7756 5.12816 13.9059C4.67065 14.0362 4.18671 14.0522 3.72118 13.9523C3.25564 13.8524 2.82357 13.64 2.46501 13.3345C2.10645 13.0291 1.83299 12.6406 1.66998 12.2051C1.50697 11.7696 1.45969 11.3012 1.5325 10.8432C1.60532 10.3852 1.79587 9.95244 2.08653 9.58516C2.37718 9.21781 2.75852 8.9277 3.1952 8.74177C3.63188 8.55585 4.10979 8.48002 4.58462 8.52142L4.57074 8.50792C5.0567 8.54782 5.54575 8.48407 6.00378 8.32124C6.4618 8.15846 6.87776 7.90043 7.2226 7.56521C7.56746 7.22998 7.83285 6.82564 8.00036 6.38041C8.16786 5.93517 8.23344 5.45976 8.1924 4.98737L8.20628 5.00087C8.15181 4.43594 8.27796 3.86844 8.56753 3.37575C8.85701 2.88307 9.29579 2.48919 9.82407 2.24782C10.3523 2.00645 10.9443 1.92933 11.5192 2.02701C12.0942 2.12467 12.6243 2.39237 13.037 2.79358C13.4497 3.19479 13.7251 3.70999 13.8256 4.26892C13.926 4.82785 13.8467 5.4033 13.5984 5.9168C13.3501 6.4303 12.9449 6.85685 12.4381 7.13828C11.9313 7.41971 11.3474 7.54233 10.7663 7.4894L10.781 7.5029C10.2949 7.46279 9.80563 7.52632 9.34741 7.68904C8.88919 7.85176 8.47309 8.10975 8.12805 8.44499C7.78301 8.78025 7.51742 9.18466 7.34983 9.63001C7.18224 10.0754 7.11669 10.551 7.15774 11.0235L7.14309 11.01C7.1833 11.4112 7.13189 11.8162 6.99251 12.196ZM11.5077 14.7121L11.493 14.6986C11.9061 14.739 12.3232 14.6897 12.7143 14.5543C13.1053 14.4188 13.4605 14.2007 13.7542 13.9154C14.0477 13.6302 14.2726 13.285 14.4121 12.905C14.5518 12.525 14.6028 12.1196 14.5615 11.718L14.5762 11.7315C14.5351 11.2591 14.6007 10.7838 14.7681 10.3385C14.9356 9.89327 15.2011 9.48893 15.5459 9.15368C15.8908 8.8185 16.3068 8.56042 16.7648 8.39767C17.2228 8.23481 17.7118 8.17111 18.1978 8.21099L18.1832 8.19749C18.7645 8.25059 19.3485 8.12801 19.8556 7.84656C20.3627 7.56511 20.7681 7.13845 21.0165 6.62479C21.265 6.11114 21.3444 5.53548 21.2439 4.97634C21.1435 4.4172 20.868 3.9018 20.4551 3.50044C20.0422 3.09909 19.512 2.8313 18.9368 2.73364C18.3616 2.63596 17.7695 2.71315 17.241 2.95467C16.7126 3.19618 16.2737 3.59027 15.9842 4.08319C15.6946 4.57609 15.5685 5.14383 15.6232 5.70895L15.6093 5.6947C15.6504 6.16712 15.585 6.64259 15.4175 7.08788C15.2501 7.53318 14.9846 7.93758 14.6398 8.27287C14.2949 8.60805 13.8789 8.86612 13.4208 9.02888C12.9627 9.19163 12.4736 9.25523 11.9876 9.21526L12.0015 9.22951C11.5885 9.18908 11.1713 9.23836 10.7803 9.37381C10.3893 9.50919 10.034 9.72744 9.74039 10.0127C9.44674 10.2979 9.22199 10.6431 9.08234 11.0231C8.94276 11.4031 8.89176 11.8085 8.93304 12.2101L8.91915 12.1966C8.96005 12.6689 8.89439 13.1443 8.72688 13.5895C8.5593 14.0346 8.29389 14.4389 7.94908 14.7741C7.60425 15.1093 7.18835 15.3673 6.73039 15.5302C6.27242 15.693 5.78342 15.7569 5.29749 15.7171L5.31138 15.7306C4.73003 15.6775 4.14599 15.8001 3.63892 16.0815C3.13186 16.363 2.72644 16.7896 2.478 17.3033C2.22954 17.817 2.15013 18.3926 2.25061 18.9518C2.35109 19.5109 2.62657 20.0263 3.03945 20.4276C3.45234 20.829 3.98253 21.0968 4.55773 21.1944C5.13293 21.2921 5.72512 21.2149 6.25353 20.9734C6.78193 20.7319 7.22085 20.3379 7.51038 19.8449C7.79994 19.352 7.92601 18.7843 7.87139 18.2191L7.88605 18.2326C7.845 17.7602 7.91058 17.2849 8.07809 16.8396C8.24551 16.3944 8.511 15.99 8.85581 15.6548C9.20069 15.3196 9.61664 15.0615 10.0746 14.8988C10.5327 14.7359 11.0217 14.6722 11.5077 14.7121ZM17.1996 10.7633C16.9071 11.0493 16.6832 11.3944 16.5437 11.7741C16.4042 12.1538 16.3526 12.5587 16.3925 12.9601L16.3786 12.9466C16.4197 13.419 16.3541 13.8944 16.1866 14.3396C16.0191 14.7849 15.7537 15.1892 15.4089 15.5244C15.064 15.8596 14.648 16.1177 14.19 16.2804C13.732 16.4433 13.2429 16.507 12.757 16.4671L12.7708 16.4806C12.1896 16.4281 11.6057 16.551 11.0989 16.8328C10.5921 17.1145 10.1871 17.5414 9.93902 18.0551C9.69097 18.5689 9.61188 19.1444 9.71265 19.7035C9.81349 20.2625 10.0892 20.7777 10.5022 21.1788C10.9152 21.5799 11.4454 21.8474 12.0205 21.9448C12.5957 22.0423 13.1877 21.9649 13.716 21.7234C14.2443 21.4817 14.683 21.0877 14.9724 20.5947C15.2618 20.1018 15.3878 19.5342 15.3332 18.9692L15.3478 18.9827C15.3068 18.5103 15.3723 18.0349 15.5398 17.5896C15.7073 17.1444 15.9728 16.7401 16.3176 16.4048C16.6625 16.0696 17.0784 15.8115 17.5364 15.6488C17.9945 15.486 18.4835 15.4222 18.9695 15.4621L18.9548 15.4486C19.4296 15.4901 19.9076 15.4144 20.3444 15.2286C20.7811 15.0427 21.1625 14.7527 21.4533 14.3854C21.744 14.0181 21.9347 13.5854 22.0075 13.1274C22.0805 12.6694 22.0332 12.2009 21.8703 11.7653C21.7073 11.3298 21.4339 10.9413 21.0754 10.6358C20.7168 10.3303 20.2848 10.1178 19.8192 10.0179C19.3536 9.91795 18.8697 9.93385 18.4121 10.0641C17.9546 10.1945 17.5383 10.4349 17.2019 10.7633H17.1996Z"
								fill="currentColor"
							/>
						</svg>
						<span class="text-2xl font-bold tracking-tight text-black">Fleet</span>
					</div>
					<p class="text-sm text-gray-600 mb-4 max-w-md">
						Building the infrastructure for embodied AI. High-fidelity simulation environments that enable agents to master real-world tasks.
					</p>
					<p class="text-xs text-gray-500">
						© 2025 Fleet. All rights reserved.
					</p>
				</div>

				<!-- Product Column -->
				<div>
					<h4 class="font-bold text-sm mb-4 text-black">Product</h4>
					<ul class="space-y-3 text-sm text-gray-600">
						<li><a href="#platform" class="hover:text-black transition-colors">Platform</a></li>
						<li><a href="https://docs.fleetai.com" class="hover:text-black transition-colors">Documentation</a></li>
						<li><a href="https://status.fleetai.com" class="hover:text-black transition-colors">Status</a></li>
						<li><a href="#" class="hover:text-black transition-colors">Pricing</a></li>
					</ul>
				</div>

				<!-- Company Column -->
				<div>
					<h4 class="font-bold text-sm mb-4 text-black">Company</h4>
					<ul class="space-y-3 text-sm text-gray-600">
						<li><a href="#" class="hover:text-black transition-colors">About</a></li>
						<li><a href="https://github.com/fleetai" class="hover:text-black transition-colors">GitHub</a></li>
						<li><a href="https://twitter.com/fleetai" class="hover:text-black transition-colors">Twitter</a></li>
						<li><a href="https://linkedin.com/company/fleetai" class="hover:text-black transition-colors">LinkedIn</a></li>
					</ul>
				</div>
			</div>

			<!-- Bottom Bar -->
			<div class="pt-8 border-t border-gray-200 flex flex-col md:flex-row justify-between items-center gap-4 text-xs text-gray-500">
				<div class="flex flex-wrap gap-6">
					<a href="#" class="hover:text-black transition-colors">Privacy Policy</a>
					<a href="#" class="hover:text-black transition-colors">Terms of Service</a>
					<a href="#" class="hover:text-black transition-colors">Brand Guidelines</a>
				</div>
				<div>
					Backed by Sequoia, Menlo Ventures, and SV Angel
				</div>
			</div>
		</div>
	</footer>
</div>

