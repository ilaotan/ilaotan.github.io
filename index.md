# 主页

无东西哦 建议关了.

```
自用插件地址
http://ilaotan.github.io/updatePlugins.xml
```

```
 nginx
 
  location /jetbrains/plugin {
    alias /usr/local/jetbrain_plugins;
    index welcome.html;
    if ($query_string ~* "build=") {rewrite ^/(.*)  http://$host/jetbrains/plugin/updatePlugins.xml? permanent;
      }
  }
 
```

子项目可以考虑使用docsify-cli 做docs  比如https://alibaba.github.io/kt-connect/#/
