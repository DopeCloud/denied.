# nginx-bad-provider-block
This is more of a personal thing, i mean maybe you don't have to ban everything same as me so you have to choose, that's why every provider has a different file and not all ips in one file!.

# How to use

```bash
cd /etc/nginx/
git clone https://github.com/DopeCloud/nginx-bad-provider-block.git badProvider
```
Now add `include /etc/nginx/badProvider/badProvider.conf;` into your `nginx.conf`

