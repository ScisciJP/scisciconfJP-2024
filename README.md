# Science of science研究会 2024 オフィシャルウェブサイト

This is the code for the official website for the 1st Annual Meeting of the Science of science conference in Japan. based on the code for [ACL 2023](https://github.com/acl-org/acl-2023).

## ローカルテスト


```
docker build -t scisciconfjp2024/website .
docker run --rm -p 4000:4000 -v $(pwd):/srv/jekyll scisciconfjp2024/website
```
