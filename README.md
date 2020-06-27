# DQ: Dom Querier For the CLI

Only an idea right now inspired by [yq](https://github.com/mikefarah/yq) and [jq](https://github.com/stedolan/jq). 
Not even under development. If you're interested, give me a shout.

## The idea 💡

Get the image tag element html from Google

```bash
dq http://google.com 'img[alt="Google"]'
```

Get the html from a local fille

```bash
dq index.html
```

Get each h2 title from a page

```bash
cat some.html | dq 'h2[*]'
```
