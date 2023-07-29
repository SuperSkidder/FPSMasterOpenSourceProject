# FPSMaster Open Source Project (FOSP)
## 项目简介
* FPSMaster是由FPSMaster团队开发的一个Minecraft PVP 客户端，本项目为其开源版本。
* FOSP(FPSMaster开源项目) 不同于其上游FPSMaster，FOSP是一个开源项目，你可以自由地使用、修改、分发和再许可本项目的代码。
* 开发人员：`@vlouboos` `@SuperSkidder` `@QianXia`
* 目前为止，FPSMaster版本为2.52
如何使用
## 特性/功能
* 帧数优化
* PVP功能
* 反作弊
* 优化的UI
## 如何配置
* 你需要安装Gradle
* 你需要安装Java 8
* 你需要安装Git
* 你需要安装IntelliJ IDEA
1. 克隆这个仓库
2. 打开IntelliJ IDEA
3. 设置启动配置(启动类为`Start`，在VM参数中添加natives的目录)`-Djava.library.path=你的natives目录`
4. 启动客户端
5. 运行`gradle build`来构建项目，客户端文件将会在`build/libs`目录下

## 贡献

感谢你考虑贡献这个项目！如果你想为项目贡献代码或报告问题，请遵循以下步骤：

1. Fork这个项目到你的GitHub账号。
2. 创建一个新的分支（branch）用于你的修改。
3. 进行修改和改进。
4. 提交一个Pull Request，描述你的改动内容。

请注意，所有贡献都需要遵守Apache License 2.0许可证。确保在你的贡献中包含适当的许可证和版权声明。

## 开源许可

这个项目采用 [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) 开源许可。
这意味着您可以自由地使用、修改、分发和再许可本项目的代码，但需要遵守以下条件：

**可以做什么：**
- 自由使用：您可以一定意义上自由地使用本项目的代码，无论是个人还是组织，都是允许的（除商业用途，见附加条款第一条）。
- 自由修改：您可以对本项目的代码进行任意修改、扩展和改进，并将修改后的版本分发。

**不可以做什么：**
- 不移除版权：您在使用本项目的代码时必须保留原始的版权声明和许可证信息，不能删除任何版权、许可证或免责声明。

**附加条款：**
- 禁止商业盈利：您不能将本项目的代码用于任何盈利的商业用途。只有非商业性质的使用是被允许的。
- 禁止使用相同名称：您不能将修改后的版本以与原项目相同的名称发布或分发。您可以在具体需要时，添加后缀或其他标识以区别您的版本和原项目（如您不能使用 FPSMaster `v???`这样的名字，但可以使用FPSMaster for xxx 这样不存在的名字，但不能与我们团队的其他FPSMaster项目名冲突）。
