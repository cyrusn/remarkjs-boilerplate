# RemarkJS

## Presentation

Serve this folder with [any HTTP server](https://gist.github.com/willurd/5720255), examples:

```sh
caddy -port 8000
ecstatic -p 8000
python3 -m http.server 8000
docker run --rm -p 8000:80 -v "$PWD":/usr/share/nginx/html:ro nginx:alpine
```

[Presentation mode · gnab/remark Wiki](https://github.com/gnab/remark/wiki/Presentation-mode)
`C`: clone presentation
`P`: enter presentation mode

## Dev

```sh
npm i -g live-server
live-server
```

Modification of files in this folder will trigger browser to live reload.


## Update dependencies

## Remark
```sh
# current version v0.14.0
# [Home · gnab/remark Wiki · GitHub](https://github.com/gnab/remark/wiki#getting-started)
wget https://remarkjs.com/downloads/remark-latest.min.js -O static/js/remark-latest.min.js 
```

## Bootstrap

```sh
# current version v4.1.1
# update from [Quick Start · BootstrapCDN by StackPath](https://www.bootstrapcdn.com/)
wget https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css -O static/css/bootstrap.min.css 

```

## Font Awesome

```sh
# current version v5.1.0
# [Getting Started | Font Awesome](https://fontawesome.com/how-to-use/on-the-web/setup/getting-started?using=svg-with-js)
wget https://use.fontawesome.com/releases/v5.1.0/js/all.js -O static/js/fontawesome-all.min.js 
```
