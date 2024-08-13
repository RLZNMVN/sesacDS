# sesacDS
새싹강동-구글AI개발과정 데이터사이언스

1. remote repo(github)에 repo생성
    dataScience2024
    https://github.com/venture21/DataScience2024.git

2. local repo를 생성(복제)
   git clone https://github.com/venture21/DataScience2024.git

3. local repo에 파일 추가
   메모장에서 github_order.txt파일 하나 생성
   git add github_order.txt

3.5 git config --global user.name "venture21"
     git config --global user.email "phj@aicore.co.kr"

4. commit (변경된 내용 서술)
   git commit -m "github_order.txt파일을 생성합니다"

5. push
   git push (2단계인증->브라우저 인증)

6. 파일의 내용을 수정하고 싶을 때
   먼저 현재까지 파일의 remote repo에서 수정내용이 있는지 확인
   수정된 내용이 있으면 업데이트
   git pull
