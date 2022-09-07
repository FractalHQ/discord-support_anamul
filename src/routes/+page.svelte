<script lang="ts">
	import { browser } from '$app/environment';
	import hMoment from './moment-hijri';
</script>

<h1>{hMoment().format('iYYYY/iM/iD')}</h1>

<h2>hello from {browser ? 'browser' : 'server'}</h2>
