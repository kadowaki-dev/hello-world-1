# hello-world
test

a bit changed.

#### 空ブランチに画像をおいて、README.mdから参照させる
* ローカル
  * git checkout -orphan <画像用branch名>
    * "orphan"は孤児という意味で、切る前のブランチ情報を引き継がない。
  * 画像用branch上で画像を追加
  * git push --set-upstream origin <画像用branch名>
  * git push origin <画像用branch名>
  * ローカルでTrackしているブランチを確認  git branch -vv
  * Github Insightsタブの[Network]からブランチが独立していることを確認。
* 元のブランチのREADME.md(ここ)で画像を参照
  * ![ためし](https://github.com/otyazukeGit/hello-world/blob/images_branch/image/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202020-02-05%2017.26.58.png)
