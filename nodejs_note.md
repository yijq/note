## nodejs相关学习记录




- [七天学会NodeJS](http://nqdeng.github.io/7-days-nodejs/)(偏向于基础概念，较全面)

    + nodejs基础
    + 代码的组织与部署
    + 文件操作
    + 网络操作
    + 进程管理
    + 异步编程
    + 案例：file-combine服务

    
- [nodejs包教不包会](https://github.com/alsotang/node-lessons)(偏向于实战应用，插件的运用)

    + express框架创建应用
    + superagent与cheerio完成爬虫
    + eventproxy控制并发
    + async控制并发
    + 测试：mocha（测试框架） should（断言插件） istanbul（测试覆盖率）
    + 测试：benchmark测试运行速度

- [node入门](https://www.nodebeginner.org/index-zh-cn.html)(偏向于初级的node应用)

    + 构建了一个图片上传及预览的服务
    + 基于事件驱动的回调
    + 阻塞与非阻塞
    + 路由的实现


- [利用ESLint检查代码质量](http://cnodejs.org/topic/57c68052b4a3bca66bbddbdd)
    + ESLint配置文件：.eslintrc.js:
    ```javascript
    module.eports = {
        extenfs: "eslint:recommended",
        env: {
          node: true,
        },
        rules: {
          'no-console': 'off',
          'indent': [ 'error', 2 ],
          'quotes': [ 'error', 'single' ],
        }
    }
    ```
    + 配置文件的内容可以添加到package.json中
    + 检查代码
    ```
    $ eslint <filepath>
    ```
    + [ESLint官方文档](http://eslint.cn/docs/rules/)

- [nodejs官方文档](http://nodejs.cn/)

