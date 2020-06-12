<script>
	import { onMount } from 'svelte';
	import Header from '../components/Header.svelte';
	import Main from '../components/Main.svelte';
	import TimeLine from '../components/TimeLine.svelte';
	import Sidebar from '../components/Sidebar.svelte';

	const API = 'https://us-central1-pugstagram-co.cloudfunctions.net/data';
	let data = {};

	onMount(async () => {
		const response = await fetch(API);
		data = await response.json();
	});
</script>

<Header />
<Main> 
	<TimeLine posts={data.posts} />
	<Sidebar {...data.user} />
</Main>