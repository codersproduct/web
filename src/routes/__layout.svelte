<script>
  import "../app.css"
  import AppHeader from "src/components/app_header.svelte";
  import AppMain from "src/components/app_main.svelte";
  import AppFooter from "src/components/app_footer.svelte";
</script>

<AppHeader />
<AppMain>
  <slot/>
</AppMain>
<AppFooter />