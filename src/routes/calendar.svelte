<script lang="ts">
	let height: number;
	let width: number;
</script>

<div bind:clientHeight={height} bind:clientWidth={width}>
	<iframe
		src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America%2FChicago&showTitle=0&showPrint=0&showCalendars=0&mode=WEEK&src=ZW1vY3ViZUBnbWFpbC5jb20&src=YXRka211am40bDI2bzRwMXVsZXV2ZXE1ZDRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&src=Yjc2Y2ViOGM0MTQzZTQyOGZmZjRlMDM4MTg3MGZiOTk0ODRkODk0YmUxNGM0ZWM0N2JmYmUwYmQzNzljY2NmYUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=ZjEwZTMwMzhhN2FlY2U3Nzk1ZjRiNzcyNTAyZjUxMjc5OGVlNDliY2EwZTZkYWVkNmU0ZjZkZDQxMTJhZjZkNUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=cnFhZWNnZDZyOHU0bzVxaWQ2MTVqZzRkcDhAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&src=azE1ZWdkZ241cXA3MnQ5cDdqbXVjNGE3dmNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&src=ODM2YTQwOGIyZTE3ZTM2MzkzYmY1YWMxYjcyNzA3ZGE4OGE1NzYyNTljNDM4YmU5ZDU2MWRjMGIyOGIwN2I1M0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=amFzb24uaG9sdHplbkBnbWFpbC5jb20&src=cDFhanNycWdpaXFsY2xycGw4YW9rYWw2OXFlMmpvcXZAaW1wb3J0LmNhbGVuZGFyLmdvb2dsZS5jb20&src=YWRkcmVzc2Jvb2sjY29udGFjdHNAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&color=%233d00ae&color=%23795548&color=%2300b3b0&color=%23F4511E&color=%23D81B60&color=%23AD1457&color=%23F6BF26&color=%23F09300&color=%237CB342&color=%237986CB"
		{width}
		{height}
		frameborder="0"
		scrolling="no"
		title="family calendar"
	/>
</div>

<style>
	div {
		width: 100%;
		height: 100%;
		overflow: hidden;
		border-radius: 0.25em;
	}
</style>
