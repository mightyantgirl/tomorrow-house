(https://mightyantgirl.github.io/tomorrow-house/)

---

### 1. GNB

- 로그인을 하지 않은 경우

```html
<div class="button-group">
  <button class="gnb-icon-button is-search lg-hidden" type="button" aria-label="검색 열기 버튼">
    <i class="ic-search"></i>
  </button>

  <a class="gnb-icon-button is-cart" href="/" aria-label="장바구니 열기 버튼">
    <i class="ic-cart"></i>
    <!-- <strong class="badge">5</strong> -->
  </a>

  <div class="gnb-auth sm-hidden">
    <a href="/">로그인</a>
    <a href="/">회원가입</a>
  </div>
</div>
```

- 로그인을 했을 경우

```html
<div class="button-group">
  <button class="gnb-icon-button is-search" type="button" aria-label="검색 열기 버튼">
    <i class="ic-search"></i>
  </button>

  <a href="/" class="gnb-icon-button sm-hidden" aria-label="북마크 페이지 이동 버튼">
    <i class="ic-bookmark"></i>
  </a>

  <a href="/" class="gnb-icon-button sm-hidden" aria-label="내소식 페이지 이동 버튼">
    <i class="ic-bell"></i>
  </a>

  <a class="gnb-icon-button is-cart" href="/" aria-label="장바구니 열기 버튼">
    <i class="ic-cart"></i>
    <strong class="badge">5</strong>
  </a>

  <button type="button" class="gnb-avatar-button sm-hidden" aria-label="마이 메뉴 열기 버튼">
    <div class="avatar-32">
      <img src="./assets/img/img-user-01.jpg" alt="사딸라아잣시" />
    </div>
  </button>
</div>
```
