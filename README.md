### ajax 실습시 JSON Server 설치(가상 Rest Api)

- vscode 상단부 -> 터미널 -> 새 터미널

```shell script
$ mkdir json-server-exam
$ cd json-server-exam
$ npm init -y //노드 패키지 초기설정
$ npm install json-server -D 
//라이브러리 설치 [라이브러리 이름] -D (개발자모드)
```

- package.json에 추가
```json
"scripts": {
    "start": "json-server --watch db.json --port 5000"    
  },
```
- json-server-exam폴더로 가서
- `$ npm start`로 서버실행

---