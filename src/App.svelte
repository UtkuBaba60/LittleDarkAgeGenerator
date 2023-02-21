
<script>
	import Youtube from "./Youtube.svelte";
	let youtubeLink =""
    let randomNumber = Math.floor(Math.random()*12)
  switch (randomNumber) {
	case 0:
		youtubeLink ="fLOVBbduHPo"
		break;

		case 1:
		youtubeLink ="dgK0L1dhBHE"
		break;

		case 2:
		youtubeLink ="MCLUtt2L29c"
		break;

		case 3:
		youtubeLink ="giYXFbrCLSQ"
		break;

		case 4:
		youtubeLink ="wWhBQS4Z8MM"
		break;

		case 5:
		youtubeLink ="74eLk0Ia9aU"
		break;
		case 6:
		youtubeLink ="vNkklwG5Pnk"
		break;

		case 7:
		youtubeLink ="pNcwCKyN5Z0"
		break;

		case 8:
		youtubeLink ="XX4795qEr_8"
		break;

		case 9:
		youtubeLink ="HGYJNSwMI14"
		break;

		case 10:
		youtubeLink = "8pDjMiewOPU"
		break;

		case 11:
		youtubeLink = "aWYpm2sT6g0"
		break;
		
	default:
		break;
  }
</script>

<main >
	<h1 >Little Dark Age Generator</h1>
</main>
<hr>
<Youtube videoId = {youtubeLink} />

<footer class ="footer">
	©️ Utku Özkanlı 2023
</footer>

<style>
	.footer{
		text-align: center;
		padding-top: 40px;
		font-family: 'Oswald', sans-serif;
	}
	
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: black;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: bold;
		text-shadow: 3px 0 grey;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
			
		}
	}
</style>


