+++
title = "AppSync ResolverでDynamo DBの条件付きアップデートをする"
date = "2021-04-27"
tags = ["AppSync"]
+++

フィールドにオートインクリメントされるバージョン番号を持たせて、アップデートする際は現在のバージョン番号が、リクエストに含まれるバージョン番号と一致する場合のみ更新を受け付けるという仕組み。

[Githubのリポジトリ](https://github.com/suzukiken/cdkappsync-dynamo-conditional-update)


