### Notes
This page is based on [hugo jane theme](https://github.com/xianmin/hugo-theme-jane).

### Build
* run `hugo server -D` for localhost test.
* run `./auto_publish.sh` to generate and deploy pages.

### Config Jane
Remove `by` from `themes/jane/layouts/partials/post/meta.html`

### deploy
setup public files
```
git clone git@github-hugo:anglebrianna/hugo.git

git submodule init
git submodule update

cd hugo.hugo

git clone git@github-hugo:anglebrianna/anglebrianna.github.io.git public

```

```
git add xxx

hugo

./auto_publish "commit message"
```

### Emoji

https://hugoloveit.com/zh-cn/emoji-support/
