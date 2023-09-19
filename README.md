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
git clone git@github.com:floatingcloud1983/floatingcloud1983.github.io.git -b master public

```

```
git add xxx

hugo

./auto_publish "commit message"
```

### Emoji

https://hugoloveit.com/zh-cn/emoji-support/
