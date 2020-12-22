# restricted-approval-job
CircleCIの承認ジョブに制限付きコンテキストを利用して、特定のユーザーがワークフローを完了できるようにしたサンプルです。

[CircleCI Advent Calendar 2020](https://qiita.com/advent-calendar/2020/circleci)の24日目の記事です。

[main ブランチ](https://github.com/CircleCI-Demo-Suzuki/restricted-approval-job)は記事内のサンプルに対応しています。

[multiple_approvals ブランチ](https://github.com/CircleCI-Demo-Suzuki/restricted-approval-job/tree/multiple_approvals)は記事内で詳細に触れていない多段承認のサンプルです。<br />
制限付きコンテキストと承認ジョブを重ねることで、以下のようなワークフローを組むことができます。<br />
![二段階認証のワークフロー](https://github.com/CircleCI-Demo-Suzuki/restricted-approval-job/blob/multiple_approvals/cci-advent-20201224-11.png?raw=true)

