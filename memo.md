## 学習メモ
- Laravelのバージョン指定
  - Laravel6のバージョン指定：`composer create-project "laravel/laravel=6.*" hello-world`
  - prefer-distオプションをつけることでLaravelの最新安定版を取得：`composer create-project --prefer-dist laravel/laravel hello-world`

- エラーログ出力場所：`storage\logs\laravel.log`

- No application encryption key has been specified.となったときの対応方法
  - 暗号化キーを設定する
  - https://qiita.com/ponsuke0531/items/197c76fcb9300d7c5f36
  
## コマンドログ
`composer create-project "laravel/laravel=6.*" laravelapp`
`php artisan serve`
