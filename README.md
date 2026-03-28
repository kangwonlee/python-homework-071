# Student ID Lookup System<br>학생 ID 조회 시스템

* Please work on the `exercise.py` file.<br>`exercise.py` 파일을 수정하세요.

## Overview
Create a Python program to manage a student ID database using a dictionary. It collects IDs and names, displays all pairs, and looks up an ID.
<br>학생 ID 데이터베이스를 사전을 사용하여 관리하는 Python 프로그램을 작성하세요. ID와 이름을 수집하고, 모든 키-밸류 쌍을 표시하며, 입력된 ID를 조회합니다.

## Requirements
1. **Part 1: Get Number of Students**
   - Prompt `Enter number of students: ` to get an integer `n`.
   <br>`Enter number of students: `를 출력하여 정수 `n`을 입력받으세요.
   - Print `==========` (10 equals signs).
   <br>`==========` (등호 10개)를 출력하세요.
   - Create an empty dictionary.
   <br>빈 사전을 생성하세요.

2. **Part 2: Collect IDs and Names**
   - Use a `for` loop to:
   <br>`for` 루프를 사용하여:
     - Prompt `Enter student ID: ` for a string ID.
     <br>`Enter student ID: `를 출력하여 문자열 ID를 입력받으세요.
     - Prompt `Enter student name: ` for a string name.
     <br>`Enter student name: `를 출력하여 문자열 이름을 입력받으세요.
     - Store ID as key, name as value in the dictionary.
     <br>ID를 키로, 이름을 값으로 사전에 저장하세요.
   - Print `==========` after the loop.
   <br>루프 후 `==========`를 출력하세요.

3. **Part 3: Display and Lookup**
   - Print each dictionary entry in `student-id : student-name` format (one per line).
   <br>각 사전 항목을 `학생id : 학생이름` 형식으로 출력하세요 (한 줄에 하나씩).
   - Print `==========`.
   <br>`==========`를 출력하세요.
   - Prompt `Enter ID to look up: ` for an ID.
   <br>`Enter ID to look up: `를 출력하여 ID를 입력받으세요.
   - Print `==========`.
   <br>`==========`를 출력하세요.
   - Print `student-id : student-name` if the ID exists, or `student-id : not found` if not.
   <br>ID가 있으면 `학생id : 학생이름`을, 없으면 `학생id : not found`를 출력하세요.

## Constraints
- Use only: print, input, f-strings, if, for loops, lists, dictionaries.
<br>print, input, f-string, if, for 루프, 리스트, 사전만 사용하세요.
- Do not use: while loops, functions, try-except, return, file operations, random module.
<br>while 루프, 함수, try-except, return, 파일 작업, random 모듈을 사용하지 마세요.
- Assume valid inputs (integer for `n`, strings for IDs/names).
<br>유효한 입력을 가정하세요 (`n`은 정수, ID와 이름은 문자열).
- Use exact output formats shown in the example.
<br>예시에 나온 정확한 출력 형식을 사용하세요.

## Example Run 실행 예

### 마지막에 물어보는 id 를 찾을 수 있는 경우
```
Enter number of students: 2
Number of students: 2
==========
Enter student ID: A123
Enter student name: Alice
Enter student ID: B456
Enter student name: Bob
==========
A123 : Alice
B456 : Bob
==========
Enter ID to look up: B456
==========
B456 : Bob
```

### 마지막에 없는 id 를 찾으려고 하는 경우
```
Enter number of students: 2
Number of students: 2
==========
Enter student ID: A123
Enter student name: Alice
Enter student ID: B456
Enter student name: Bob
==========
A123 : Alice
B456 : Bob
==========
Enter ID to look up: C789
==========
C789: Not found
```

## Submission
- Ensure it passes all tests (run `pytest` if available).
<br>모든 테스트를 통과하는지 확인하세요 (`pytest` 실행 가능 시).

## Tips
- Use `int(input(...))` for `n`.
<br>`n`에 대해 `int(input(...))`을 사용하세요.
- Include comments `# PART 1`, `# PART 2`, `# PART 3` before each section.
<br>각 섹션 전에 `# PART 1`, `# PART 2`, `# PART 3` 주석을 포함하세요.
- Iterate with `for id in students` to print dictionary pairs.
<br>`for id in students`로 사전 key value 쌍을 출력하세요.
- Match output formats exactly.
<br>출력 형식을 정확히 맞추세요.

