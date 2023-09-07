<script lang="ts">
	import { twMerge } from 'tailwind-merge';

	type ButtonType = 'primary' | 'secondary' | 'tertiary';

	export let type: ButtonType = 'primary';

	const BASE_CLASS_NAME = 'rounded-xl text-center px-4 py-[0.29rem] text-lg';

	const buttonClassNames = {
		primary: `${BASE_CLASS_NAME} font-medium text-white bg-black`,
		secondary: `${BASE_CLASS_NAME} text-black bg-neutral-200 font-bold`,
		tertiary: `${BASE_CLASS_NAME} text-black bg-neutral-200 font-bold border border-neutral-600`
	};
</script>

<button type="button" class={twMerge(buttonClassNames[type], $$restProps.class ?? '')}>
	<slot />
</button>
