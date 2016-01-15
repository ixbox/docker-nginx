FROM alpine:3.3

RUN wget http://pub.ixbox.jp/alpine/v3.3/main/x86_64/nginx-lua-1.9.9-r1.apk \
      && apk add --no-cache --allow-untrusted ./nginx-lua-1.9.9-r1.apk \
      && rm ./nginx-lua-1.9.9-r1.apk \
      && ln -sf /dev/stdout /var/log/nginx/access.log \
      && ln -sf /dev/stderr /var/log/nginx/error.log

CMD ["nginx", "-g", "daemon off;"]
