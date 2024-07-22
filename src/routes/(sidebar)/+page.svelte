<script lang="ts">
	import type { PageData } from './$types';
	import Dashboard from '../utils/dashboard/Dashboard.svelte';
	import MetaTag from '../utils/MetaTag.svelte';
	export let data: PageData;

	const path: string = '';
	const description: string = 'Admin Dashboard for Doctor-GGD Bookings';
	const title: string = 'WeAllShare NL';
	const subtitle: string = 'AI Automation Dashboard';
</script>

<MetaTag {path} {description} {title} {subtitle} />
<main class="p-4">
	<Dashboard {data} />
</main>
