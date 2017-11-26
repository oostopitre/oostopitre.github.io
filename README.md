## oostopitre.github.io

This is the repo which hosts the anchor for oostopitre.github.io

Links:
- Website: https://oostopitre.github.io
- Host: http://github.com/oostopitre
- Anchor: http://github.com/oostopitre/oostopitre.github.io
- Contents: http://github.com/oostopitre/gitblog
- Connect Anchor and Contents: https://gohugo.io/hosting-and-deployment/hosting-on-github/


## useful commands

Setup and first blog:
```bash
 brew install hugo
 hugo version
 which hugo

 hugo new site gitblog
 git clone https://github.com/nishanths/cocoa-hugo-theme.git themes/cocoa
 cp -r themes/cocoa/exampleSite/* ./

 hugo new blog/first_post.md
 hugo new blog/second_post.md

 hugo server
 hugo server -D

 ./deploy.sh 'commit message'
```


New blog:
```bash
 cd gitblog
 hugo new blog/second_post.md
 ./deploy.sh
```



