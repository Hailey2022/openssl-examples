# openssl-examples

#### 加密文字
```
echo "hi" | openssl enc -e -aes-256-cbc -pbkdf2 -md sha512 -a
```
