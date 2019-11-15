# hugo-theme-pure

This is a port of [this theme](https://github.com/xiaoheiAh/hugo-theme-pure), which is a port of another port.
Turtles all the  way down.

## Screenshots

![](https://raw.githubusercontent.com/sergiocarlosmorales/hugo-theme-pure/master/images/grey.png)

![](https://raw.githubusercontent.com/sergiocarlosmorales/hugo-theme-pure/master/images/black.png)

![](https://raw.githubusercontent.com/sergiocarlosmorales/hugo-theme-pure/master/images/blue.png)

![](https://raw.githubusercontent.com/sergiocarlosmorales/hugo-theme-pure/master/images/green.png)

![](https://raw.githubusercontent.com/sergiocarlosmorales/hugo-theme-pure/master/images/purple.png)


### **Note** 

1. Please copy the config.yml under the `exampleSite` folder to the root folder of your Hugo Site. Feel free to change it.

2. Your post should under the `posts` folder, like this : `hugo new posts/any.md`

## Multilingual

Translations are collected from the [`/i18n/`](https://github.com/sergiocarlosmorales/hugo-theme-pure/tree/master/i18n) folder (built into the theme), as well as present in `i18n` at your root of project.

You can specify `defaultContentLanguage` to use translations.

```yml
defaultContentLanguage: en # en,fr,es...
```

## Favicon & Images

You should put you images into `static` folder at your root project. When specify `favicon` or `donate qr code` , don't use absolute url like `/favicon.ico`, please use relative url like `favicon.ico` or `donate/alipay.png`

## Menu Icons

You can configure the menu according to the icons of [Iconfont](http://blog.cofess.com/hexo-theme-pure/iconfont/demo_fontclass.html), the following is configuration.

```yml
menuIcons:
  enable: true  
  home: icon-home-fill
  archives: icon-archives-fill
  categories: icon-folder
  tags: icon-tags
  repository: icon-project
  books: icon-book-fill
  links: icon-friendship
  about: icon-cup-fill
```

## TOC

enable toc 

```yml
  # config
  config:
    toc: true
```


## License

Released under the [MIT](https://github.com/sergiocarlosmorales/hugo-theme-pure/blob/master/LICENSE) License.

## Acknowledgements
- [hugo-theme-pure](https://github.com/xiaoheiAh/hugo-theme-pure)

- [hexo-theme-pure](https://github.com/cofess/hexo-theme-pure)

- [hugo-theme-even](https://github.com/olOwOlo/hugo-theme-even)

  

