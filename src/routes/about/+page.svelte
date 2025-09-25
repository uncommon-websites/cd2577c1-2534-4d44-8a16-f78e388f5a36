<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "AI-native first",
			description: "Building intelligent systems from the ground up, not retrofitting existing solutions with AI as an afterthought."
		},
		{
			title: "Personalization at scale", 
			description: "Creating software experiences that adapt to individual users while maintaining the performance and reliability enterprises demand."
		},
		{
			title: "Rapid prototyping",
			description: "Shipping working prototypes within two weeks to validate concepts and accelerate your AI integration timeline."
		}
	];
</script>

<SecondaryHero
	title="Personal software, built for you"
	subtitle="AI experiences that adapt, not overwhelm"
	imageSrc="/generated/image-diverse-team-of-five-adults-collaboratin.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and investor sections removed - no verified information available -->

<!-- CTA Section -->
<CallToAction
	title="Ready to build AI-native?"
	subtitle="From concept to prototype in two weeks"
	description="Join the Series A-C startups already leveraging our AI expertise to integrate intelligent capabilities into their core products without hiring specialized ML teams."
	imageSrc="/generated/image-professional-cto-confident-and-approacha.webp"
/>
