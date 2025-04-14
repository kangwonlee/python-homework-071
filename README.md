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
- Include comments `# PART 1`, `# PART 2`, `# PART 3` before each section.
<br>각 섹션 전에 `# PART 1`, `# PART 2`, `# PART 3` 주석을 포함하세요.
- Use exact output formats shown in the example.
<br>예시에 나온 정확한 출력 형식을 사용하세요.

## Example Run
```
Enter number of students: 2
Number of students: 2
==========
Enter student ID: A123
Enter student name: Alice
Enter student ID: B456
Enter student name: Bob
==========
Student ID: A123, Name: Alice
Student ID: B456, Name: Bob
==========
Random student: ID = A123, Name: Alice
==========
Enter ID to look up: C789
Queried ID: C789: Not found
```

## Submission
- Ensure it passes all tests (run `pytest` if available).
<br>모든 테스트를 통과하는지 확인하세요 (`pytest` 실행 가능 시).

## Tips
- Use `int(input(...))` for `n`.
<br>`n`에 대해 `int(input(...))`을 사용하세요.
- Iterate with `for id in students` to print dictionary pairs.
<br>`for id in students`로 사전 key value 쌍을 출력하세요.
- Match output formats exactly.
<br>출력 형식을 정확히 맞추세요.

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

## NOTICE REGARDING STUDENT SUBMISSIONS<br>제출 결과물에 대한 알림

* Your submissions for this assignment may be used for various educational purposes. These purposes may include developing and improving educational tools, research, creating test cases, and training datasets.<br>제출 결과물은 다양한 교육 목적으로 사용될 수 있을 밝혀둡니다. (교육 도구 개발 및 개선, 연구, 테스트 케이스 및 교육용 데이터셋 생성 등).

* The submissions will be anonymized and used solely for educational or research purposes. No personally identifiable information will be shared.<br>제출된 결과물은 익명화되어 교육 및 연구 목적으로만 사용되며, 개인 식별 정보는 공유되지 않을 것입니다.

* If you do not wish to have your submission used for any of these purposes, please inform the instructor before the assignment deadline.<br>위와 같은 목적으로 사용되기 원하지 않는 경우, 과제 마감일 전에 강사에게 알려주기 바랍니다.

``Until here is common to all assignments.``
