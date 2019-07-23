---
title: github.io blog 생성 테스트!
published: true
---

# github.io Blog 생성 테스트
> 블로그 생성이 잘되나 볼까?   
   
`$ jekyll server`   
   
```bash
#!/bin/bash

docker run --rm -p 8000:8000 \
  --volume="LOCATION_OF_YOUR_JEKYLL_BLOG:/srv/jekyll" \
  -it tocttou/jekyll:3.5 \
  jekyll serve --watch --port 8000
```

## 끝
* * * 
