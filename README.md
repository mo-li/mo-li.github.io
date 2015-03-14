[TOC]

####Setting

    {
        tex  : true
    }

####Examples
            
$$E=mc^2$$

Inline 行内的公式$$E=mc^2$$行内的公式，行内的$$E=mc^2$$公式。

$$c = \\pm\\sqrt{a^2 + b^2}$$

$$f(x) = x^2$$

$$\alpha = \sqrt{1-e^2}$$

$$\(\sqrt{3x-1}+(1+x)^2\)$$
             
$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

$$\\dfrac{-b \\pm \\sqrt{b^2 - 4ac}}{2a}$$

$$f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi$$

$$\displaystyle \frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}} {1+\frac{e^{-8\pi}} {1+\cdots} } } }$$

$$\displaystyle \left( \sum\_{k=1}^n a\_k b\_k \right)^2 \leq \left( \sum\_{k=1}^n a\_k^2 \right) \left( \sum\_{k=1}^n b\_k^2 \right)$$

####Custom KaTeX source URL

```javascript
// Default using CloudFlare KaTeX's CDN
// You can custom url
editormd.katexURL = {
    js  : "your url",
    css : "your url"
};
```

#### KaTeX vs MathJax

[https://jsperf.com/katex-vs-mathjax](https://jsperf.com/katex-vs-mathjax "KaTeX vs MathJax")
