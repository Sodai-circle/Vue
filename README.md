# Vue環境構築

- vueの環境です。

## VueDock

1. リポジトリをクローン

   ```
   git clone https://github.com/Sodai-circle/Vue.git vue_app/vuedock
   ```

2. vuedockの階層で

   ```
   docker-compose build vue
   ```
   
   ```
   docker-compose up -d vue
   docker-compose exec vue bash
   vue create 名前
   ```

   - 基本そのままEnterをおす。vueのバージョンは選択する。
   - typescriptを入れる場合はここで選択する。
   
   ```
   cd 名前
   yarn serve
   ```

3. [ここに](http://localhost:8080)アクセスし、うまくいっているか確認


## 使い方

- 始めるとき vuedockの階層で
   ```bash
   docker-compose up -d vue
   ```
- 終わるとき
   ```bash
   docker-compose down
   ```

   
