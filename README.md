# TestGit

## Git 명령어 알아보기

## Git 초기설정하기 명령어

-   이메일 등록하기 :git config --global user.email "이메일주소"
-   등록한 이메일 주소보기 :git config --global user.email
-   이름 등록하기 :git config --global user.name "이름"
-   등록한 이름 주소보기 :git config --global user.name
-   이후 리포지토리에 있는 내용대로 실행하여 연동

Git 사용 명령어

-   **git init**
    -   여러 파일을 추적하는\*\* .git 폴더\*\*가 생성됩니다.
    -   Terminal 창에서 원하는 디렉토리로 이동후 git init 명령어를 입력하면 해당 디렉 토리는 이제 Local Git Repository로 등록 되고, 이제 git 명령어를 사용할 수 있습니다.
    -   얼핏보면 차이가 없지만, '.git' 파일이 생성되어 숨어 있습니다.
    -   여러 파일을 추적하는\*\* .git 폴더\*\*가 생성됩니다.
-   **git add**
    -   Git이 추적하고 있는 수정된 파일이 working directory에서 staging area에 저장됩니다.
-   **git commit**
    -   staging area에 저장됐던 파일이 local repository로 확정됩니다.
    -   commit은 "작업을 마무리 했다"라는 버전 등록을 의미합니다.
-   git push <리모트 저장소 이름> <push할 브랜치 이름>
    -   git push 명령어를 사용하면, 드디어 로컬 저장소에 있던 파일을 원격 저장소로 보낼 수 있게 됩니다.

## 실습

[##_Image|kage@du8mhe/btq1WKWh1ve/LxXZ9UKCj3I5wHElziFLnK/img.png|alignLeft|data-origin-width="0" data-origin-height="0" data-ke-mobilestyle="widthContent"|||_##]

### git add <파일 이름>

-   Git이 추적하고 있는 수정된 파일이 working directory에서 staging area에 저장됩니다.
-   NewTextDocument.txt 라는 파일을 staging area에 추가

[##_Image|kage@dS9jRQ/btq1YjReuN4/PU8gjcHo9ePa310SfrbuOk/img.png|alignLeft|data-origin-width="0" data-origin-height="0" data-ke-mobilestyle="widthContent"|||_##]

### git commit -m "comment"

-   staging area에 있는 file을 local repository로 이동  
    [##_Image|kage@2deOx/btq1R85dzlT/NSQ5SPWkE5HpkEgFo7f9n0/img.png|alignLeft|data-origin-width="0" data-origin-height="0" data-ke-mobilestyle="widthContent"|||_##]

### git clone <주소>

[##_Image|kage@zPnoJ/btq1U6Z7AEX/wsL0KybNvqOu0846KKzfc1/img.png|alignCenter|data-origin-width="0" data-origin-height="0" data-ke-mobilestyle="widthContent"|||_##]
