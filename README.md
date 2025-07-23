# markdown-pdf Template

Visual Studio Code의 [markdown-pdf](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)
extension을 위한 template입니다.

## Tips

생각나는 대로 추가 예정

### 사진 크기 조절

```html
<img src="./image.png" width="500" height="300"/>
```

### 수식 추가

.md 파일 맨 끝에 아래 html 추가

```html
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
  <script type="text/x-mathjax-config">
    MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>
```
