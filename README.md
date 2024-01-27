# midjourney-proxy-with-image-content

When I using [midjourney-proxy](https://github.com/novicezk/midjourney-proxy), I noticed that the returned url is started with `cdn.discordapp.com`, which is not available from some of my users.

So I configure another reverse proxy to proxy the image content from `cdn.discordapp.com` to my own domain.
