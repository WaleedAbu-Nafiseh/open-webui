<script lang="ts">

	import { getContext } from 'svelte';
	import { WEBUI_NAME } from '$lib/stores';

	const i18n = getContext('i18n');


</script>

<svelte:head>
	<title>
		{$i18n.t('Agents')} | {$WEBUI_NAME}
	</title>
</svelte:head>


<div class="mb-3">
	<div class="flex justify-between items-center">
		<div class=" text-lg font-semibold self-center">{$i18n.t('Agents')}</div>
	</div>
</div>
