<script>
  import SectionWorkflowArrow from "./section-workflow-arrow.svelte";

  const items = [
    {
      title: "요구 사항 분석.",
      description: "시작은 고객의 아이디어를 경청하는 일입니다. codersproduct가 도울 수 있는 방법을 모색합니다.",
    },
    {
      title: "검증 전략 구성.",
      description: "최우선 목표는 최소기능제품입니다. 단순한 장난감이 아니라, 가설을 실제적으로 논증할 수단입니다.",
    },
    {
      title: "핵심 기능 정의.",
      description: "가장 중요한 몇 가지의 기능만으로도 문제를 해결할 수 있어야 합니다. 우리는 지름길을 찾습니다.",
    },
    {
      title: "즉시 시작하는 개발.",
      description: "산만한 문서 작업은 최소화합니다. 디자인도 기다리지 않습니다. 곧바로 작동하는 제품을 만듭니다.",
    },
    {
      title: "일주일 단위의 배포.",
      description: "당신의 제품이 발전하는 모습을 자주 확인하세요. 완제품이란 불가능하기 때문입니다. 공개할 뿐입니다.",
    },
    {
      title: "테스트 및 피드백.",
      description: "제품은 고객과 사용자가 즉시 검토할 수 있습니다. 결과를 직접 확인하고 다음 단계를 준비하세요.",
    }
  ]
</script>

<section>
  <ol>
    <li>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height="40px" viewBox="0 0 24 24" width="40px"><g><rect fill="none" height="24" width="24"/></g><g><g/><g><path d="M12,3c-0.46,0-0.93,0.04-1.4,0.14C7.84,3.67,5.64,5.9,5.12,8.66c-0.48,2.61,0.48,5.01,2.22,6.56 C7.77,15.6,8,16.13,8,16.69V19c0,1.1,0.9,2,2,2h0.28c0.35,0.6,0.98,1,1.72,1s1.38-0.4,1.72-1H14c1.1,0,2-0.9,2-2v-2.31 c0-0.55,0.22-1.09,0.64-1.46C18.09,13.95,19,12.08,19,10C19,6.13,15.87,3,12,3z M14,17h-4v-1h4V17z M10,19v-1h4v1H10z M15.31,13.74c-0.09,0.08-0.16,0.18-0.24,0.26H8.92c-0.08-0.09-0.15-0.19-0.24-0.27c-1.32-1.18-1.91-2.94-1.59-4.7 c0.36-1.94,1.96-3.55,3.89-3.93C11.32,5.03,11.66,5,12,5c2.76,0,5,2.24,5,5C17,11.43,16.39,12.79,15.31,13.74z"/></g><g><rect height="3" width="1" x="11.5" y="11"/><rect height="3" transform="matrix(0.7071 -0.7071 0.7071 0.7071 -4.0312 10.8536)" width="1" x="10.59" y="8.79"/><rect height="3" transform="matrix(-0.7071 -0.7071 0.7071 -0.7071 14.7678 26.7028)" width="1" x="12.41" y="8.79"/></g></g></svg>  
      </i>
      <h2>
        { items[0].title }
      </h2>
      <p>
        { items[0].description }
      </p>
    </li>
    <i class="arrow">
      <SectionWorkflowArrow />
    </i>
    <li>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height="40px" viewBox="0 0 24 24" width="40px"><rect fill="none" height="24" width="24"/><g><path d="M19.88,18.47c0.44-0.7,0.7-1.51,0.7-2.39c0-2.49-2.01-4.5-4.5-4.5s-4.5,2.01-4.5,4.5s2.01,4.5,4.49,4.5 c0.88,0,1.7-0.26,2.39-0.7L21.58,23L23,21.58L19.88,18.47z M16.08,18.58c-1.38,0-2.5-1.12-2.5-2.5c0-1.38,1.12-2.5,2.5-2.5 s2.5,1.12,2.5,2.5C18.58,17.46,17.46,18.58,16.08,18.58z M15.72,10.08c-0.74,0.02-1.45,0.18-2.1,0.45l-0.55-0.83l-3.8,6.18 l-3.01-3.52l-3.63,5.81L1,17l5-8l3,3.5L13,6C13,6,15.72,10.08,15.72,10.08z M18.31,10.58c-0.64-0.28-1.33-0.45-2.05-0.49 c0,0,5.12-8.09,5.12-8.09L23,3.18L18.31,10.58z"/></g></svg>  
      </i>
      <h2>
        { items[1].title }
      </h2>
      <p>
        { items[1].description }
      </p>
    </li>
    <i class="arrow">
      <SectionWorkflowArrow />
    </i>
    <li>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height="40px" viewBox="0 0 24 24" width="40px"><rect fill="none" height="24" width="24"/><path d="M22,7h-9v2h9V7z M22,15h-9v2h9V15z M5.54,11L2,7.46l1.41-1.41l2.12,2.12l4.24-4.24l1.41,1.41L5.54,11z M5.54,19L2,15.46 l1.41-1.41l2.12,2.12l4.24-4.24l1.41,1.41L5.54,19z"/></svg>
      </i>
      <h2>
        { items[2].title }
      </h2>
      <p>
        { items[2].description }
      </p>
    </li>
  </ol>
  <div class="middle">
    <div class="spacer up">
      <i class="arrow up">
        <SectionWorkflowArrow />
      </i>
    </div>
    <div class="spacer" />
    <div class="spacer down">
      <i class="arrow down">
        <SectionWorkflowArrow />
      </i>
    </div>
  </div>
  <ol class="bottom">
    <li>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" height="40px" viewBox="0 0 24 24" width="40px"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M22.61 18.99l-9.08-9.08c.93-2.34.45-5.1-1.44-7C9.79.61 6.21.4 3.66 2.26L7.5 6.11 6.08 7.52 2.25 3.69C.39 6.23.6 9.82 2.9 12.11c1.86 1.86 4.57 2.35 6.89 1.48l9.11 9.11c.39.39 1.02.39 1.41 0l2.3-2.3c.4-.38.4-1.01 0-1.41zm-3 1.6l-9.46-9.46c-.61.45-1.29.72-2 .82-1.36.2-2.79-.21-3.83-1.25C3.37 9.76 2.93 8.5 3 7.26l3.09 3.09 4.24-4.24-3.09-3.09c1.24-.07 2.49.37 3.44 1.31 1.08 1.08 1.49 2.57 1.24 3.96-.12.71-.42 1.37-.88 1.96l9.45 9.45-.88.89z"/></svg>
      </i>
      <h2>
        { items[3].title }
      </h2>
      <p>
        { items[3].description }
      </p>
    </li>  
    <i class="arrow left">
      <SectionWorkflowArrow />
    </i>
    <li>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height="40px" viewBox="0 0 24 24" width="40px"><g><rect fill="none" height="24" width="24"/></g><g><g><path d="M6,15c-0.83,0-1.58,0.34-2.12,0.88C2.7,17.06,2,22,2,22s4.94-0.7,6.12-1.88C8.66,19.58,9,18.83,9,18C9,16.34,7.66,15,6,15 z M6.71,18.71c-0.28,0.28-2.17,0.76-2.17,0.76s0.47-1.88,0.76-2.17C5.47,17.11,5.72,17,6,17c0.55,0,1,0.45,1,1 C7,18.28,6.89,18.53,6.71,18.71z M17.42,13.65L17.42,13.65c6.36-6.36,4.24-11.31,4.24-11.31s-4.95-2.12-11.31,4.24l-2.49-0.5 C7.21,5.95,6.53,6.16,6.05,6.63L2,10.69l5,2.14L11.17,17l2.14,5l4.05-4.05c0.47-0.47,0.68-1.15,0.55-1.81L17.42,13.65z M7.41,10.83L5.5,10.01l1.97-1.97l1.44,0.29C8.34,9.16,7.83,10.03,7.41,10.83z M13.99,18.5l-0.82-1.91 c0.8-0.42,1.67-0.93,2.49-1.5l0.29,1.44L13.99,18.5z M16,12.24c-1.32,1.32-3.38,2.4-4.04,2.73l-2.93-2.93 c0.32-0.65,1.4-2.71,2.73-4.04c4.68-4.68,8.23-3.99,8.23-3.99S20.68,7.56,16,12.24z M15,11c1.1,0,2-0.9,2-2s-0.9-2-2-2s-2,0.9-2,2 S13.9,11,15,11z"/></g></g></svg>
      </i>
      <h2>
        { items[4].title }
      </h2>
      <p>
        { items[4].description }
      </p>
    </li>
    <i class="arrow left">
      <SectionWorkflowArrow />
    </i>
    <li>
      <i>
        <svg xmlns="http://www.w3.org/2000/svg" height="40px" viewBox="0 0 24 24" width="40px"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M20 2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm0 14H5.17l-.59.59-.58.58V4h16v12zm-9-4h2v2h-2zm0-6h2v4h-2z"/></svg>
      </i>
      <h2>
        { items[5].title }
      </h2>
      <p>
        { items[5].description }
      </p>
    </li>  
  </ol>
