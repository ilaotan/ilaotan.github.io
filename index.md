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
  }
 做的高级点就判断下build参数, 有build参数时,跳转到xml文件  /jetbrains/plugin/?build=IU-213.7172.25
 
```

子项目可以考虑使用docsify-cli 做docs  比如https://alibaba.github.io/kt-connect/#/
