<template>
	<div>
		<div @click="toggle" class="cursor-pointer bg-[#4b7bf5] text-white font-bold py-2 px-4 rounded-t">
			{{ title }}
		</div>
		<div v-show="isOpen" class="border border-t-0 border-[#4b7bf5] py-2 px-4 rounded-b">
			<slot></slot>
		</div>
	</div>
</template>

<script>
export default {
	name: 'CollapsePanel',
	props: {
		title: {
			type: String,
			required: true,
		},
	},
	data() {
		return {
			isOpen: false,
		};
	},
	methods: {
		toggle() {
			this.isOpen = !this.isOpen;
		},
	},
};
</script>

<style scoped>
/* Optional: Add transition for a smoother effect */
div[style*="display: none;"] {
	display: block !important;
	max-height: 0;
	overflow: hidden;
	transition: max-height 0.3s ease-in-out;
}
div[style*="display: block;"] {
	max-height: 1000px; /* Adjust as necessary */
	transition: max-height 0.3s ease-in-out;
}
</style>