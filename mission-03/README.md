# hover transition 구현

* 순서가 없는 리스트 이므로 ul태그 안에 li 생성.

* 마우스를 올렸을 때 박스가 펼쳐지기 위해 :hover 설정.
* 리스트가 접혀 있을 땐 다른 링크가 안보이도록 overflow: hidden을 적용.

```
  transition: padding-top 0.4s;
  transition-delay: 0.5s;
```
 \- 리스트에 transition-delay 주어 뒤늦게 내려오도록 적용.

 # Result
![result](https://github.com/BBIIN/HomeWork/assets/107901091/eb73cd60-9e89-4a22-a31d-e1278981895b)