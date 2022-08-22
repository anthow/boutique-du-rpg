<script>
	import Layout from './__layout.svelte';
	import Fa from 'svelte-fa/src/fa.svelte';
	import {
		faTwitch,
		faYoutube,
		faFacebook,
		faInstagram
	} from '@fortawesome/free-brands-svg-icons/index.es';
	import {
		faShop,
		faBroom,
		faCartShopping,
		faTruckFast
	} from '@fortawesome/free-solid-svg-icons/index.es';
</script>

<article class="header p-20   headbody header opacity-70 m-auto text-center mb-10 ">
	<section>
		<h1 class="text-5xl text-center mb-10 ">LA BOUTIQUE DU RPG</h1>
		<p class="text-3xl">Votre spécialiste en jrpg rétro</p>
	</section>
</article>

<article class=" w-10/12 m-auto flex flex-col gap-y-20 mb-10   bg-fond m-auto">
	<section class=" flex flex-col gap-y-10 md:grid grid-cols-4 gap-x-20">
		<div class=" ff7 flex flex-col gap-y-10 m-auto text-lg col-span-3">
			<p class="text-center">
				La boutique du Rpg est une boutique qui vous proposera périodiquement une série d'articles
				liés au j-rpg chinés et sélectionnés avec précaution qui sera ensuite reconditionnée, par la
				réparation des disques, remplacement des boîtes cassées, réimpressions des fascicules et
				jaquettes manquantes ou abimées dans la mesure du possible
			</p>
			<p class="text-center ">
				envie d'en savoir plus ? Abonnez-vous à notre newsletter pour être informé du lancement ou
				rejoignez-nous sur les réseaux sociaux
			</p>
			<p class="text-center ">à très vite</p>
		</div>
		<div class=" flex flex-col gap-y-10 items-center ">
			<div class="place-items-center mt-10 ">
				<a href="./newsletter">
					<button class="ff7 text-5xl py-5 p-10">INSCRIPTION</button>
				</a>
			</div>
			<div class="flex gap-x-5 items-center">
				<a href="https://www.twitch.tv/la_boutique_du_rpg" target="_blank" rel="noreferrer">
					<Fa icon={faTwitch} size="2x" />
				</a>
				<a
					href="https://www.youtube.com/channel/UCyKYurmFpp79ZPGsyfIleVg"
					target="_blank"
					rel="noreferrer"
				>
					<Fa icon={faYoutube} size="2x" />
				</a>
				<a href="https://www.facebook.com/Laboutiquedurpg/" target="_blank" rel="noreferrer">
					<Fa icon={faFacebook} size="2x" />
				</a>
				<a href="https://www.instagram.com/boutiquedurpg/" target="_blank" rel="noreferrer">
					<Fa icon={faInstagram} size="2x" />
				</a>
			</div>
		</div>
	</section>
	<section class="flex flex-col  md:grid gap-y-10 grid-cols-4">
		<div class="flex flex-col space-y-5 items-center justify-between ">
			<div class="ff7">
				<Fa icon={faShop} size="2x" />
			</div>
			<p class="text-xl">Chinage</p>
		</div>
		<div class="flex flex-col space-y-5 items-center justify-between">
			<div class="ff7">
				<Fa icon={faBroom} size="2x" />
			</div>
			<p class="text-xl text-center">Reconditionnement</p>
		</div>
		<div class="flex flex-col space-y-5 items-center justify-between">
			<div class="ff7">
				<Fa icon={faCartShopping} size="2x" />
			</div>
			<p class="text-xl">Mise en vente</p>
		</div>
		<div class="flex flex-col space-y-5 items-center justify-between">
			<figure class="">
				<div class="ff7">
					<Fa icon={faTruckFast} size="2x" />
				</div>
			</figure>

			<p class="text-xl">Envoi</p>
		</div>
	</section>
</article>
