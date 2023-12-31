# gitとは、分散管理型のバージョン管理システムであり、オープンソフトウェア開発に用いられる。
変更履歴が残るなど、他人と編集することができるのが特徴である。
gitが管理するプロジェクトのフォルダのことをレポジトリと呼び、個々の作業環境をローカル、元の共通のレポジトリをリモートと呼び、ローカルレポジトリで加えられた変更をコミットし、リモートレポジトリに反映する。
コミットとは、新たなファイルを作成することやファイルに対する変更、削除の記録を指し、誰がいつどのような変更を加えたかを記録することができる。

# gitコマンドの例として、次のようなものがある。  return
git init gitを初期化し、設定を開始する。  
git status ワークツリーのステータスを表示する。  
git config gitに関する設定の確認、変更を行える。  
git log コマンドのログを表示する。  
git diff ファイルの差分を表示する。  
git add ステージングエリアにローカルレポジトリを加える。  
git commit コミットの実行  

# gitフローとは、gitフローが派生したものである。
メインブランチがデフォルトで設定され、このメインブランチは常に本番環境へ実装可能である。開発を行うときは、詳細なブランチを作成し作業する。作業内容はコミットし、定期的にプッシュすることで反映させる。サポートやコメントを求めるときにプルリクエストを送ることができ、コメントすることができる。プルリクエストに対し、他のメンバーが内容を確認することでメインブランチにマージすることができる。このように、メインブランチを軸に別のブランチで作業して反映させることで、開発をシンプルにしている。
