https://github.com/kat0h/hugo-blog-template
https://zenn.dev/kato_k/articles/66531db0c4024d
https://www.membersedge.co.jp/blog/create-hugo-theme-and-deploy-to-github-pages/

https://naokomada.github.io/blog/


server
https://hub.docker.com/r/klakegg/hugo
docker run --rm -it -v $(pwd):/src klakegg/hugo:0.101.0
docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:0.101.0 server