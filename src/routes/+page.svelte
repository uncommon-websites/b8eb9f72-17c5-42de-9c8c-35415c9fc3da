<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconCalendar from "~icons/lucide/calendar";
	import IconTrophy from "~icons/lucide/trophy";
	import IconSparkles from "~icons/lucide/sparkles";
	import IconFolderKanban from "~icons/lucide/folder-kanban";
	import IconRefreshCw from "~icons/lucide/refresh-cw";
	import IconGift from "~icons/lucide/gift";
</script>

<Hero
	title="Turn family chaos into seamless coordination"
	subtitle="One gamified planning hub that replaces scattered calendars, endless group texts, and missed appointments."
	imageSrc="/generated/image-a-cheerful-family-scene-inside-a-cozy-su.webp"
	centered={false}
	callsToAction={[
		{
			href: "/",
			label: "Start free trial"
		},
		{
			href: "/about",
			label: "Learn more"
		}
	]}
/>
<LogoScroller 
	label="Trusted by families at"
	logoUrls={[
		'https://cdn.brandfetch.io/patagonia.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/salesforce.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/netflix.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/target.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Rooted consolidates your family's calendars, tasks, and projects into one intuitive planning hub designed specifically for dual-income households managing kids' schedules. We transform the daily juggle of disconnected apps and endless group texts into seamless coordination, so you can focus on what matters most—spending quality time together instead of chasing down logistics."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Mehta",
			position: "Marketing Director & Mom of 3",
			company: "Seattle, WA",
			quote:
				"Rooted saved us 8+ hours weekly by eliminating the endless back-and-forth texts about who's picking up whom. Our family finally has one source of truth for soccer practice, dentist appointments, and everything in between.",
			image: "/generated/image-professional-headshot-of-a-confident-asi.webp"
		},
		{
			name: "Carlos Rivera",
			position: "Software Engineer & Dad of 2",
			company: "Austin, TX",
			quote:
				"We haven't missed a single recital or pickup since switching to Rooted three months ago. The daily digest means my wife and I are always on the same page without constantly checking four different apps.",
			image: "/generated/image-professional-headshot-of-a-friendly-hisp.webp"
		},
		{
			name: "Amara Williams",
			position: "Nurse Manager & Mom of 2",
			company: "Atlanta, GA",
			quote:
				"The gamification turned chore wars into teamwork. My kids actually complete tasks now because they're earning points, and I reclaimed 5 hours per week I used to spend nagging and coordinating.",
			image: "/generated/image-professional-headshot-of-an-approachable.webp"
		}
	]}
/>

<Features
	title="Everything your family needs, all in one place"
	subtitle="Replace scattered apps and endless group texts with a single hub that makes coordination effortless"
	features={[
		{
			title: "Unified family calendar",
			description:
				"See everyone's schedules at a glance and eliminate missed appointments. Sync with Google Calendar, Outlook, and Apple Calendar so nothing falls through the cracks.",
			icon: IconCalendar
		},
		{
			title: "Gamified task management",
			description:
				"Turn chores into achievements with points, streaks, and rewards that motivate kids to actually help. Watch household responsibilities transform from nagging battles into friendly competition.",
			icon: IconTrophy
		},
		{
			title: "Smart daily digest",
			description:
				"Get one morning notification with everything your family needs to know today. No more checking four different apps or scrolling through endless group texts to stay coordinated.",
			icon: IconSparkles
		},
		{
			title: "Collaborative project hub",
			description:
				"Manage complex family projects like vacation planning, home renovations, and birthday parties with shared task lists and file attachments. Everyone stays aligned without the chaos.",
			icon: IconFolderKanban
		},
		{
			title: "Real-time family sync",
			description:
				"See instant updates when schedules change or tasks get completed. Replace notification overload with smart alerts that keep everyone informed without the constant buzzing.",
			icon: IconRefreshCw
		},
		{
			title: "Household rewards system",
			description:
				"Build family accountability with customizable points and rewards that drive engagement. Kids earn privileges while parents gain peace of mind knowing responsibilities are handled.",
			icon: IconGift
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop juggling apps"
	subtitle="Start enjoying family time"
	description="You're already managing enough. Replace your scattered Google Calendar, Todoist, and endless group texts with one simple hub. Start your free trial today and get your evenings back."
	imageSrc="/generated/image-a-happy-working-parent-sitting-comfortab.webp"
	callsToAction={[
		{
			href: "/",
			label: "Start free trial",
			variant: "primary"
		},
		{
			href: "/",
			label: "See how it works",
			variant: "secondary"
		}
	]}
/>
