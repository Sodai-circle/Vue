# React環境構築

- node.js + reactの環境です。

- dockerを使ったvueの環境構築なのでvuedockと名付けています。

  

## VueDock

1. リポジトリをクローン

   ```
   git clone https://gitlab.com/welcome-to-sodai/vue.git vue_app/vuedock
   ```

2. vuedockの階層で

   ```
   docker-compose run --rm node sh -c "npm install -g vue-cli && vue init webpack ."
   ```

   - 基本そのままEnterをおす。
   - config/index.jsの該当部分を以下にする
   ```
    host: '0.0.0.0', // can be overwritten by process.env.HOST
   ```

3. ```
   docker-compose up -d node
   ```

4. [ここに](http://localhost:8080)アクセスし、うまくいっているか確認


## 使い方

- 始めるとき readockの階層で
   ```bash
   docker-compose up -d node
   ```
- 終わるとき
   ```bash
   docker-compose down
   ```

## まとめ

- Vueの環境構築ができた

## Next Step

- Vueを勉強していくのみ!
- Sodai.でチュートリアル作ってくれる方募集中です...

   
