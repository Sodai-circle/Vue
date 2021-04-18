# Vue環境構築

- node.js + vueの環境です。

## VueDock

1. リポジトリをクローン

   ```
   git clone https://github.com/Sodai-circle/Vue.git vue_app/vuedock
   ```

2. vuedockの階層で

   ```
   docker-compose build node
   ```
   
   ```
   docker-compose up -d node
   docker-compose exec node bash
   npm install -g @vue/cli@next
   vue create 名前
   ```

   - 基本そのままEnterをおす。vueのバージョンは選択する。
   
   ```
   cd 名前
   npm run serve
   ```

3. [ここに](http://localhost:8080)アクセスし、うまくいっているか確認


## 使い方

- 始めるとき vuedockの階層で
   ```bash
   docker-compose up -d node
   ```
- 終わるとき
   ```bash
   docker-compose down
   ```

   
