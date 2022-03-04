<section>
  <ol>
    <li>
      <h2>
        작은 팀.
      </h2>
      <p>
        우리는 민첩하게 움직입니다. 분명한 책임에 따라 빠르게 결정하며 커뮤니케이션 비용을 아낍니다.
      </p>
    </li>
    <li>
      <h2>
        코드지향적.
      </h2>
      <p>
        불필요한 문서 작업을 최소화합니다. 비결은 codersproduct의 투명한 개발 방법입니다.
      </p>
    </li>
    <li>
      <h2>
        안티-매너리즘.
      </h2>
      <p>
        훌륭한 제품은 적극적인 몰입에서 탄생합니다. 우리 개발자들은 "더 좋은 것"을 알고 있습니다.
      </p>
    </li>
  </ol>
</section>

<style>
  section {
    padding: 0 16px;
  }

  ol {
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
    margin-bottom: 8px;
  }

  p {
    text-align: center;

    line-height: 1.6;
  }

  @media (max-width: 480px) {
    ol {
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
    ol {
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