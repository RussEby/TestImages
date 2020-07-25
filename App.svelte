<script>
  import Button from "./Button.svelte";
  import imageLogo from "./images/ZTR.png";
  import StarTrekImage from "./images/StarTrek.jpeg";
  import NetNinjaLogo from "./images/netNinjaLogo.svg";
  import NetNinjaCompoment from "./NetNinjaLogo";

  let image = "https://placeimg.com/640/480/any";
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
  }
  img {
    width: 150px;
  }
  #NetNinjaLogo {
    width: 150px;
    height: 150px;
    border: 1px solid black;
    background-image: url("./images/netNinjaLogo.svg");
    background-size: contain;
  }
</style>

<main>
	<h1>Hello CodeSandbox</h1>
	<h2>Start editing to see some magic happen!</h2>
  <img src="{image}" alt="misc image">
  <img src="{imageLogo}" alt="LOGO">
  <img src="{StarTrekImage}" alt="Star Trek" >
  <NetNinjaCompoment />

  <div id="NetNinjaLogo"></div>

	<Button />
</main>