# Blog

This blog is written with Hexo

Please refer to the documentation here: https://hexo.io/docs


You can also use a docker container to auto-build and changes or new files added and put them in the ```public``` directory.

```bash
docker run --rm -it --name hexo -v `pwd`:/blog hourd/hexo hexo generate --watch
```

To make a new post just create a markdown file in ```sources/_posts```
