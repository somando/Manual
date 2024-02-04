# gitのコマンドリスト】

## git init
ディレクトリを初期化。

ディレクトリでgitを使えるようにするコマンド。

## git clone [SSH key]
SSH keyのリポジトリから自分のディレクトリへコピーするコマンド。

## git add [File name or '.']
GitHubにアップするファイルを選択するコマンド。

'.'を指定することで、ディレクトリ内のすべてのファイルを追加する。

## git commit -m "[Add commit name]"
Commit nameを追加するオプション。

最初のCommitは "First commit" というCommit nameにする慣習がある。

日本語も使用できる。

## git remote add origin [SSH key]
cloneを使用せずに自分がFirst commitをする際に使用するコマンド。

## git push origin [remote branch]
GitHubにファイルをアップするコマンド。

branchを指定することでpull requestも使用できる。

branchを使用していない場合は 'main' と書けば良い。

## git pull origin [remote branch]
GitHubに上がっているファイルを自分のディレクトリにダウンロードするコマンド。

branchを指定することでbranch内のファイルをダウンロードすることもできる。

branchを使用していない場合は 'main' と書けば良い。

## git branch
GitHubにアップされている branch の情報を取得。

自分がいる branch にアスタリスクと色付きで表示。

## git checkout [menu] [branch name]
branchを切り替えるために使用するコマンド。

menuはbranch新規作成時以外不要です。

branchを新規作成するためにはmenuで'-b'を指定して、次いで新規作成するbranchの名前を入力します。
 - 例1）TestBranchというbranchを作る場合
	- git checkout -b TestBranch
 - 例2）main branchに戻る場合
    - git checkout main

## git status
gitの状態を照会するコマンド。

現在どこのbranchにいるかなどが分かる。
    