
# node.js는 단독으로 백엔드에서 사용할 수 있게 만든 프로그램. 홈페이지 첫 장면은 백엔드 시작할때 구동하는(?) 코드 이다.
# ES와 CJS코드방식 헷갈리지 말기!
# npm init -y -> dir -> index.js파일 설치 -> npm run test 
# 실행 할때 node index.js (XXXXXX!!XXXX) -> npm run으로 기입해야함
# npm으로는 start라는 고정값이 아닌 자유로운 key로 선언해도 된다.
# node_modules가 설치 되었다  -> 이 파일 프로젝트당 패키지가 설치 되었다. ==> 각 파일마다 프로젝트 모듈을 설치 해야한다! = npm i nodemon ===> 
# nodemon 모듈즈 파일이 크기 때문에 제외한 3개의 파일만 가져가며 다른 컴퓨터에서 사용할때 모듈즈 제외한 파일들만 모으고 "npm i"만 설치하면 package.json 내부 dependencies에 있는 버젼으로 자동 설치 된다.
