


<script>

	let total_URL_count = 1252;
	let phishing_kits = 17;
	let total_AuNZ_domains = 84;
	let top_ten_domains = "Microsoft.com"
	let top_ten_favicons = "Icons Here"

</script>


<div class="container mx-auto p-8 space-y-8">
	
	<h1 class="h3">Welcome to Fish Factory</h1>
	<p>Fishfactory is a utility for extracting intelligence from phishing URLs. Fishfactory is intended to automate all of the 'low hanging fruit' intelligence pivots for credential phishing infrastructure (T1566.002 + T1078) to give users insight into the mechanics and scope of phishing attacks impacting them.</p>

</div>

<div class="container mx-auto p-8 space-y-8">

	<div class="grid grid-cols-3 gap-6 my-3">
		<div class="card p-4 text-center"><p class="text-6xl">{total_URL_count}<p><br>Stored Phishing URLs</div>
		<div class="card p-4 text-center"><p class="text-6xl">{phishing_kits} <p> <br>Identified Phishing Kits</div>
		<div class="card p-4 text-center"><p class="text-6xl">{total_AuNZ_domains} <p> <br>Identified AU/NZ Domains</div>
	</div>
	<div class="grid grid-cols-2 gap-6 my-3">
		<div class="card p-4 text-center"><p>Top 10 Domains</p><br><p class="text-2xl">{top_ten_domains}<p></div>
		<div class="card p-4 text-center"><p>Top 10 Favicons</p><br><p class="text-2xl">{top_ten_favicons}<p></div>

	</div>
</div>

