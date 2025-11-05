<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconBrain from "~icons/lucide/brain";
	import IconShield from "~icons/lucide/shield";
	import IconWorkflow from "~icons/lucide/workflow";
	import IconZap from "~icons/lucide/zap";
	import IconSparkles from "~icons/lucide/sparkles";
	import IconSmartphone from "~icons/lucide/smartphone";
</script>

<CenteredTextOnlyHero
	title="Your browser that thinks ahead"
	subtitle="Neuve learns your patterns and proactively completes tasks, transforming mobile browsing into personalized assistance with privacy-first, on-device AI."
	imageSrc="/generated/image-a-modern-startup-workspace-captured-in-d.webp"
/>
<LogoScroller
	label="Trusted by power users at"
	logoUrls={[
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/linear.app/w/400/h/400/logo',
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Built for power users"
	text="Neuve is an AI-powered mobile browser that learns from your browsing patterns and proactively completes tasks before you even ask. We serve iOS power users who demand personalized workflows and privacy-first technology. Unlike traditional browsers with static features, Neuve adapts to you, saving hours every week through intelligent automation that runs entirely on your device."
/>

<Testimonials
	testimonials={[
		{
			name: "Keiko Tanaka",
			position: "Senior iOS Engineer",
			company: "Notion",
			quote:
				"Neuve saves me 2 hours daily by automatically handling my recurring web tasks. I used to manually check 12 sites every morning, now my browser just shows me what matters.",
			image: "/generated/image-candid-documentary-style-photo-of-a-prof.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Product Lead",
			company: "Linear",
			quote:
				"The on-device processing means my browsing patterns never leave my phone. I switched from Chrome when I realized how much of my workflow data was being collected.",
			image: "/generated/image-documentary-style-image-of-a-middle-aged.webp"
		},
		{
			name: "Sofia Ramirez",
			position: "Founder",
			company: "Indie Developer",
			quote:
				"Neuve reduced my context switching by 60%. Instead of opening 8 tabs to research something, it proactively surfaces related content as I browse. Game changer for solo founders.",
			image: "/generated/image-candid-photo-of-a-young-hispanic-woman-e.webp"
		}
	]}
/>

<Features
	title="Built for how you actually browse"
	subtitle="Neuve isn't just smarter—it's designed to anticipate, adapt, and act on your behalf, transforming mobile browsing from reactive to proactive."
	features={[
		{
			title: "Proactive intelligence",
			description:
				"Neuve learns your browsing patterns and anticipates your needs before you search. Your browser completes tasks while you focus on what matters.",
			icon: IconBrain
		},
		{
			title: "On-device privacy",
			description:
				"All AI processing happens locally on your iPhone with zero-logging architecture. Your data stays yours, never shared or stored in the cloud.",
			icon: IconShield
		},
		{
			title: "Adaptive workflows",
			description:
				"Dynamic shortcuts evolve with your habits, replacing static bookmarks with intelligent suggestions that adapt to your context and time of day.",
			icon: IconWorkflow
		},
		{
			title: "Seamless task automation",
			description:
				"Automate repetitive mobile browsing tasks from form filling to multi-step searches. Neuve handles the busy work so you don't have to.",
			icon: IconZap
		},
		{
			title: "Context-aware assistance",
			description:
				"Your browser understands what you're trying to accomplish and surfaces relevant tools, content, and actions at exactly the right moment.",
			icon: IconSparkles
		},
		{
			title: "Built for iOS first",
			description:
				"Native iOS experience designed from the ground up for mobile, not a desktop browser retrofit. Fast, fluid, and feels like it belongs on your iPhone.",
			icon: IconSmartphone
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
