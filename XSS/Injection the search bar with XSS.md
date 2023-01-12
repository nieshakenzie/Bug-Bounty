## Introduction

This blog post covers a Cross-Site Scripting bug that i found on Sumselprov.go.id

This bug could have allowed hackers to Open Redirection, Website Defacement and Malware

## PoC

<img src="https://user-images.githubusercontent.com/67650329/211984395-59ac2452-cb68-49a2-9e1f-afe2d7ee4569.jpg" width="500px" align="center">

## How I Found The Bug

1. I use subfinder to search the subdomain of the website.
2. Check one by one the subdomain patiently.
3. And i got the one of subdomain to exploit with XSS on the search bar.
4. I use this script to exploit and worked for me.
```
"><script>alert(document.domain)</script>
```

👋 Thank You
