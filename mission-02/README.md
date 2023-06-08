# webCafe 페이지 중 login form 구현

```
<legend class="hidden">로그인 폼</legend>
```
```
  .hidden {
  overflow: hidden;
  position: absolute !important;
  clip: rect(0, 0, 0, 0);
  clip-path: inset(50%);
  width: 1px;
  height: 1px;
  margin: -1px;
}
```
\- position에 !important를 주어 만약 다른 속성들과 겹쳐도 변경되지 않게끔 설정하였고,clip과 clip-path의 값을 이용해 화면에서 legend 요소가 안보이게 하였습니다.

```
  <li class="loginForm-box">
    <label for="login" class="txt">아이디</label>
    <input type="text" id="login" placeholder="euid@euid.dev"/>
  </li>
  <li class="loginForm-box">
    <label for="password">비밀번호</label>
    <input type="password" id="password" placeholder="8자리 이상"/>
  </li>
```
```
.txt {
  display: inline-block;
  width: 3.5rem; 
}
```

\- width를 지정하기 위해 inline에서 inline-block으로 변경하고 width 값을 입력해 두개의 li 크기를 맞추었습니다.

```
.login-btn {
  background: #ED552F;
  width: 3.125rem;
  height: 3.3125rem;
  border: 0;
  border-radius: 0.3125rem;
  color: #fff;
  position: absolute;
  left: 11.5625rem;
  top: 4.0625rem;
  font-size: 0.75rem;
}
```
\- 버튼의 position을 absolute로 바꿔 left와 top을 사용해 위치를 지정해주었습니다.

```
<ul class="memberService">
  <li><a href="/" class="serviceLink float-l">회원가입</a></li>
  <li><a href="/" class="serviceLink float-r">아이디 비밀번호 찾기</a></li>
</ul>
```
```
.float-l {
  float: left;
}
.float-r {
  float: right;
}
```
\- li들을 한 줄에 넣기 위해 각각 float left와 right를 단일 클래스로 주었습니다.