<script>
  import "../app.css"
  import AppHeader from "src/components/app/app_header.svelte";
  import AppMain from "src/components/app/app_main.svelte";
  import AppFooter from "src/components/app/app_footer.svelte";
</script>

<AppHeader />
<AppMain>
  <slot/>
</AppMain>
<AppFooter />