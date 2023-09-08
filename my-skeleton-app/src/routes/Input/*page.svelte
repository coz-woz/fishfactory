


<div class="container mx-auto p-8 space-y-8">

	<h3 class="h3">Search Types</h3>

	<l class='h4'><b>Reconaissance:</b></l><br>
	<l>The Reconaissance module uses the Playwright browser automation to gather information about phishing pages including:</l>
		<ul style="padding-left:40px">
			<li>&#x2022 HTTP title</li>
			<li>&#x2022 screenshot of page content (SHA256 and phash)</li>
			<li>&#x2022 favicon murmurhash</li>
			<li>&#x2022 SSL thumbprint</li>
			<li>&#x2022 IP and domain</li>
		</ul>

	<l class='h4'><b>Downloader:</b></l>
	<br>
	<l>The Downloader module performs threaded directory enumeration requests to attempt to download and process ZIP phishing kits. Traverses archive files and extracts features including:</l>
		<ul style="padding-left:40px">
			<li>&#x2022 email addresses</li>
			<li>&#x2022 IP addresses</li>
			<li>&#x2022 references to text files, which Fisfactory will attempt to download and extract email and IP addresses from/li>
			<li>&#x2022 brute performs threaded directory enumeration using common credential store locations, which Fishfactory will download and process email and IP addresses from</li>
		</ul>
	<br>
	<section>
		<a class="btn variant-filled-primary" href="https://kit.svelte.dev/">SvelteKit</a>
		<a class="btn variant-filled-secondary" href="https://tailwindcss.com/">Tailwind</a>
		<a class="btn variant-filled-tertiary" href="https://github.com/">GitHub</a>
	</section>
</div>