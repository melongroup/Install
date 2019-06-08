# Melon指令集  windows only

```javaScript
    //安装CNPM (如已安装 可跳过)
    npm install -g cnpm --registry=https://registry.npm.taobao.org
    //安装TypeScript (如已安装 可跳过)
    cnpm install typescript -g
    //安装 其他内容
    cnpm i
    //编译
    tsc
    //安装melon编译器
    .\publish.dat
```

```javaScript
    console.log(`current version:${new File(process.env.APPDATA + "\\npm\\node_modules\\melon\\version.txt").readUTF8().trim()}`)
    console.log(`   melon          --编译生成html文件`)
    console.log(`   melon setup    --更新melon编译库`)
    console.log(`   melon update   --更新stage3d wechat 等lib库`)
    console.log(`   melon create   --创建web nodejs项目`)
    console.log(`   melon release  --发布release版本`)
    console.log(`   melon publish  --发布release版本到内网测试服务器`)
```

```javaScript

    压缩版发布
    melon release -mini

    微信小程序发布
    melon release -wechat
```