__Happy coding!__

## Grading Criteria 채점 기준

| Criteria<br>기준 | Points<br>배점 |
|:-----:|:-----:|
| Is the code written according to Python syntax?<br>Python 문법대로 작성되었는가? | 2 |
| Does code respect style guidelines?<br>코드 스타일 권고사항을 준수하는가? | 1 |
| Is the result as expected?<br>결과가 예상과 같은가? | 2 |

``From here is common to all assignments.``

## Submission 제출 방법

1. Modify the contents of the `exercise.py` file to write your program.<br>`exercise.py` 파일의 내용을 수정하여 프로그램을 작성합니다.
2. Use the GitHub online editor to commit and push your changes. (See below for detailed instructions)<br>GitHub 온라인 편집기를 사용하여 수정 사항을 커밋하고 푸시합니다. (자세한 사용법은 아래 참조)
3. At the Actions tab of your Github repository, please check the result.<br>깃헙 저장소의 Actions 탭에서 결과를 확인 바랍니다.

## Shared Computer Warning<br>공용 컴퓨터 사용 시 주의사항

* **University labs**: Always use **incognito/private mode** (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>N</kbd>) to access GitHub. Closing the window automatically logs you out.<br>**대학 컴퓨터실**: 반드시 **시크릿 모드** (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>N</kbd>)로 GitHub에 접속하세요. 창을 닫으면 자동으로 로그아웃됩니다.

<details>
<summary><h2>How to Use the GitHub Online Editor<br>Github 온라인 편집기 사용법</h2></summary>

* Press the <kbd>.</kbd> key while viewing the files in your repository on GitHub. This will launch a web version of VS Code.<br>저장소의 [Code] 탭을 선택 후 <kbd>.</kbd> 키를 누르면 MS VS Code 의 Web version 이 시작됨
* Make your changes to the `exercise.py` file.<br>`exercise.py` 파일을 수정
* To commit your changes, click on the branch icon on the left sidebar (the third icon after the magnifying glass).<br>수정 사항을 commit 등록 하려면 왼쪽에서 줄 셋 아래 (확대경 다음) 세번째 가지치기 아이콘 선택
* Click the "+" sign next to the filename to stage your changes.<br>파일 이름의 오른쪽 + 기호 선택 (staging)
* Write a brief description of your changes in the text box above.<br>위 빈칸에 변경 사항 설명 입력
* Click "Commit & Push."<br>[커밋 및 푸시] 선택
* Click "Back to Repository" on the branch icon to return to your repository.<br>줄 셋 의 [리포지토리로 이동] 선택하여 저장소로 복귀

</details>


<details>
<summary><h2>Common Git Commands<br>주요 Git 명령어</h2></summary>

If you work with Git from a terminal (e.g., VS Code terminal, WSL, or macOS Terminal), these are the commands you will use most often.<br>터미널(VS Code 터미널, WSL, macOS 터미널 등)에서 Git을 사용하는 경우, 가장 자주 사용하는 명령어입니다.

| Command | Description |
|:--------|:------------|
| `git status` | Show which files have been changed<br>변경된 파일 확인 |
| `git add <file>` | Stage a file for commit<br>커밋할 파일 준비 (스테이징) |
| `git commit -m "message"` | Save staged changes with a description<br>스테이징된 변경 사항을 메시지와 함께 저장 |
| `git push` | Send commits to GitHub<br>커밋을 GitHub에 전송 |
| `git log --oneline` | View commit history (one line per commit)<br>커밋 히스토리 조회 (한 줄씩) |
| `git diff` | See what changed before committing<br>커밋 전 변경 내용 확인 |

**Typical workflow**<br>**일반적인 작업 흐름:**

```bash
git add exercise.py
git commit -m "Add loop to calculate factorial"
git push
```

</details>

## Writing Descriptive Git Commit Messages<br>커밋 메시지 작성 권고안

