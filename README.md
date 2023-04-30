# TypeScript Blockchain Practice

TypeScript로 작성된 간단한 블록체인 예제입니다.

## 구현 내용

1. Block 클래스는 이전 블록의 해시(prevHash), 높이(height), 데이터(data)를 입력받아 새로운 블록의 해시(hash)를 생성합니다.
2. Blockchain 클래스는 블록 배열(blocks)을 가지며, getPrevHash() 메서드로 이전 블록의 해시를 반환하고, addBlock() 메서드로 새로운 블록을 추가합니다.
3. Blockchain 클래스는 getBlocks() 메서드로 블록 배열을 반환합니다.

TypeScript의 정적 타입 검사에 대해 공부하였으며, 
예제를 통해서 클래스, 인터페이스, 정적 메서드, Node.js의 crypto 모듈 등을 사용해 보았습니다.

## 실행 방법

코드를 실행하면 새로운 블록을 추가하고, 블록 배열을 출력합니다.

```bash
$ npm install
$ npm start

## 참고자료
- PoiemaWeb - TypeScript Class
Javascript에 typescript .d.ts.파일 추가하기
- https://github.com/DefinitelyTyped/DefinitelyTyped <br>
- npm i -D dev @types/node