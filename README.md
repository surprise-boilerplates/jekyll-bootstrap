# jekyll-bootstrap
A Jekyll Bootstrap

## Docker Testing

You can spin up a standard Jekyll container and serve directly from Jekyll, using watch and incremental.

```
docker run -d --name ntt -v C:\path\to\project:/srv/jekyll -p 4000:4000 --entrypoint "jekyll serve --watch --incremental" jekyll/jekyll
```
