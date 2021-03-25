<script>
	import { page } from '$app/stores';

	let name = $page.query.get('name');
</script>

<main>
	{name}
</main>
