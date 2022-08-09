# 깃허브 특강
- ">"를 사용하면 인용이 가능
>인용
- "#"으로 제목과 부제목 등을 설정이 가능
- 순서가 있는 목차와 없는 목차 설정이 가능
- 백텍을 사용하여 코드 입력도 가능
``` python
a = "여러줄 코드"
b = "입력이 가능"
print("a+b")
```

1. 순서가
2. 있는
3. 번호매기기

- 순서가
- 없는
- 번호
  - 매기기
  - 입니다.

## 깃허브에 올리는 법
- 작성 후 저장할 것 (ctrl + s)
- git init 입력
  - 폴더당 초반에 한번만 입력해야함
  - 두번 이상 입력하게되면 절대 안됨
- 저장 후 터미널에서 git add .
- git commit -m "설명작성"
- 중간중간 git log로 저장 기록 확인 가능
- 중간중간 git status로 상태 확인 가능
- git remote add <이름설정> <repository주소 복사>
  - 이름 설정에는 이름 지정하면 됨. ex)origin
  - 주소에는 github의 해당 repository 주소 복사해서 붙여넣기
- git remote -v
  - remote가 잘 되었는지 확인이 가능 
- git push <설정한 이름> master
  - 설정한 이름에는 위에서 설정한 이름 적으면 됨
  - ex) git push origin master
  - 이렇게 하면 깃허브상에 깃에서 작성한 내용이 업로드됨.

## 깃허브에서 내용 작성 후
- 추가적으로 깃허브상에서 내용을 작성한 후에는
- vscode에서 git pull origin master로 끌어온 후 내용을 작성해야 오류가 나지 않음.
- 그 후 vscode에서 내용 작성 후 저장
- git add .
- git commit -m "설명"
- git push origin master
- 이런식으로 진행하면 됨.

