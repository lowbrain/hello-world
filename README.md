# Hello-World

## メモ
- https://qiita.com/syukai/items/0d4bf27f82fef9965cdd
  
## 原理原則
- [GitHub flow](https://guides.github.com/introduction/flow/)
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)

<details>
<summary>参考資料などなど</summary>

## GitHub Learning Lab のおすすめコース
### Paths
- [First Day on GitHub](https://lab.github.com/githubtraining/first-day-on-github) 
- [First Week on GitHub](https://lab.github.com/githubtraining/first-week-on-github)
### Courses
- [GitHub Actions: Hello World](https://lab.github.com/githubtraining/github-actions:-hello-world)

## その他参考
### Git
- [Pro Git book 日本語訳](http://git-scm.com/book/ja/v2)
- [Try Git simulator](http://try.github.io/)
### GitHub
- [GitHubオープンソースガイドライン](https://opensource.guide/ja/)
### Flow
- [Git+GitHub入門 #07：ブランチ運用のガイドライン Git Flow](https://www.youtube.com/watch?v=NxjTTIUl_Pw)
- [Git+GitHub入門 #08：プルリクエストを使ったブランチ運用 GitHub Flow](https://www.youtube.com/watch?v=xDMBBzWiSEI)
</details>

## 環境まわり

### Git
- [公式サイト](https://gitforwindows.org/)からインストーラーを入手し導入
  - "Select Components"タブの`Windows Explorer Integration`は、右クリックメニューにGit関連のメニューが出てきてほしくない場合にチェックを外す  
  - "Choosing the default editor used by Git"タブは、VSCodeを標準利用するので`Use Visual Studio Code as Git's default editor`を選択
  - "Adjusting the name of the initial branch in new repositories"タブは、GitHub連携を前提とするため`Override the default branch name for new repositories`を選択し、指定名は`main`に
  - "Choosing HTTPS transport backend"タブは、GitHub連携を前提とするため`Use the OpenSSL library`に
  - "Configuring the line ending conversions"タブは、勝手に改行コードを変換されたくないので`Checkout as-is, commit as-is`を選択
  - "Configuring the terminal emulator to use with Git Bash"タブは、お好みで
- インストール後においては、ターミナルを開いて以下グローバル設定を施す
  ```DOS
  $ git config --global user.name "GitHubのアカウント名" 
  $ git config --global user.email "GitHubアカウントに紐づく"***@users.noreply.github.com"アドレス" 
  ```

### VSCode
- 導入するExtension
  - [Japanese Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-ja)
  - [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
    - [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
    - [Remote - SSH: Editing Configuration Files](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh-edit)
    - [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
    - [Remote - WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)
  - [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- Visual Studio Code + Remote Containersで開発する
  - [Developing inside a Container](https://code.visualstudio.com/docs/remote/containers)を参照してベースとしての開発環境を構築する
  - Container内のVSCodeに導入するExtensionは以下のとおり
    - [GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)

### Docker

### React
- React DevTools(ブラウザの拡張機能)
