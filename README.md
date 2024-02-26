## [Sventalk.xyz](https://sventalk.xyz)

The home of all the code which builds my simple blogging website. It is powered by [Hugo](gohugo.io) - a simple, lean, fast architecture for making really simple (generally static) websites.

The deployment is even simpler utilizing GH Pages and then routing to a domain name I own.

Content I wish to write is simply begun using

```bash
hugo new content posts/some-nice-name-here.md
```

and you can start the website and serve is locally via

```bash
# the D option serves up drafts as well
hugo serve -D
```
