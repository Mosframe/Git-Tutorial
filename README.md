# Git-Tutorial
Git Tutorial

- 이슈 이둉 하기
    - 이슈에 이미지나 코드의 해시코드를 링크하여 활요한다.
    - 이슈를 할당하여 오픈하고 이슈를 해결하면 이슈를 종료처리한다.


- 콘솔

    // 클론
    > git clone http://......

    // 현재 상태들 확인하기
    > git status

    // 설정
    > git config --global user.name "Mosframe"
    > git config --global user.email ceo.mosframe@gmail.com

    // 설정 확인
    > git config --list

    // 커밋
    > git commit -a -m "README 수정"  // 추가,수정된 것들 모두 커밋

    // 로그 확인
    > git log -2 // 마지막 2개만 확인
    // 최신로그가 최상위에 출력됨
    // 리스트가 스크롤될 경우 출력을 종료하려면 :q

    // 원격 저장소 주소 얻기
    > git remote -v
    origin  https://github.com/Mosframe/Git-Tutorial.git (fetch)
    origin  https://github.com/Mosframe/Git-Tutorial.git (push)

    // 원격지 추가하기
    > git remote add origin https://github.com/Mosframe/Git-Tutorial.git

    // 푸시하기
    > git push origin master

    // 새로운 파일 추가
    > git add "파일명"
    > git add . // 모두 추가

    // 풀
    > git pull origin master






