<form id="login-form" action="/signup" method="POST">
  <div>
    <label for="id">아이디</label>
    <input type="text" id="id" required />
  </div>
  <div>
    <label for="password">패스워드</label>
    <input type="password" id="password" name="password" required />
  </div>
  <div>
    <button type="submit">로그인</button>
  </div>
  <div id="info" />
</form>
