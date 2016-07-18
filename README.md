# bower-register
바우어에 패키지 등록을 위한 저장소


### 1.git 저장소 만들기

예제에서는 `bower-register` 라는 저장소를 만들었습니다.

내컴퓨터로 복사해서 등록할 파일들을 만듭니다.


### 2.bower.json 만들기

`bower init` 명령어로 `bower.json` 을 만듭니다.

깃저장소에서 복사해왔으면 기본정보는 다 입력이 되어있습니다.

패키지로 사용할 파일들을 모두 만들어 놓습니다.

### 3.git 저장소 커밋하기

등록할 파일들을 모두 만들었으면 git 저장소에 올립니다.

아래 명령어를 순서대로 입력합니다.

```sh
git add .
git commit -m 'first commit'
git pull
git push
```

원격저장소에 모두 올렸습니다.


### 4.바우어에 패키지 등록하기

아래 명령어로 바우어에 등록합니다.

```sh
bower register 패키지이름 git저장소주소
```

