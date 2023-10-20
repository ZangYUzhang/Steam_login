# Steam_login
2023-10-20
Steam更新了新的登录接口 "https://login.steampowered.com/jwt/finalizelogin"


调用示例：
```python
    login = LoginExecutor(your_steam_account, password, shared_secret)
    session = login.login()
    login.test_is_logined()
```
