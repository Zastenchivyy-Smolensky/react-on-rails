このアプリはreact-on-railsで作ったアプリである！


command line
ここではreact-on-railsのプロジェクトを作成するためのコマンドを記載するランである.
1.
terminal: react new react-on-rails
(railsでアプリを作るコマンドである)
2.プロジェクトができば,gemfileに移り,以下のコードをgemfileに記載する.
gemfile
gem "react-rails"
gem "webpacker"

3.bundle installでインストールする
terminal:
＄　bundle install

4.webpackerをインストールする 
terminal: 
＄　rails webpacker:install
terminal: 
＄　rails webpacker:install:react

5.reactをインストールする.
$　rails g react:install

これらのコマンドを実行することによりreact-on-railsでアプリを作ることができる.

次に,React Routerでバージョンによるエラーが発生してしまった場合は,react-domのバージョンを下げることをお勧めする.
terminal: npm install react-router-dom@5


参考文献
URL:
https://qiita.com/k-penguin-sato/items/e3cc04f787cf3254cfae
タイトル:ReactをRailsと共に使う方法

