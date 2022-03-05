<script>
import AppNavigation from "./app_navigation.svelte";
import AppTitle from "./app_title.svelte";
</script>

<header>
  <div class="inner">
    <AppTitle />
    <AppNavigation />
  </div>
</header>

<style>
  header {
    display: flex;

    justify-content: center;

    width: 100%;

    border-bottom: 1px solid var(--color-border);
  }

  .inner {
    display: flex;

    justify-content: space-between;

    align-items: center;

    max-width: var(--width-inner);

    width: 100%;

    padding: 8px 16px;
  }
</style>