# 创建Vue程序

## 使用VUE-CLI创建项目

```shell
vue create real-word-v1 # 工程名
```

可以通过选项自动配置工程和依赖，下面只是一种选择：

1. 选择通过手工选择特性

   ![image-20220123222043796](https://gitee.com/siyingcheng/pic-bed/raw/main/images/robot_20220123222044.png)

2. 选择基础模块，这里再默认的选线外勾选上Router和Vuex

   ![image-20220123222152956](https://gitee.com/siyingcheng/pic-bed/raw/main/images/robot_20220123222153.png)

3. 选择vue版本，我们这里选择3.x

   ![image-20220123222253336](https://gitee.com/siyingcheng/pic-bed/raw/main/images/robot_20220123222253.png)

4. 配置history mode for router以及选择linter / formatter

   ![image-20220123222745034](https://gitee.com/siyingcheng/pic-bed/raw/main/images/robot_20220123222745.png)

   然后回车(默认选择`Lint on save`)，然后再回车(默认选择`In dedicated config files`)

等待CLI自动解决依赖以及自动配置，直到提示成功：

![image-20220123225233743](https://gitee.com/siyingcheng/pic-bed/raw/main/images/robot_20220123225234.png)

然后我们根据提示进入工程目录，执行`npm run serve`启动程序：

```shell
cd real-word-v1
npm run serve
```

![image-20220123225428538](https://gitee.com/siyingcheng/pic-bed/raw/main/images/robot_20220123225429.png)

现在我们在浏览器中访问即可。



## 使用VUE-UI创建项目

还可以通过VUE-UI创建项目，我们只需要在命令行输入`vue ui`即可。vue-ui会立即启动一个http程序，并打开浏览器访问该程序。我们可以在浏览器中创建项目、配置项目、安装插件、启动项目以及资源监控。

![image-20220123230301392](https://gitee.com/siyingcheng/pic-bed/raw/main/images/robot_20220123230302.png)

