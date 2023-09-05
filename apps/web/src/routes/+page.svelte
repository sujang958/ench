<script lang="ts">
	import Button from '$lib/components/Button.svelte';
</script>

<section class="h-screen flex flex-col items-center justify-center text-center gap-y-12">
	<p class="text-8xl font-bold leading-tight">I can make you <br /> read mails</p>
	<p class="text-2xl text-neutral-600 break-words max-w-3xl w-full font-medium">
		If you have trouble reading your mail frequently, this app is right for you. Ench provides you a
		chat app-like experience in mail.
	</p>
	<div class="py-1" />
	<div class="flex flex-row items-center gap-x-4">
		<Button class="text-black bg-neutral-200 font-bold">About</Button>
		<Button>Sign Up</Button>
	</div>
</section>
