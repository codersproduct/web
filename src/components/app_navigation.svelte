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

  @media (max-width: 480px) {
    li {
      font-size: 14px;
      
    }
    li + li {
      margin-left: 16px;
    }
  }

  @media (min-width: 481px) {
    li + li {
      margin-left: 32px;
    }
  }
</style>