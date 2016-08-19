# 틀(Tle)-CSS
최소 지향 한글 CSS 프레임워크

# 특징
* "틀"은 정말 간단한 CSS 프레임워크예요.
* [milligram](http://milligram.github.io/)에서 많이 가져왔지만 조금 달라요.
* 기본 설정은 거의 호환돼요.

# 사용 예
## jade에서 ([meteor-jade](https://atmospherejs.com/spectrum/jade)랑 같이 사용하세요)
### 단추
```
 .단추
 .단추.안됨
 .단추.외곽선
 .단추.외곽선.안됨
 .단추.투명
 .단추.투명.안됨
``` 
 이렇게 쉬운 우리말로 표현하면 돼요. 순서는 상관없고요.
### 숨김 
``` 
 .숨김
```
특정 요소를 안 보이게 해줘요.
### 서식
```
 .한줄
```
서식에서 label을 한 줄로 붙여 쓸 때 사용해요.
### 틀
```
 .틀
   .행.감쌈.시작.종료.중앙.늘임.바닥.붙임
   .열.머리.바닥.중앙
     .열.틈1-10.틈1-5.틈1-4.틈1-3.틈1-2.틈2-3.틈3-4.틈4-5.틈9-10
     .열.칸1-10.칸1-5.칸1-4.칸1-3.칸2-5.칸1-2.칸3-5.칸2-3.칸3-4.칸4-5.칸9-10
```
틈은 벌어진 정도고 ```틈1-4```면 1/4만큼 ```틈1-2```면 1/2만큼 떨어뜨려요.

칸은 한 칸의 크기예요. 틈과 마찬가지로 ```칸1-2```면 1/2, ```칸3-4```면 3/4이죠.
### 붙이고 떨어뜨리고
```
  .오른쪽착
  .왼쪽착
  .떨어져
```
한 줄에 몰아서 붙일 때 사용해요.

```오른쪽착```, ```왼쪽착``` 사용 후 원래대로 되돌리려면 ```떨어져```를 쓰세요.
