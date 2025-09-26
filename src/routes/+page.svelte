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
	imageSrc="/generated/image-lifestyle-editorial-photo-candid-moment-.webp"
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
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
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
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Get your working AI prototype in two weeks"
	subtitle="You're one call away from seeing real results"
	description="No long contracts. No AI hype. Just a better product, faster. CTOs at Series A–C companies trust us to deliver production-grade AI that actually works—without building an in-house ML team."
	imageSrc="/generated/image-editorial-corporate-portrait-of-a-confid.webp"
	callsToAction={[
		{
			href: "/",
			label: "Start your prototype",
			variant: "primary"
		},
		{
			href: "/",
			label: "Talk to our team",
			variant: "secondary"
		}
	]}
/>
