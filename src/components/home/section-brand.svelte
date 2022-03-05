<section>
  <h1 class="title">Coder's Product</h1>
  <p class="description">귀하의 빛나는 아이디어를 검증하는 가장 빠른 방법입니다.</p>
</section>

<style>
  section {
    display: flex;

    flex-direction: column;

    justify-content: center;

    height: 480px;
  }

  .description {
    margin-top: 4px;

    line-height: 1.6;
  }

  @media (max-width: 480px) {
    .title {
      font-size: 40px;
    }

    .description {
      font-size: 19px;
    }
  }

  @media (min-width: 481px) {
    .title {
      font-size: 64px;
    }

    .description {
      font-size: 24px;
    }
  }
</style>