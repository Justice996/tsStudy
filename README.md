# tsStudy
typeScript Study note

# 特点
 
 * 类型检查
 * 语言扩展
 * 工具属性

# 静态类型语言和动态类型语言的区别

 1. 静态类型语言 <br>
    在编译阶段确定所有变量的类型
      + 编译阶段确定属性的偏移量
      + 用偏移量访问代替属性名访问
      + 偏移量信息共享
    
 2. 动态类型语言
    在执行阶段确定所有变量的类型
     + 在程序运行时，动态计算属性偏移量
     + 需要额外的空间存储属性名
     + 所有对象的偏移量信息各存一份
# 安装
  
  需要准备nodejs环境并安装vscode

  1. 初始化项目   ```` npm init -y````
  2. 安装ts     ````npm i typescript -g ````   
  3. 创建配置项  ````tsc --init ````
     编译文件 ````tsc ./src/index.ts ````
  4. 构建环境  ```` npm i webpack webpack-cli webpack-dev-server -D````