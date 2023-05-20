<script>
	import {
		Motivators,
		Subscription,
		Logos,
		Prices,
		Video,
    CardsMatch,
		Description,
		Footer
	} from '../lib/widgets/';

  import { motivatorsList, fearsList } from '../lib/shared';
</script>

<main>
	<Subscription />
	<Logos />

	<!-- motivators -->
	<Description />
	<Motivators />
	<Video />
  <CardsMatch cardList={motivatorsList}/>

	<!-- fears -->
	<Description />
	<Motivators />
	<Video />
  <CardsMatch cardList={fearsList}/>


	<Prices />
</main>

<Footer />
