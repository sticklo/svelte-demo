<script lang="ts">
  import Header from "./components/Header.svelte";
  import AccessorizeBanny from "./components/AccessorizeBanny.svelte";
  import MidSectionOne from "./components/MidSectionOne.svelte";
  import MidSectionTwo from "./components/MidSectionTwo.svelte";
  import BannyProfile from "./components/BannyProfile.svelte"
</script>

<Header />
<AccessorizeBanny />
<MidSectionOne />
<MidSectionTwo />
<BannyProfile />
<main />

<style>
  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
