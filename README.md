# Ruby Ruby on Rails学習

## 環境構築(macOS)
Ruby version 3.0.2 \
Rails version 7.0.0

### 1. 必要なツールのインストール
```
# Homebrew の更新
brew update

# rbenv と ruby-build のインストール
brew install rbenv ruby-build

# rbenv の初期設定
echo 'export RBENV_ROOT="$HOME/.rbenv"' >> ~/.zshrc
echo 'export PATH="$RBENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(rbenv init -)"' >> ~/.zshrc
source ~/.zshrc
```

### 2. Ruby のインストール
```
# Ruby のインストール可能バージョンを確認
rbenv install --list

# 特定の Ruby バージョンのインストール (例: 3.0.2)
rbenv install 3.0.2

# グローバルな Ruby バージョンの設定
rbenv global 3.0.2

# インストールされた Ruby バージョンの確認
ruby -v
```

### 3. Rails のインストール
```
# Rails のインストール (例: バージョン 7.0.0)
gem install rails -v 7.0.0 -N

# インストールされた Rails バージョンの確認
rails -v
```

## 参考
https://prog-8.com/docs/ruby-env
https://qiita.com/aki319809/items/9de7f14285cd0c69e2d2