# Science of science研究会 2024 オフィシャルウェブサイト

本リポジトリは、第1回Science of science研究会の公式ウェブサイト用リポジトリです。
本コードは、[ACL 2023](https://github.com/acl-org/acl-2023)からフォークしておりますので、編集の詳細につきましてはフォーク元のREADMEをご覧ください。

- Webpage: https://sciscijp.github.io/scisciconfJP2024/

## How to contribute

### 1. Clone

```
git clone git@github.com:ScisciJP/scisciconfJP2024.git
```

### 2. Build with docker

```
cd scisciconfJP2024
docker build -t scisciconfjp2024/website .
docker run --rm -p 4000:4000 -v $(pwd):/srv/jekyll scisciconfjp2024/website
```

-> http://0.0.0.0:4000/scisciconfJP2024/ からアクセスできます。

### 3. Edit pages

branchを切ってから、編集してください。
編集する回数の多い箇所は、フォーク元の[こちら](https://github.com/acl-org/acl-2023?tab=readme-ov-file#important-files)に記載があります。

### 4. Push to repository

```
git commit -m "編集内容"
git push origin <branch_name>
```

- push後は、プルリクエストを出してください。
- プログラム委員が確認次第、随時更新します。


# プログラム運営委員

Contact: [sciscijp@googlegroups.com](mailto:sciscijp@googlegroups.com)

* 三浦 崇寛(東京大学)