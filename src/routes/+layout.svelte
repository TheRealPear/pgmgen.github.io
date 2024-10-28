<script>
  import 'bootstrap/dist/css/bootstrap.css';
  import 'bootstrap-icons/font/bootstrap-icons.css';
  import scriptSrc from 'bootstrap/dist/js/bootstrap.bundle.js?url';
  import colorModes from '$lib/js/color-modes.js?url';
  import Header from '$lib/components/header.svelte'
  import Footer from '$lib/components/footer.svelte'
  /** @type {{children?: import('svelte').Snippet}} */
  let { children } = $props();
</script>
<svelte:head>
  <script src={scriptSrc}></script>
  <script src={colorModes}></script>
</svelte:head>
<Header />
{@render children?.()}
<Footer />