<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="Mobile browsing, reimagined"
	subtitle="The first truly agentic browser that learns your patterns and proactively completes tasks. Transform your iPhone into a personalized web assistant."
	imageSrc="/generated/image-a-candid-documentary-style-photo-of-a-fo.webp"
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/figma.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/linear.app/w/400/h/400/logo'
	]}
/>

<Summary
	title="The future of mobile browsing"
	text="Neuve transforms your iPhone into an intelligent web companion that learns your patterns, anticipates your needs, and completes tasks proactively—all while keeping your data completely private with on-device processing."
/>

<Testimonials
	testimonials={[
		{
			name: "Alex Chen",
			position: "iOS Developer",
			company: "Tech Enthusiast",
			quote:
				"Neuve completely changed how I browse on my iPhone. It learns my workflow patterns and actually completes tasks before I even think to do them. The privacy-first approach with on-device processing is exactly what power users have been waiting for.",
			image: "/generated/image-professional-head-and-shoulders-portrait.webp"
		},
		{
			name: "Jordan Martinez",
			position: "Product Designer",
			company: "Early Adopter",
			quote:
				"Finally, a mobile browser that doesn't treat me like every other user. Neuve's agentic AI understands my research patterns and proactively surfaces relevant information. It's like having a personal assistant built into my browser.",
			image: "/generated/image-professional-headshot-of-a-confident-bla.webp"
		},
		{
			name: "Taylor Kim",
			position: "Privacy Advocate",
			company: "Tech Community",
			quote:
				"I was skeptical about AI in browsers until I tried Neuve. The zero-logging architecture and on-device processing mean I get personalized assistance without sacrificing privacy. This is the future of mobile browsing.",
			image: "/generated/image-professional-headshot-of-a-confident-lat.webp"
		}
	]}
/>

<Features
	title="Agentic browsing capabilities"
	subtitle="AI that learns, adapts, and acts on your behalf"
	features={[
		{
			title: "Pattern Learning",
			description:
				"Neuve observes your browsing habits and learns your unique workflow patterns to provide increasingly personalized assistance over time."
		},
		{
			title: "Proactive Task Completion",
			description:
				"Your browser anticipates your needs and completes routine tasks automatically, from form filling to research compilation, saving hours every week."
		},
		{
			title: "Privacy-First AI",
			description:
				"All AI processing happens on-device with zero-logging architecture. Your browsing patterns and personal data never leave your iPhone."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Join the future of mobile browsing"
	subtitle="Be among the first to experience agentic AI browsing"
	description="Neuve is launching soon for iOS power users. Join our exclusive waitlist to get early access to the first truly intelligent mobile browser that learns your patterns and works proactively on your behalf."
	imageSrc="/generated/image-a-candid-image-of-a-diverse-small-group-.webp"
	callsToAction={[
		{
			href: "/",
			label: "Join the waitlist",
			variant: "primary"
		},
		{
			href: "/",
			label: "Learn more",
			variant: "secondary"
		}
	]}
/>
