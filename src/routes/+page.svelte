<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	centered={false}
	title="Transform your expertise into an AI-powered digital mind"
	subtitle="Join coaches and consultants scaling personalized guidance to thousands while you sleep. Turn knowledge into 24/7 revenue streams."
	imageSrc="/generated/image-a-professional-business-coach-is-engagin.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Create your digital mind"
		},
		{
			href: "/demo",
			label: "Watch demo"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/masterclass.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/coursera.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/mindvalley.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/udemy.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Scaling wisdom, one digital mind at a time"
	text="Delphi transforms coaches and consultants into AI-powered digital minds that provide personalized guidance 24/7. Train your AI on your expertise, reach thousands of clients simultaneously, and generate passive income while preserving the authentic conversational style that makes your advice invaluable."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "Executive Business Coach",
			company: "Peak Performance Consulting",
			quote:
				"My Delphi clone handles 200+ client consultations monthly while I sleep. I've recovered 40 hours per week and increased revenue by 180% without sacrificing the personal touch my clients expect.",
			image: "/generated/image-professional-headshot-of-marcus-chen-a-c.webp"
		},
		{
			name: "Elena Rodriguez",
			position: "Leadership Development Expert",
			company: "Transform Leadership Institute",
			quote:
				"I was turning away $75K in coaching requests annually due to time constraints. Now my digital mind serves clients 24/7, generating $45K monthly in passive income while maintaining authentic conversations.",
			image: "/generated/image-professional-headshot-of-elena-rodriguez.webp"
		},
		{
			name: "David Thompson",
			position: "Career Transition Specialist",
			company: "NextLevel Career Solutions",
			quote:
				"Delphi eliminated the risk of losing my expertise when I took a sabbatical. My digital clone maintained client relationships and generated $28K in revenue during my 3-month break, proving business continuity is possible.",
			image: "/generated/image-professional-headshot-of-david-thompson-.webp"
		}
	]}
/>

<Features
	title="Scale your expertise beyond physical limits"
	subtitle="Transform your knowledge into an AI-powered digital mind that serves clients 24/7, speaks their language, and generates passive income while you focus on what matters most."
	features={[
		{
			title: "Authentic conversational AI",
			description: "Your digital mind speaks only your words, never improvising, preserving the authentic voice and wisdom that makes your guidance invaluable."
		},
		{
			title: "Multi-modal client engagement", 
			description: "Reach clients through chat, voice calls, video calls, SMS, WhatsApp, Slack, and Zoom—meeting them wherever they prefer to connect."
		},
		{
			title: "Passive revenue generation",
			description: "Turn your expertise into 24/7 income streams through memberships, paid conversations, and product upselling while you sleep."
		},
		{
			title: "Real-time knowledge updates",
			description: "Your digital mind continuously learns from your latest content, podcasts, videos, and live feeds to stay current with your evolving expertise."
		},
		{
			title: "Global accessibility",
			description: "Serve clients across 40+ languages and time zones, breaking down barriers that previously limited your reach to local markets."
		},
		{
			title: "Complete ownership and privacy",
			description: "Your digital mind belongs entirely to you—securely stored, fully encrypted, never shared or sold, with complete control over interactions."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop turning away $50K+ in coaching revenue"
	subtitle="Your digital mind starts working in 24 hours"
	description="Join 2,400+ coaches who've eliminated client waitlists and scaled their expertise 24/7. While competitors limit themselves to 1-on-1 sessions, your AI clone serves unlimited clients simultaneously—preserving your authentic voice and generating passive income while you sleep."
	imageSrc="/generated/image-a-successful-business-coach-dressed-in-p.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Create your digital mind now",
			variant: "primary"
		},
		{
			href: "/demo",
			label: "See authentic AI in action",
			variant: "secondary"
		}
	]}
/>
