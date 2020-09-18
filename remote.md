# 원격 저장소 활용하기

## 충돌 상황

```bash
$ git push origin master
To https://github.com/kcloud721/remote.git
 ! [rejected]        master -> master (fetch first)
error: 레퍼런스를 'https://github.com/kcloud721/remote.git'에 푸시하는데 실패했습니다
힌트: 리모트에 로컬에 없는 사항이 들어 있으므로 업데이트가
힌트: 거부되었습니다. 이 상황은 보통 또 다른 저장소에서 같은
힌트: 저장소로 푸시할 때 발생합니다.  푸시하기 전에
힌트: ('git pull ...' 등 명령으로) 리모트 변경 사항을 먼저
힌트: 포함해야 합니다.
힌트: 자세한 정보는 'git push --help'의 "Note about fast-forwards' 부분을
힌트: 참고하십시오.
```

```bash
$ git pull origin master
```

