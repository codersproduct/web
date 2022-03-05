<script>
  const onSubmitted = () => {}
</script>

<section>
  <h1>
    귀하의 아이디어를 들려주세요.
  </h1>
  <p>
    막연해도 좋습니다. 소중한 가능성을 성급하게 포기하지 마세요.
    <br />
    아무도 모릅니다. 머릿속이 아닌 눈앞의 현실에서 확인하기 전까지는.
    <br />
    codersproduct가 당신을 돕습니다.
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

    margin-top: 144px;

    margin-bottom: 128px;
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

    padding: 0;
  }

  button:hover {
    text-decoration: underline;
  }

  @media (max-width: 480px) {
    h1 {
      font-size: 28px;
    }

    p {
      font-size: 16px;
    }

    input[type="submit"] {
      width: 100%;
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