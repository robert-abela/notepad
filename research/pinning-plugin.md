# Cert Pinning Browser Plugin

## BGP Routing attacks
BGP routing attacks seem to pop up over and over again over the years. A recent one from 2022 is below:
```
Earlier this month on February 3rd, a Thursday, customers of a South Korean cryptocurrency
platform known as KLAYswap, lost a total of 2.2 billion Korean won, which is equivalent to
around $1.9 million US dollars as a result of 407 fraudulent, intercepted and altered
cryptocurrency transactions across a total of 325 KLAYswap customer wallets.
``` 
Read more:
- https://www.grc.com/sn/SN-859-Notes.pdf
- https://www.bankinfosecurity.com/crypto-exchange-klayswap-loses-19m-after-bgp-hijack-a-18518

## Cert Pinning
If a mobile app uses certificate pinning, and DNS takes you elsewhere with a new cert, the app will notice:
- https://owasp.org/www-community/controls/Certificate_and_Public_Key_Pinning
- https://en.wikipedia.org/wiki/HTTP_Public_Key_Pinning
- https://developer.android.com/training/articles/security-ssl#Pinning
- https://approov.io/blog/securing-https-with-certificate-pinning-on-android


## A broswer plugin
But with desktop browsers it won't happen. A browser plugin which pins the certs to your sensitive sites (eg banking) and complains when it changes could be a solution: - https://developer.mozilla.org/en-US/docs/Web/HTTP/Public_Key_Pinning
- https://addons.mozilla.org/en-US/firefox/addon/certificate-pinner/
- https://blog.wirelessmoves.com/2019/07/certificate-pinning-is-back-in-firefox.html