</section>

<style>
  section {
    display: flex;

    flex-direction: column;

    justify-content: center;

    padding-bottom: 144px;
  }

  ol {
    display: flex;

    align-items: center;

    list-style: none;
  }

  li {
    display: flex;

    flex-direction: column;

    align-items: center;

    width: 100%;

    padding: 0 16px;
  }

  li h2 {
    margin-top: 8px;

    font-size: 20px;
  }

  .arrow.down {
    transform: rotateZ(90deg);
  }

  .middle {
    display: flex;
  }

  .spacer {
    display: flex;

    justify-content: center;
  }

  p {
    margin-top: 8px;

    text-align: center;

    color: var(--color-body-500);

    line-height: 1.5;
  }

  @media (max-width: 480px) {
    ol {
      flex-direction: column;
    }

    .spacer.down {
      width: 100%;
    }

    .arrow.up {
      display: none;
    }

    .arrow {
      margin: 32px 0;

      transform: rotateZ(90deg);
    }
  }

  @media (min-width: 481px) {
    ol.bottom {
      flex-direction: row-reverse;
    }

    .spacer {
      width: 100%;
    }

    .spacer + .spacer {
      margin-left: 32px;
    }

    .arrow.up,
    .arrow.down {
      margin: 20px 0;
    }

    .arrow.up {
      transform: rotateZ(270deg);
    }

    .arrow.left {
      transform: rotateZ(180deg);
    }
  }
</style>