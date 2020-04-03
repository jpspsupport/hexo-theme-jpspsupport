# hexo-theme-jpazure

hexo theme for jpspsupport tech blog

> forked from [hexo-theme-landscape](https://github.com/hexojs/hexo-theme-landscape)

## Set Up

```sh
git clone https://github.com/jpspsupport/hexo-theme-jpspsupport.git themes/jpspsupport
npm i -D hexo-generator-feed
npm i -D jpspsupport/hexo-helper-github-issues hexo-generator-root-tag
```

## hexo config.yml


```yml
root_tag_generator:
  root_tag_names:
    - SharePoint Online
    - Onedrive for Business
  sub_tag_limit: 20
  
github:
  url: https://github.com/jpspsupport/blog/
  posts_dir: articles

```
