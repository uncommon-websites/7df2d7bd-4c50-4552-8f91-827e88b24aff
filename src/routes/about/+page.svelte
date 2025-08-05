<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Preserve wisdom",
			description: "Born from a grandson's desire to access his grandfather's knowledge, we believe every expert's wisdom deserves digital immortality, ensuring guidance transcends time and physical limitations."
		},
		{
			title: "Democratize expertise",
			description: "From coaches turning away $50K+ in clients to millions seeking mentorship, we're breaking down barriers between exceptional expertise and those who need it most."
		},
		{
			title: "Authentic voices",
			description: "Our digital minds speak only the creator's authentic words across 40+ languages, preserving personality and expertise without artificial improvisation or generic responses."
		}
	];
</script>

<SecondaryHero
	title="Preserving wisdom for generations"
	subtitle="Born from a grandson's longing to connect with his grandfather's knowledge, Delphi transforms how we access and share human expertise across time and distance."
	imageSrc="/generated/image-two-entrepreneurs-engaged-in-a-lively-di.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"It started with a profound loss and the crushing reality of isolation. When co-founder Dara Ladjevardian's grandfather suffered a stroke, decades of wisdom from a successful pre-revolution Iranian businessman became unreachable. As a solo founder navigating uncertainty, Dara discovered the painful truth that millions face: the people we need guidance from most are often the least accessible. This personal crisis revealed a universal problem – exceptional expertise trapped in individual minds, leaving those who need it most to struggle alone.",
		"What began as a desperate attempt to reconnect with lost wisdom evolved into something revolutionary. Using AI to create a digital version of his grandfather for personalized advice, Dara experienced the first glimpse of what would become Delphi. Together with co-founder Sam Spelsberg, they embarked on a mission to democratize access to the world's greatest minds. From processing 100,000 words to unlimited content, from simple chat to multi-modal interactions across 40+ languages, they built a platform that transforms how expertise flows from those who have it to those who need it most.",
		"Today, Delphi serves as a modern Oracle – not dispensing one-size-fits-all prophecies, but providing personalized guidance from experts like Ben Greenfield, Keith Rabois, and thousands of other thought leaders. We're creating digital minds that preserve human wisdom at scale, turning the $366 billion professional services market into a more accessible, personal experience. Every coach, consultant, and expert who builds their digital mind with us doesn't just scale their business – they extend their legacy, ensuring their knowledge continues to guide and inspire long after they're gone."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our founders."
	subtitle="The minds behind democratizing wisdom."
	stakeholders={[
		{
			name: "Dara Ladjevardian",
			position: "Co-Founder & CEO",
			bio: "First-generation American with Iranian immigrant parents who experienced crushing loneliness as a solo founder. After his grandfather's stroke left decades of business wisdom unreachable, Dara created the first digital mind to preserve and access that knowledge—sparking the vision for Delphi.",
			image: "/generated/image-a-middle-eastern-american-business-execu.webp"
		},
		{
			name: "Sam Spelsberg",
			position: "Co-Founder",
			bio: "Visionary co-founder dedicated to democratizing access to personalized mentorship and wisdom at scale. Partners with Dara to solve the fundamental challenge of making expert guidance accessible to everyone who needs it.",
			image: "/generated/image-a-young-tech-entrepreneur-with-a-warm-sm.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Turn expertise into legacy"
	subtitle="Create your digital mind today"
	description="Join visionaries like Ben Greenfield, Matthew Hussey, and Keith Rabois who've discovered the secret to scaling wisdom—preserving their expertise in digital minds that provide personalized guidance 24/7, in 40+ languages, ensuring their knowledge never stops helping others."
/>
