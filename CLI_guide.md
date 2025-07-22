# CLI

### Basic commands

- `pwd` : 현재 작업중인 디렉토리의 절대경로
- `touch <file>` : 파일 생성
- `mkdir <directory>` : 디렉토리 생성
- `ls` : 현재 작업중인 디렉토리의 항목들 나열
- `cd <directory>` : 작업 디렉토리 변경
- `cp <file1> <file2>` : 파일 복사
- `mv <file> <dirctory>` : 파일 옮기기 
  - 이때 디렉토리에 수정할 파일명으로 쓰면 파일명을 바꿀 수 있다 
- `rm <file/directory>` : 파일 또는 디렉토리 삭제
  - 디렉토리 삭제하려면 옵션 `-r`
- `cat`, `less`, `head`, `tail` : 파일 내용 출력 

<br>

### 기타 유용한 명령어
- `code` : 특정 디렉토리를 vs code에서 열기
  - e.g., 현재 작업 중인 디렉토리를 열려면 `code .`

<br>

### 경로

- `/` : root
- `~` : 홈
- `.` : 현재 디렉토리
- `..` : 상위 디렉토리

#### 절대경로와 상대경로

- 절대경로는 root부터 시작한다.

  (ex) `/c/Users/YJSHIN/Desktop` 이건 절대경로

- 상대경로는 현재 작업중인 디렉토리를 기준으로 한다.

  (ex) `../git_prac` 이건 상대경로

<br>

### Options

- command 뒤에 `-[option]` 붙여서 사용
- 여러 개를 한 번에 사용할 수도 있음
```
command -x
command -abcd
```

<br><br>

# Markdown

- 파일명(확장자) `.md`
- 참고용: [Markdown guide](https://www.markdownguide.org/basic-syntax/)
