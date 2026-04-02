# (C# 코딩) 로그인 화면

## 개요
- C# 프로그래밍 학습
- 1줄 소개: 아이디와 패스워드를 입력해야 하는 로그인 화면
- 사용한 플랫폼: 
	- C#, .NET Windows Forms, Visual Studio, GitHub
- 사용한 컨트롤:
	-TextBox, Button, Label
- 사용한 기술과 구현한 기능:
	- Visual Studio를이용하여 UI 디자인
	- 논리 연산자 사용으로 로그인 성공 여부 확인
	- Placeholder 기능 구현
	- 탭을 이용한 입력 포커스 제어

## 실행화면(과제1)
-과제1 코드의 실행 스크린샷
![과제1 실행화면](img/project1.png)
![과제1 실행화면](img/project2.png)
![과제1 실행화면](img/project3.png)

- 과제내용
	- Label(표시), Textbox(입력), Button(전송)을 정확히 배치
	- TextBox에 Placeholder 기능 구현
	- 아이디와 패스워드 처리 기능 구현
- 구현내용과기능설명
	- UI 구성 (TextBox(아이디, 패스워드), Button(로그인) 배치)
	- Placeholder 기능 구현 (아이디와 페스워드 입력 힌트 표시)
	- 로그인 기능 구현 (아이디와 패스워드 모두 일치시 로그인 성공 출력/둘 중 하나라도 틀릴시 로그인 실패 출력)

## 실행화면(과제2)
- 과제2 코드의 실행 스크린샷
![과제2 실행화면](img/project4.png)

- 과제내용
	- 아이디 또는 페스워드가 잘못 입력되었을 떄 Label로 에러 메시지 출력
	- Enter키로 넘어가는 기능 구현
- 구현내용과기능설명
	- Lable 컨트롤 추가(에러 메시지 출력용)
	- Visible 속성으로 아이디또는 페스워드가 잘못 입력되었을 떄만 Label을 띄우게 함
	- 아이디 입력 후 Enter키 누르면 패스워드 입력으로 이동
	- 패스워드 입력 후 Enter키 누르면 로그인 시도
