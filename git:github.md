# Git,Github

1. **git이란?**
   - 분산버전관리시스템

2. **공간분리 마술(git 3가지)**

| Modified      | 파일이 수정된 상태 (add, staging area 로이동) |
| ------------- | --------------------------------------------- |
| **staged**    | **임시공간 2통 커밋 의미있는 저장**           |
| **committed** | **커밋이 된 상태**                            |

3. **git 명령어**

   - Git init : git 시작 (master) 로 변환 버전 기록 중 
     - ✔️ 초보자들은 절때 절때 기억할 것은 파일 안에서 꼭 시작할 것

   - git status : git 상태를 알려줌
   - Git add : staging area 로 파일이 넘어감
   - git commit - m '메시지' : staging area 에서 로컬 repositoryf 로 업로드
   - Git log : git 버전 확인
   - Git remote : 원격 저장소로 저장 , git 사이트로 올리는 것
     - Git remont add origin [허브주소]

   - Git push : 생성한 파일을 원격 저장소에 업로드
   - Git config --global --list : 현재 갓허브 연결된 것은 확인 시켜줌 