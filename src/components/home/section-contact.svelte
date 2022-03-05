<script>
  const onEmailButtonClicked = () => {
    window.open("mailto:developer@codersproduct.com")
  }

  const onSubmitted = () => {}
</script>

<section>
  <h1>
    귀하의 아이디어를 들려주세요.
  </h1>
  <p>
    codersproduct는 모든 견해와 발상을 존중합니다. 혹은
    <button on:click={onEmailButtonClicked}>developer@codersproduct.com</button>으로 직접 연락하세요.
  </p>
  <form on:submit|preventDefault={onSubmitted}>
    <input type="text" placeholder="이름을 입력해 주세요." />
    <input type="email" placeholder="답장을 수신할 이메일 주소를 입력해 주세요." />
    <textarea placeholder="내용을 입력해 주세요." />
    <input type="submit" value="제출하기" />
  </form>
</section>

<style>
  section {
    display: flex;

    flex-direction: column;

    justify-content: center;

    margin-top: 240px;

    margin-bottom: 64px;
  }

  p {
    margin-top: 4px;

    color: var(--color-body-500);

    line-height: 1.4;
  }

  form {
    display: flex;

    flex-direction: column;

    max-width: 576px;

    margin-top: 4px;
  }

  input,
  textarea {
    padding: 12px;

    margin-top: 12px;

    font-size: 1rem;
  }

  textarea {
    height: 164px;
  }

  button {
    font-size: 16px;

    color: var(--color-secondary);

    border: none;

    background: transparent;
  }

  input[type="submit"] {
    margin-top: 16px;

    width: fit-content;

    padding: 0;

    color: var(--color-secondary);

    background-color: transparent;
  }

  @media (max-width: 480px) {
    h1 {
      font-size: 28px;
    }

    p {
      font-size: 16px;
    }

    input[type="submit"] {
      align-self: center;
    }
  }

  @media (min-width: 481px) {
    h1 {
      font-size: 40px;
    }

    p {
      margin-top: 8px;

      font-size: 18px;
    }
  }
</style>