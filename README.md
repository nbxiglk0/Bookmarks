- [Bookmarks](#bookmarks)
  - [WebSites](#websites)
    - [WAF](#waf)
      - [waf-bypass-techniques-using-http-standard-and-web-servers-behaviour](#waf-bypass-techniques-using-http-standard-and-web-servers-behaviour)
      - [Bug Writeup: RCE via SSTI on Spring Boot Error Page with Akamai WAF Bypass](#bug-writeup-rce-via-ssti-on-spring-boot-error-page-with-akamai-waf-bypass)
    - [OAuth](#oauth)
      - [hidden-oauth-attack-vectors](#hidden-oauth-attack-vectors)
    - [Cache Attack](#cache-attack)
      - [Caching the Un-cacheables - Abusing URL Parser Confusions (Web Cache Poisoning Technique)](#caching-the-un-cacheables---abusing-url-parser-confusions-web-cache-poisoning-technique)
    - [JAVA](#java)
      - [design-patterns-java](#design-patterns-java)
      - [Java即时编译器原理解析及实践](#java即时编译器原理解析及实践)
      - [Java线程池实现原理](#java线程池实现原理)
      - [Java 动态调试技术原理及实践](#java-动态调试技术原理及实践)
      - [字节码增强技术探索](#字节码增强技术探索)
      - [Java动态追踪技术探究](#java动态追踪技术探究)
      - [Java魔法类：Unsafe应用解析](#java魔法类unsafe应用解析)
      - [MyBatis缓存机制](#mybatis缓存机制)
      - [Bypassing OGNL sandboxes for fun and charities](#bypassing-ognl-sandboxes-for-fun-and-charities)
    - [XXE](#xxe)
      - [exploiting-xxe-with-local-dtd-files](#exploiting-xxe-with-local-dtd-files)
    - [XSS](#xss)
      - [如何防止XSS攻击？](#如何防止xss攻击)
    - [ESI Injection](#esi-injection)
      - [Beyond XSS: Edge Side Include Injection](#beyond-xss-edge-side-include-injection)
      - [esi-injection-part-2-abusing-specific-implementations](#esi-injection-part-2-abusing-specific-implementations)
      - [Exploring the World of ESI Injection](#exploring-the-world-of-esi-injection)
    - [PHP](#php)
      - [PHP FILTERS CHAIN: WHAT IS IT AND HOW TO USE IT](#php-filters-chain-what-is-it-and-how-to-use-it)
    - [DNS](#dns)
      - [Melting the DNS Iceberg: Taking over your infrastructuredds Kaminsky style](#melting-the-dns-iceberg-taking-over-your-infrastructuredds-kaminsky-style)
      - [guide-to-dns-takeovers](#guide-to-dns-takeovers)
    - [BugBounty](#bugbounty)
      - [$6000 with Microsoft Hall of Fame | Microsoft Firewall Bypass | CRLF to XSS | Microsoft Bug Bounty](#6000-with-microsoft-hall-of-fame--microsoft-firewall-bypass--crlf-to-xss--microsoft-bug-bounty)
  - [PDF](#pdf)
      - [对基于Git的版本控制服务的通用攻击面的探索](#对基于git的版本控制服务的通用攻击面的探索)
      - [自动化API漏洞Fuzz实战【KCon2022】](#自动化api漏洞fuzz实战kcon2022)
      - [Hacking JSON](#hacking-json)
      - [Magic in RASP-attack and defense【KCon2022】](#magic-in-rasp-attack-and-defensekcon2022)
      - [tabby java code review like a pro【KCon2022】](#tabby-java-code-review-like-a-prokcon2022)
      - [A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages](#a-new-era-of-ssrf-exploiting-url-parser-in-trending-programming-languages)
      - [us-17-Munoz-Friday-The-13th-JSON-Attacks-wp](#us-17-munoz-friday-the-13th-json-attacks-wp)
      - [us-17-Gil-Web-Cache-Deception-Attack-wp](#us-17-gil-web-cache-deception-attack-wp)
      - [Bug Bounty on Steroids](#bug-bounty-on-steroids)
      - [What is SSRF and how to Detect them on Web Application](#what-is-ssrf-and-how-to-detect-them-on-web-application)
# Bookmarks
一些随手存的文章和pdf
## WebSites
### WAF
#### waf-bypass-techniques-using-http-standard-and-web-servers-behaviour

* [waf-bypass-techniques-using-http-standard-and-web-servers-behaviour](https://www.slideshare.net/SoroushDalili/waf-bypass-techniques-using-http-standard-and-web-servers-behaviour)  
#### Bug Writeup: RCE via SSTI on Spring Boot Error Page with Akamai WAF Bypass
* [Bug Writeup: RCE via SSTI on Spring Boot Error Page with Akamai WAF Bypass](https://h1pmnh.github.io/post/writeup_spring_el_waf_bypass/)
### OAuth
#### hidden-oauth-attack-vectors
* [hidden-oauth-attack-vectors](https://portswigger.net/research/hidden-oauth-attack-vectors)
### Cache Attack
#### Caching the Un-cacheables - Abusing URL Parser Confusions (Web Cache Poisoning Technique)
* [Caching the Un-cacheables - Abusing URL Parser Confusions (Web Cache Poisoning Technique)](https://nokline.github.io/bugbounty/2022/09/02/Glassdoor-Cache-Poisoning.html)
### JAVA
#### design-patterns-java
* [design-patterns-java](https://www.decipherzone.com/blog-detail/design-patterns-java?continueFlag=1f350539170b2ba2f112b6ed2113990e)
#### Java即时编译器原理解析及实践
* [Java即时编译器原理解析及实践](https://tech.meituan.com/2020/10/22/java-jit-practice-in-meituan.html)
#### Java线程池实现原理
* [Java线程池实现原理](https://tech.meituan.com/2020/04/02/java-pooling-pratice-in-meituan.html)
#### Java 动态调试技术原理及实践
* [Java 动态调试技术原理及实践](https://tech.meituan.com/2019/11/07/java-dynamic-debugging-technology.html)
#### 字节码增强技术探索
* [字节码增强技术探索](https://tech.meituan.com/2019/09/05/java-bytecode-enhancement.html)
#### Java动态追踪技术探究
* [Java动态追踪技术探究](https://tech.meituan.com/2019/02/28/java-dynamic-trace.html)
#### Java魔法类：Unsafe应用解析
* [Java魔法类：Unsafe应用解析](https://tech.meituan.com/2019/02/14/talk-about-java-magic-class-unsafe.html)
#### MyBatis缓存机制
* [MyBatis缓存机制](https://tech.meituan.com/2018/01/19/mybatis-cache.html)
#### Bypassing OGNL sandboxes for fun and charities
* [Bypassing OGNL sandboxes for fun and charities](https://github.blog/2023-01-27-bypassing-ognl-sandboxes-for-fun-and-charities/)
### XXE
#### exploiting-xxe-with-local-dtd-files
* [exploiting-xxe-with-local-dtd-files](https://mohemiv.com/all/exploiting-xxe-with-local-dtd-files/)
### XSS
#### 如何防止XSS攻击？
* [如何防止XSS攻击？](https://tech.meituan.com/2018/09/27/fe-security.html)
### ESI Injection
#### Beyond XSS: Edge Side Include Injection
* [Beyond XSS: Edge Side Include Injection](https://www.gosecure.net/blog/2018/04/03/beyond-xss-edge-side-include-injection/)
#### esi-injection-part-2-abusing-specific-implementations
* [esi-injection-part-2-abusing-specific-implementations](https://www.gosecure.net/blog/2019/05/02/esi-injection-part-2-abusing-specific-implementations/)
#### Exploring the World of ESI Injection
* [Exploring the World of ESI Injection](https://infosecwriteups.com/exploring-the-world-of-esi-injection-b86234e66f91?source=social.tw)
### PHP
#### PHP FILTERS CHAIN: WHAT IS IT AND HOW TO USE IT
* [PHP FILTERS CHAIN: WHAT IS IT AND HOW TO USE IT](https://www.synacktiv.com/publications/php-filters-chain-what-is-it-and-how-to-use-it.html#)  
* [persistent-php-payloads-in-pngs-how-to-inject-php-code-in-an-image-and-keep-it-there.html](https://www.synacktiv.com/publications/persistent-php-payloads-in-pngs-how-to-inject-php-code-in-an-image-and-keep-it-there.html)
### DNS
#### Melting the DNS Iceberg: Taking over your infrastructuredds Kaminsky style
* [Melting the DNS Iceberg: Taking over your infrastructuredds Kaminsky style](https://sec-consult.com/blog/detail/melting-the-dns-iceberg-taking-over-your-infrastructure-kaminsky-style/)
#### guide-to-dns-takeovers
* [guide-to-dns-takeovers](https://blog.projectdiscovery.io/guide-to-dns-takeovers/)

### BugBounty
#### $6000 with Microsoft Hall of Fame | Microsoft Firewall Bypass | CRLF to XSS | Microsoft Bug Bounty
* [$6000 with Microsoft Hall of Fame | Microsoft Firewall Bypass | CRLF to XSS | Microsoft Bug Bounty](https://infosecwriteups.com/6000-with-microsoft-hall-of-fame-microsoft-firewall-bypass-crlf-to-xss-microsoft-bug-bounty-8f6615c47922)
## PDF
#### 对基于Git的版本控制服务的通用攻击面的探索
* [对基于Git的版本控制服务的通用攻击面的探索](/对基于Git的版本控制服务的通用攻击面的探索.pdf)
#### 自动化API漏洞Fuzz实战【KCon2022】
* [自动化API漏洞Fuzz实战【KCon2022】](/自动化API漏洞Fuzz实战【KCon2022】.pdf)
#### Hacking JSON
* [Hacking JSON](/Bookmarks/Hacking%20JSON【KCon2022】.pdf)
#### Magic in RASP-attack and defense【KCon2022】
* [Magic in RASP-attack and defense【KCon2022】](/Magic%20in%20RASP-attack%20and%20defense【KCon2022】%20.pdf)
#### tabby java code review like a pro【KCon2022】
* [tabby java code review like a pro【KCon2022】](/tabby%20java%20code%20review%20like%20a%20pro【KCon2022】.pdf)
#### A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages
* [A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages](/us-17-Tsai-A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages.pdf)
#### us-17-Munoz-Friday-The-13th-JSON-Attacks-wp
* [us-17-Munoz-Friday-The-13th-JSON-Attacks-wp](/us-17-Munoz-Friday-The-13th-JSON-Attacks-wp.pdf)
#### us-17-Gil-Web-Cache-Deception-Attack-wp
* [us-17-Gil-Web-Cache-Deception-Attack-wp](/us-17-Gil-Web-Cache-Deception-Attack-wp.pdf)
#### Bug Bounty on Steroids
* [Bug Bounty on Steroids](/Bug%20Bounty%20on%20Steroids.pdf)
#### What is SSRF and how to Detect them on Web Application
* [What is SSRF and how to Detect them on Web Application](/What%20is%20SSRF%20and%20how%20to%20Detect%20them%20on%20Web%20Application.pdf)