# Python Homework Template
Please work on : `exercise.py`

## Purpose 목적:

Why do we want to do this assignment? What do we want to accomplish?

## Description 설명:

* Describe homework here

## Instructions 지침:

* How to do this homework
* `classroom.yml` file is at `.github/workflows/` folder. `.github` folder is hidden on the Linux operating system but will be visible on the Github repository.
* Please set `vars.PYTHON_GRADER_URL` in the `classroom.yml` in the repository settings (Settings > Secrets and Variables > Actions > Variables) to your grader image (e.g., ghcr.io/your-org/python-pytest:latest).
* Set your AI feedback natural language in `classroom.yml`.

## Example Run 실행 예시:

* input
```
input example here
```
* output
```
----------
output example here
```

## Tips 팁:

* please add some more hints here

__Happy coding!__

## Grading Criteria 채점 기준

| Criteria | Points |
|:--------:|:------:|
| Is the code written according to Python syntax?<br>코드가 파이썬 문법에 따라 작성되었는가? | 2 |
| Does the code satisfy the requirements?<br>코드가 요구사항을 충족하는가? | 3 |

``From here is common to all assignments.``

## Submission 제출 방법

1. Modify the contents of the `exercise.py` file to write your program.<br>`exercise.py` 파일의 내용을 수정하여 프로그램을 작성합니다.
2. Use the GitHub online editor to commit and push your changes. (See below for detailed instructions)<br>GitHub 온라인 편집기를 사용하여 수정 사항을 커밋하고 푸시합니다. (자세한 사용법은 아래 참조)
3. At the Actions tab of your Github repository, please check the result.<br>깃헙 저장소의 Actions 탭에서 결과를 확인 바랍니다.

## How to Use the GitHub Online Editor<br>Github 온라인 편집기 사용법

* Press the <kbd>.</kbd> key while viewing the files in your repository on GitHub. This will launch a web version of VS Code.<br>저장소의 [Code] 탭을 선택 후 <kbd>.</kbd> 키를 누르면 MS VS Code 의 Web version 이 시작됨
* Make your changes to the `exercise.py` file.<br>`exercise.py` 파일을 수정
* To commit your changes, click on the branch icon on the left sidebar (the third icon after the magnifying glass).<br>수정 사항을 commit 등록 하려면 왼쪽에서 줄 셋 아래 (확대경 다음) 세번째 가지치기 아이콘 선택
* Click the "+" sign next to the filename to stage your changes.<br>파일 이름의 오른쪽 + 기호 선택 (staging)
* Write a brief description of your changes in the text box above.<br>위 빈칸에 변경 사항 설명 입력
* Click "Commit & Push."<br>[커밋 및 푸시] 선택
* Click "Back to Repository" on the branch icon to return to your repository.<br>줄 셋 의 [리포지토리로 이동] 선택하여 저장소로 복귀


## Writing Descriptive Git Commit Messages<br>커밋 메시지 작성 권고안

* To help you develop a better coding habits, we encourage descriptive Git commit messages when committing changes to your repositroy.<br>보다 바람직한 코딩 습관을 기르기 위해, 저장소에 변경 사항을 등록할 때 메시지에 보다 자세히 설명하는 것을 권합니다.
* A good commit message clearly explains what you changed and why, making it easier for you to understand your work later.<br>바람직한 커밋 메시지는 무엇을 변경했는지, 왜 변경했는지를 명확히 설명하여 나중에 수정 사항을 이해하기 쉽게 도와줄 것입니다.

### Guidelines for Commit Messages<br>메시지 작성 지침
* Describe the change more specifically, e.g., "Add factorial function to exercise.py" or "Fix bug in sum calculation".<br>변경 사항을 보다 구체적으로 설명합니다. 예를 들어, "exercise.py에 팩토리얼 함수 추가" 또는 "합계 계산 버그 수정"과 같이 작성합니다.
* Use Action Verbs: Start with words like "Add", "Fix", "Update", or "Refactor".<br>영문의 경우, "Add", "Fix", "Update", "Refactor"와 같은 동사로 시작합니다.

* Avoid Vague Messages: Messages like "update" or "fix" can be too general.<br>"update", "fix"와 같은 메시지는 너무 일반적입니다.

* Keep It Concise: Aim for 15-50 characters, but ensure clarity.<br>15-50자 정도로 간결하게 작성하되, 명확성을 유지합니다.
* Examples 예:
  * Good: "Add unit tests for sort function in exercise.py"<br>바람직: "exercise.py의 정렬 함수에 대한 단위 테스트 추가"
  * Bad: "update", "fix 1", "changed file"<br>바람직하지 않음: "update", "fix 1", "changed file"

### Why It Matters 왜 중요한가
* Clear commit messages improve collaboration, debugging, and code review in real-world projects.<br>커밋 메시지가 명확하면 프로젝트 실무에서 공동 작업, 버그 수정, 코드 검토에서 도움을 얻을 수 있을 것입니다.

### Resources 참고 자료
* [How to Write a Git Commit Message](https://cbea.ms/git-commit/)
* [좋은 Git Commit message 작성법]( https://velog.io/@k-minsik/좋은-Git-Commit-message-작성법")

## NOTICE REGARDING STUDENT SUBMISSIONS<br>제출 결과물에 대한 알림

* Your submissions for this assignment may be used for various educational purposes. These purposes may include developing and improving educational tools, research, creating test cases, and training datasets.<br>제출 결과물은 다양한 교육 목적으로 사용될 수 있을 밝혀둡니다. (교육 도구 개발 및 개선, 연구, 테스트 케이스 및 교육용 데이터셋 생성 등).

* The submissions will be anonymized and used solely for educational or research purposes. No personally identifiable information will be shared.<br>제출된 결과물은 익명화되어 교육 및 연구 목적으로만 사용되며, 개인 식별 정보는 공유되지 않을 것입니다.

* If you do not wish to have your submission used for any of these purposes, please inform the instructor before the assignment deadline.<br>위와 같은 목적으로 사용되기 원하지 않는 경우, 과제 마감일 전에 강사에게 알려주기 바랍니다.

## Acknowledgments

* The template for this assigment is registered as a part of #C-2025-016393 in the Korea Copyright Commission.

``Until here is common to all assignments.``
