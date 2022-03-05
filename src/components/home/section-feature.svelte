<script>
import Index from "src/routes/index.svelte";

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
    <li>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height="72px" viewBox="0 0 24 24" width="72px"><rect fill="none" height="24" width="24"/><g><path d="M4,13c1.1,0,2-0.9,2-2c0-1.1-0.9-2-2-2s-2,0.9-2,2C2,12.1,2.9,13,4,13z M5.13,14.1C4.76,14.04,4.39,14,4,14 c-0.99,0-1.93,0.21-2.78,0.58C0.48,14.9,0,15.62,0,16.43V18l4.5,0v-1.61C4.5,15.56,4.73,14.78,5.13,14.1z M20,13c1.1,0,2-0.9,2-2 c0-1.1-0.9-2-2-2s-2,0.9-2,2C18,12.1,18.9,13,20,13z M24,16.43c0-0.81-0.48-1.53-1.22-1.85C21.93,14.21,20.99,14,20,14 c-0.39,0-0.76,0.04-1.13,0.1c0.4,0.68,0.63,1.46,0.63,2.29V18l4.5,0V16.43z M16.24,13.65c-1.17-0.52-2.61-0.9-4.24-0.9 c-1.63,0-3.07,0.39-4.24,0.9C6.68,14.13,6,15.21,6,16.39V18h12v-1.61C18,15.21,17.32,14.13,16.24,13.65z M8.07,16 c0.09-0.23,0.13-0.39,0.91-0.69c0.97-0.38,1.99-0.56,3.02-0.56s2.05,0.18,3.02,0.56c0.77,0.3,0.81,0.46,0.91,0.69H8.07z M12,8 c0.55,0,1,0.45,1,1s-0.45,1-1,1s-1-0.45-1-1S11.45,8,12,8 M12,6c-1.66,0-3,1.34-3,3c0,1.66,1.34,3,3,3s3-1.34,3-3 C15,7.34,13.66,6,12,6L12,6z"/></g></svg>
      </i>
      <h2>
        { items[0].headline }
      </h2>
      <div class="text">
        <p>
          { items[0].description }
        </p>
        <a href={ items[0].href_more }>
          자세히 알아보기
        </a>
      </div>
    </li>
    <li>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" height="72px" viewBox="0 0 24 24" width="72px"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M9.4 16.6L4.8 12l4.6-4.6L8 6l-6 6 6 6 1.4-1.4zm5.2 0l4.6-4.6-4.6-4.6L16 6l6 6-6 6-1.4-1.4z"/></svg>
      </i>
      <h2>
        { items[1].headline }
      </h2>
      <div class="text">
        <p>
          { items[1].description }
        </p>
        <a href={ items[1].href_more }>
          자세히 알아보기
        </a>
      </div>
    </li>
    <li>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height="72px" viewBox="0 0 24 24" width="72px"><g><rect fill="none" height="24" width="24"/></g><g><g><path d="M23,11.99l-2.44-2.79l0.34-3.69l-3.61-0.82L15.4,1.5L12,2.96L8.6,1.5L6.71,4.69L3.1,5.5L3.44,9.2L1,11.99l2.44,2.79 l-0.34,3.7l3.61,0.82L8.6,22.5l3.4-1.47l3.4,1.46l1.89-3.19l3.61-0.82l-0.34-3.69L23,11.99z M19.05,13.47l-0.56,0.65l0.08,0.85 l0.18,1.95l-1.9,0.43l-0.84,0.19l-0.44,0.74l-0.99,1.68l-1.78-0.77L12,18.85l-0.79,0.34l-1.78,0.77l-0.99-1.67l-0.44-0.74 l-0.84-0.19l-1.9-0.43l0.18-1.96l0.08-0.85l-0.56-0.65l-1.29-1.47l1.29-1.48l0.56-0.65L5.43,9.01L5.25,7.07l1.9-0.43l0.84-0.19 l0.44-0.74l0.99-1.68l1.78,0.77L12,5.14l0.79-0.34l1.78-0.77l0.99,1.68l0.44,0.74l0.84,0.19l1.9,0.43l-0.18,1.95l-0.08,0.85 l0.56,0.65l1.29,1.47L19.05,13.47z"/><polygon points="10.09,13.75 7.77,11.42 6.29,12.91 10.09,16.72 17.43,9.36 15.95,7.87"/></g></g></svg>
      </i>
      <h2>
        { items[2].headline }
      </h2>
      <div class="text">
        <p>
          { items[2].description }
        </p>
        <a href={ items[2].href_more }>
          자세히 알아보기
        </a>
      </div>
    </li>
  </ul>
</section>

<style>
  section {
    padding: 144px 0;
  }

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

    height: 200px;
  }

  li i {
    display: flex;

    flex-direction: column;

    justify-content: flex-end;

    height: 100%;
  }

  li h2 {
    display: flex;

    flex-direction: column;

    justify-content: flex-end;

    margin: 8px;
  }

  li .text {
    display: flex;

    flex-direction: column;

    align-items: center;

    height: 100%;
  }

  li p {
    text-align: center;

    color: var(--color-body-500);
    
    line-height: 1.6;
  }

  li a {
    margin-top: 16px;
  }

  @media (max-width: 480px) {
    ul {
      flex-direction: column;
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

    li h2 {
      font-size: 32px;
    }

    li + li {
      margin-left: 16px;
    }
  }
</style>