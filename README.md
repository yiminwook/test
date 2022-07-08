# test list

git remote rename pair team1 // pair -> team으로 변경 시

git remote remove // pair 끊기

reset HEAD~1 사용시 git이 자꾸 꼬인다, 신중하게 commit을 작성하여 history를 관리하자

rebase-i HEAD~1 vi편집기에 대한 지식 필요, 추후 다시 test

mkdir folder, touch file.txt

띄어쓰기가 포함된 파일명은 항상 ""를 사용

not staged file : 수정사항이 있어 add된 파일 // red - commit 작성이 필요한 상태, green - push가 가능한 상태

untracked file : 수정사항이 있거나 새로 만들어진 파일, git에 업로드를 위해서는 add필요

push 된 파일명을 바꿀때엔 mv를 사용

push 된 파일이 gui에서 제거되었을때 복원법 // git checkout -- filename.txt 

gui에서 파일을 삭제시, git rm으로 삭제후 git commit -m ""

gui에서 파일명 변경시, rm으로 이전 파일 삭제&commit, 변경한 파일명으로 add

빈폴더를 add 할 수 있는가 -> 불가능

폴더안에 파일을 add하면 파일채로 올라가는가? -> 가능

각각에 폴더안에 같은 이름의 파일을 add하면 -> 현재경로의 파일만 add

파일이 존재하지 않는 다른 경로에서 같이 이름의 파일이 서로 다른 폴더에 있을때 파일명으로만 add가 가능한가? -> 파일명을 포함한 정확한 경로로 add해야됨

폴더 내 파일을 전부 삭제시 폴더도 자동으로 삭제됨


