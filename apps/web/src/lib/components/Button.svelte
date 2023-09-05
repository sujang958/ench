<script lang="ts">
	import { twMerge } from 'tailwind-merge';
</script>

<button
	type="button"
	class={twMerge('rounded-xl text-center px-4 py-[0.29rem] text-lg font-medium text-white bg-black', $$restProps.class ?? '')}
>
	<slot />
</button>
