# php.js
#### 采用 locutus 生成浏览器可引入 php.js

#### 生成方式

采用 browserify 对 locutus 进行生成浏览器端可执行 php.js 文件

引入 [locutus](https://github.com/kvz/locutus)

```
npm install locutus
```

引入全局 [browserify](http://browserify.org)

```
npm install -g browserify
```

修改 construct.js 文件

```
browserify  construct.js -o php.js
```

#### 注意事项

   var,array 类属于保留关键字，可根据自身需要重新编译新引入名 
