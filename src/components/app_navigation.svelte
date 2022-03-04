<script>
  const items = [
    {
      label: "제품",
      href: "/product"
    },
    {
      label: "읽을 거리",
      href: "/article",
    },
    {
      label: "로그인",
      href: "/sign-in",
    },
  ]
</script>

<nav>
  <ul>
    {#each items as { label, href }}
      <li>
        <a href={ href }>
          { label }
        </a>
      </li>
    {/each}
  </ul>
</nav>

<style>
  nav ul {
    display: flex;

    list-style: none;
  }

  nav ul li + li {
    margin-left: 32px;
  }
</style>