运行
```
λ parcel src/index.html
```

打包
```

相对路径
命令：
parcel build src/index.html --no-minify --public-url ./
dist/index.html文件：
src="main.5b385a8d.js"

绝对路径
命令：
parcel build src/index.html --no-minify --public-url https://ioudan.com/nav/dist/

dist/index.html文件：
src="https://ioudan.com/nav/dist/main.5b385a8d.js"
```