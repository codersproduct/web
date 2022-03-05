<script>
  const items = [
    {
      headline: "작은 팀.",
      description: "우리는 민첩하게 움직입니다. 분명한 책임에 따라 빠르게 결정하며 커뮤니케이션 비용을 아낍니다.",
      href_more: "/team",
    },
    {
      headline: "코드지향적.",
      description: "불필요한 문서 작업을 최소화합니다. 비결은 codersproduct의 투명한 개발 방법입니다.",
      href_more: "/dev",
    },
    {
      headline: "안티-매너리즘.",
      description: "훌륭한 제품은 적극적인 몰입에서 탄생합니다. 우리 개발자들은 \"더 좋은 것\"을 알고 있습니다.",
      href_more: "/values",
    }
  ]
</script>

<section>
  <ul>
    {#each items as { headline, description, href_more }}
      <li>
        <h2>
          { headline }
        </h2>
        <div class="text">
          <p>
            { description }
          </p>
          <a href={ href_more }>
            자세히 알아보기
          </a>
        </div>
      </li>
    {/each}
  </ul>
</section>

<style>
  ul {
    display: flex;
    
    width: 100%;

    list-style: none;
  }

  li {
    display: flex;

    flex-direction: column;

    justify-content: center;

    align-items: center;

    width: 100%;
  }

  li h2 {
    display: flex;

    flex-direction: column;

    justify-content: flex-end;

    height: 100%;

    margin-bottom: 8px;
  }

  li .text {
    display: flex;

    flex-direction: column;

    align-items: center;

    height: 100%;
  }

  li p {
    text-align: center;

    line-height: 1.6;
  }

  li a {
    margin-top: 16px;
  }

  @media (max-width: 480px) {
    ul {
      flex-direction: column;
    }

    li {
      height: 200px;
    }

    li h2 {
      font-size: 28px;
    }

    li + li {
      margin-top: 64px;
    }
  }
  
  @media(min-width: 481px) {
    ul {
      justify-content: space-evenly;
    }

    li {
      height: 480px;
    }

    li h2 {
      font-size: 32px;
    }

    li + li {
      margin-left: 16px;
    }
  }
</style>