* To help you develop better coding habits, we encourage descriptive Git commit messages when committing changes to your repository.<br>보다 바람직한 코딩 습관을 기르기 위해, 저장소에 변경 사항을 등록할 때 메시지에 보다 자세히 설명하는 것을 권합니다.
* A good commit message clearly explains what you changed and why, making it easier for you to understand your work later.<br>바람직한 커밋 메시지는 무엇을 변경했는지, 왜 변경했는지를 명확히 설명하여 나중에 수정 사항을 이해하기 쉽게 도와줄 것입니다.

### Guidelines for Commit Messages<br>메시지 작성 지침

* **Use the imperative mood** — write as if giving an instruction: "Add", "Fix", "Update", "Refactor".<br>**명령형으로 작성** — "Add", "Fix", "Update", "Refactor"와 같은 동사로 시작합니다.
* **Capitalize the first word** and do not end with a period.<br>**첫 글자는 대문자**로 쓰고, 마침표는 붙이지 않습니다.
* **Keep it concise** — aim for 15–50 characters, but ensure clarity.<br>**간결하게** — 15–50자 정도로 작성하되, 명확성을 유지합니다.
* **Be specific** — describe *what* changed and *why*, not just "update" or "fix".<br>**구체적으로** — 무엇을 왜 변경했는지 설명합니다. 단순히 "update"나 "fix"는 너무 일반적입니다.

### Examples 예시

| | Message | Why |
|:---:|:--------|:----|
| Good | `Add factorial function to exercise.py` | Clearly states what was added<br>무엇을 추가했는지 명확히 설명 |
| Good | `Fix off-by-one error in loop counter` | Identifies the bug and location<br>버그와 위치를 구체적으로 식별 |
| Good | `Update print format to match expected output` | Explains purpose of the change<br>변경의 목적을 설명 |
| Bad | `update` | Too vague — what was updated?<br>너무 모호 — 무엇을 수정했는지 알 수 없음 |
| Bad | `fix 1` | No context — fix what?<br>맥락 없음 — 무엇을 수정했는지 알 수 없음 |
| Bad | `changed file` | Every commit changes a file — this says nothing<br>모든 커밋은 파일을 변경함 — 아무 정보도 없음 |

### Why It Matters<br>왜 중요한가

* Clear commit messages improve collaboration, debugging, and code review in real-world projects.<br>커밋 메시지가 명확하면 프로젝트 실무에서 공동 작업, 버그 수정, 코드 검토에서 도움을 얻을 수 있을 것입니다.
* Your commit history tells the story of how your code evolved — make it readable.<br>커밋 히스토리는 코드가 어떻게 발전했는지 보여주는 기록입니다 — 읽기 쉽게 작성하세요.

### Resources 참고 자료
* [How to Write a Git Commit Message](https://cbea.ms/git-commit/)
* [좋은 Git Commit message 작성법](https://velog.io/@k-minsik/좋은-Git-Commit-message-작성법)

<details>
<summary><h2>NOTICE REGARDING STUDENT SUBMISSIONS<br>제출 결과물에 대한 알림</h2></summary>

* Your submissions for this assignment may be used for various educational purposes. These purposes may include developing and improving educational tools, research, creating test cases, and training datasets.<br>제출 결과물은 다양한 교육 목적으로 사용될 수 있을 밝혀둡니다. (교육 도구 개발 및 개선, 연구, 테스트 케이스 및 교육용 데이터셋 생성 등).

* The submissions will be anonymized and used solely for educational or research purposes. No personally identifiable information will be shared.<br>제출된 결과물은 익명화되어 교육 및 연구 목적으로만 사용되며, 개인 식별 정보는 공유되지 않을 것입니다.

* If you do not wish to have your submission used for any of these purposes, please inform the instructor before the assignment deadline.<br>위와 같은 목적으로 사용되기 원하지 않는 경우, 과제 마감일 전에 강사에게 알려주기 바랍니다.

</details>

## Acknowledgments

* The template for this assigment is registered as a part of #C-2025-016393 in the Korea Copyright Commission.
* Various LLMs and AI tools helped implement the templates for this assignment.<br>다양한 LLM 및 AI 도구가 이 과제의 템플릿 구현에 도움을 주었습니다.
    - Google Gemini
    - xAI Grok3
    - Claude.ai
    - Perplexity Sonar

``Until here is common to all assignments.``
