# Vue環境構築

- node.js + vueの環境です。

## VueDock

1. リポジトリをクローン

   ```
   git clone https://github.com/Sodai-circle/Vue.git vue_app/vuedock
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

   
