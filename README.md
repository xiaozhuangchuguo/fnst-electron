# fnst-electron
research and some demos about electron

# 热更新功能试验
**2017.07.07**  

**热更新流程说明**
1. 使用github作为服务器来存放文件
   - package.json一定要
   - html、css等文件
2. 应用启动时检查*package.json*中的*version*号
3. 下载github上的更新资源
4. 替换对应的本地文件
5. 刷新页面就行

***package.json*中需要的内容**
- *version*
- *name*
- *productName*
- *manifest*数组
  - *version*
  - *file*数组
  - *detail*数组
- *description*
- *main*
- *script*
- *repository*
- *keywords* 
- *author*
- *devDependencies*
- *license*

*参考了bobo-electron中关于热更新的相关代码  
*项目地址：https://github.com/yued-fe/bobo-electron 欢迎大家fork
