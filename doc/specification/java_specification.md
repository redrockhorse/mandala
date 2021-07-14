# java后端开发规范 
### 参考 
https://blog.csdn.net/u010520146/article/details/81085390
1. 开发环境
   * 开发环境：JDK1.8+ 
   * 开发工具：IntelliJ IDEA 2017（安装Lombok Plugin） 
   * 构建工具：Maven3.5.3 
   * 代码管理工具：Git  

2. 源码目录
   * 源码目录指：{项目目录}/src/main/
   * 打包定义目录：src/main/assembly
   * 代码目录：src/main/java
   * 资源目录：src/main/resources
   * 数据库脚本归档: src/main/resources/db
   * 内部依赖数据归档: src/main/resources/data
   * 脚本目录：src/main/bin

3. 包规范
   * 项目基本包：com.company.{项目英文名（较长时适当简化）}.{模块名（可选）}
   * config：配置类
   * startup：与服务启动相关的类
   * client：提供客户端实现的相关类
   * common：公共类，定义常量类，组件
   * entity: 数据库相关的实体类
   * model: 数据模型类(参数模型，数据传输模型等）
   * control: 控制层接口
   * service: 服务层
   * dao：数据库访问层





