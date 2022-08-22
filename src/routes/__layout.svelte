<script>
  import "../app.css";
  import Fa from 'svelte-fa/src/fa.svelte'
  import { faTwitch, faYoutube,faFacebook,faInstagram } from '@fortawesome/free-brands-svg-icons/index.es'
</script>

<header class="p-2 sticky top-0 z-50 flex items-center bg-fond flex-row justify-between">
  <article>
    <a href="./">
     <h1 class=" text-xl md:text-2xl">LA BOUTIQUE DU RPG </h1></a>
  </article>
  <nav class="flex gap-x-2   md:gap-x-5 items-center">
    <a href="https://www.twitch.tv/la_boutique_du_rpg" target="_blank" rel="noreferrer" >
    <Fa icon={faTwitch} size="1x" />
  </a>
  <a href="https://www.youtube.com/channel/UCyKYurmFpp79ZPGsyfIleVg" target="_blank" rel="noreferrer" >
    <Fa icon={faYoutube} size="1x" />
    </a>
    <a href="https://www.facebook.com/Laboutiquedurpg/" target="_blank" rel="noreferrer">

			 <Fa icon={faFacebook} size="1x" />
       </a>
       <a href="https://www.instagram.com/boutiquedurpg/" target="_blank" rel="noreferrer">

			 <Fa icon={faInstagram} size="1x" />
       </a>
       <a href="./newsletter">
       <button class="ff7 text-2xl ml-2 py-1 px-1	">INSCRIPTION</button>
      </a>
  </nav>
</header>
  <main class="relative">
  <slot></slot>
</main>
<footer class="text-center">@laboutique du rpg</footer>
