# cloudflare-proxy-docker

## 简介

近期国内很多的docker镜像站都被下架了，还有少数镜像站能用，但是大部分都已经变成了**仅供内部使用**，例如：腾讯云、中科大

要么就是镜像同步不及时，例如：阿里云

为解决这个问题，可以通过反向代理docker官方源的方法实现国内的正常访问，有海外VPS的小伙伴可以在VPS上用nginx进行反代，没有的小伙伴可以通过cloudflare的worker和pages实现反代

**不过，使用CF反代需要准备好自己的域名，因为CF的域名在国内无法征程访问**
 
## 教程

https://linux.do/t/topic/107726

https://global.v2ex.com/t/1007922
