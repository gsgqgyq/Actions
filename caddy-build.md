
## 基于 GitHub Actions 编译个人所需 Caddy 文件
xcaddy build ${version} --output ./caddy_${version} \
          --with github.com/caddy-dns/cloudflare \
          --with github.com/caddy-dns/alidns \
          --with clevergo.tech/caddy-dnspodcn \
          --with github.com/caddy-dns/dnspod \
          --with github.com/lucaslorentz/caddy-docker-proxy/plugin/  \
          --with github.com/mholt/caddy-l4  \
          --with github.com/mastercactapus/caddy2-proxyprotocol \
          --with github.com/mholt/caddy-webdav  \
          --with github.com/caddyserver/forwardproxy@caddy2  \
          --with github.com/imgk/caddy-trojan  
