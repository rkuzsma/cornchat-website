# CornChat Website

The CornChat public website was originally cloned from the [Hexo Doc Theme Seed Project](https://zalando-incubator.github.io/hexo-theme-doc/index.html)

To run the site locally:

```
npm install -g hexo-cli
cd <THIS DIRECTORY>
npm install
hexo s
```

Browse to http://localhost:4000

To build and deploy to GitHub pages at [https://rkuzsma.github.io/cornchat-website/](https://rkuzsma.github.io/cornchat-website/) run:
```
hexo generate -d
```

The CSS and image paths will appear broken on the github pages site, but they work on [www.cornchat.online](https://www.cornchat.online/).

A CNAME file is configured for [https://www.cornchat.online/](https://www.cornchat.online/)

## License

MIT License. See [LICENSE](LICENSE) and [LICENSE-hexo-theme-doc-seed](LICENSE-hexo-theme-doc-seed).
