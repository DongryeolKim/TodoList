# TodoList

I make TodoList app by myself.

1. 스테이징 //.은 현재 디렉토리의 모든 변경된 파일을 추가한다는 의미입니다. 만약 특정 파일만 추가하고 싶다면 해당 파일명을 지정가능
   git add.
   (스테이징 취소) git reset

2. 커밋
   git commit -m "작업한 내용에 대한 설명"
   (커밋취소) git reset --soft HEAD^

3. 푸쉬 // GitHub로 푸시 (git push) 커밋한 후, 원격 저장소(GitHub)에 변경 사항을 업데이트
   git push origin main
   (푸쉬치소) git reset --soft HEAD^
