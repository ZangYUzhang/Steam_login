# Steam_login
2023-10-20
Dealing with the new Steam login URL：https://login.steampowered.com/jwt/finalizelogin


Call Example：
```python
    login = LoginExecutor(your_steam_account, password, shared_secret)
    session = login.login()
    login.test_is_logined()
```
