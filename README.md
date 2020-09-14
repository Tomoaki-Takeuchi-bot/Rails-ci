## GitHub Actions の設定について

### ファイル

- linter.yml rubocop による linter check
- rspec.yml rspec による test (selenium のインストールとテスト)
- database.yml.github-actions (config にて)

### 追加 Gem

- gem 脆弱性診断
  `gem 'bundler-audit'`
- セキュリティ診断
  `gem 'brakeman'`

### gitignore 追加

.local/share/ruby-advisory-db
