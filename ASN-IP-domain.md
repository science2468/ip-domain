uclient-fetch --no-check-certificate -qO- "https://ipinfo.io/AS59930" 2>/dev/null | grep -E "a href.*59930\/" | grep -v ":" | sed 's/^.*<a href="\/AS'"59930"'\///; s/".*//'




### Google
```
AS396982
AS15169
常用的Google产品都在里面
142.250.0.0/15
2607:f8b0::/32
googlevideo用于YouTube内
173.194.0.0/16 
74.125.0.0/16
Gemini API
142.250.0.0/15
172.217.0.0/16
216.239.32.0/19
```
### telegram
```
常用
149.154.160.0/21 telegram wgb + 149.154.168.0/21 #telegram client = 149.154.160.0/20 
91.108.56.0/22
不常用

ipv6:
2001:b28:f23f::/48 + 2001:b28:f23d::/48 + 2001:b28:f23c::/48 = 2001:b28:f23c::/46

2001:b28:f23c::/46
2a0a:f280:203::/48
2001:67c:4e8::/48
```
### chatgpt
```
auth0.openai.com
auth.openai.com
chat.openai.com
api.openai.com
```
### github.com
```
140.82.112.0/20

143.55.64.0/20
192.30.252.0/22
185.199.108.0/22
```
### proton
```
185.70.40.0/22

185.159.159.0/24
2a05:2700::/29
```
