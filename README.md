## Git Command

<br>
<br>

### 📌 git init

---

작업 디렉토리에서 git을 사용할 수 있도록 초기화 (시작!)하는 명령어입니다.

<br>

### 📌 git remote add origin ...

---

작업 디렉토리는 로컬, 내 컴퓨터에만 있습니다.

우리의 코드를 다른 개발자와 공유하기 위해 `git`과 `github`를 사용하는데요.

github의 레포지토리 (디렉토리)에 연동하기 위해 다음 명령어를 입력해줍니다.

    git remote add origin https:github.com/user_name/repository_name.git

이제 우리가 로컬컴퓨터에서 작업한 내용을 github 레포지토리에도 공유할 수 있습니다.

<br>

### 📌 git add

---

로컬 컴퓨터에서 작업한 파일을 `git`에 올리는 단계입니다.

    git add file_name or . (all)

<br>

### 📌 git commit

작업하거나 수정한 파일을 커밋하는 단계입니다.

    git commit >> Be able to write header and bodies of commit message

    git commit -m "messages here"

커밋 메시지를 길고 자세하게 작성하려면 위의 명령어를,

짧은 메시지만을 담고 싶다면 아래 명령어를 사용하면 됩니다.

<br>

### 📌 git push origin branch_name

이제 git에 커밋한 파일은 github 레포지토리에 보내야합니다.

    git push origin branch_name

작업하고 있는 branch의 이름을 `branch_name`에 적어줍니다.

우리가 로컬 컴퓨터에서 작성한 코드를 다른 개발자들에게 공유할 수 있습니다.
