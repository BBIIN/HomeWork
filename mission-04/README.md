# Grid를 사용한 새소식 구현

**HTML**
```
  <figure class="imgBox">
    <img src="w3c.png">
    <figcaption>W3C 리뉴얼</figcaption>
  </figure>
```
\- figure태그를 이용해 img와 figcaption에 이미지 설명을 넣어줌.

**CSS**
```
  grid-area: 2 / 1 / 2 / 1;
```
\- grid-area를 사용해 위치 지정.

```
  border-bottom:1px solid;
  border-image:linear-gradient(90deg, #A9A9A9 -1.32%, #FFFFFF 100%);
  border-image-slice: 1;
  ```
 \- border에 gradient를 사용.


 ## Result

 ![](result.png)
