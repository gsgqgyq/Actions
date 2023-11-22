
## 基于 GitHub Actions 编译个人所需 Caddy 文件
xcaddy build ${version} --output ./caddy_${version} \
          --with github.com/mholt/caddy-l4 \
          --with github.com/caddy-dns/cloudflare \
          --with clevergo.tech/caddy-dnspodcn \
          --with github.com/caddy-dns/duckdns \
          --with github.com/mholt/caddy-dynamicdns \
          --with github.com/mholt/caddy-events-exec \
          --with github.com/WeidiDeng/caddy-cloudflare-ip \
          --with github.com/caddyserver/forwardproxy@caddy2 \
          --with github.com/imgk/caddy-trojan \
          --with github.com/mholt/caddy-webdav \
