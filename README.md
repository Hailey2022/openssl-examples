# openssl-examples

#### 加密文字
```
echo "hi" | openssl enc -e -aes-256-cbc -salt -pbkdf2 -iter 1000000 -md sha512 -base64
```
