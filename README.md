# 3proxy-config
### 该配置主要优化了国内访问cloudfront（global）、cloudflare的速度
## 不支持列表
### Akamai：因为使用Akamai的网站都使用不同的IP，所以无法分配，但可以添加hosts指定IP
### Fastly：额，这速度优化了跟没优化一样，所以注释掉了

## 食用方法
### 请搭配[3proxy](https://github.com/3proxy/3proxy)食用，把配置文件下载或复制进3proxy.cfg即可
