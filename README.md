# blog
blog

https://qiita.com/dongsu-iis/items/8662472e98e7fe598849#github-pages%E3%81%AB%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89

https://hexo.io/docs/front-matter


npx hexo clean
npx hexo generate


:\git\blog>npx hexo server


npx hexo new post


npx hexo deploy -g


 Gitからデプロイ
GitHubにデプロイするためのNodeモジュールをインストールします。

npm install hexo-deployer-git --save
以下のコマンドを実行すると、Github Pagesにアップロードできます。

hexo deploy -g
このコマンドでもOKです。


hexo generate -d




Create a new post
1
$ hexo new "My New Post"
More info: Writing

Run server
1
$ hexo server
More info: Server

Generate static files
1
$ hexo generate
More info: Generating

Deploy to remote sites
1
$ hexo deploy


npm install プラグイン名 --save


npx hexo config deploy.repository git@github.com:e99h2121/blog.git
