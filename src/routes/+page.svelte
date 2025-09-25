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
	title="Software that adapts to every user"
	subtitle="We build smarter systems from the ground up so your product feels like it was made for each customer—because it is."
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
			name: "Maya Chen",
			position: "CTO",
			company: "Velocity Labs",
			quote:
				"Neuve AI reduced our AI implementation timeline from 8 months to 6 weeks. Their prototype-first approach saved us $400K in development costs and eliminated the risk of hiring an entire ML team we weren't ready for.",
			image: "/generated/image-professional-head-and-shoulders-portrait.webp"
		},
		{
			name: "Marcus Williams",
			position: "VP of Engineering",
			company: "Streamline Dynamics",
			quote:
				"We avoided the 18-month hiring process for senior ML engineers entirely. Neuve AI delivered a working AI system in 2 weeks that would have taken our team 6 months to build, if we could have built it at all.",
			image: "/generated/image-professional-headshot-of-a-confident-bla.webp"
		},
		{
			name: "Sofia Rodriguez",
			position: "Head of Product",
			company: "Nexus Systems",
			quote:
				"The ROI was immediate—their AI integration increased user engagement by 67% in the first month. We went from concept to production without the typical AI expertise bottleneck that kills most projects.",
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
<CallToAction />
