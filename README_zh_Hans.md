<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 DumbDo

[![集成程度](https://apps.yunohost.org/badge/integration/dumbdo)](https://ci-apps.yunohost.org/ci/apps/dumbdo/)
![工作状态](https://apps.yunohost.org/badge/state/dumbdo)
![维护状态](https://apps.yunohost.org/badge/maintained/dumbdo)

[![使用 YunoHost 安装 DumbDo](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbdo)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 DumbDo。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A stupidly simple todo list application that just works. No complex database, no unnecessary features - just todos.

### Features

- Clean, minimal interface
- Dark/Light mode with system preference detection
- File-based storage - todos persist between sessions
- Fully responsive design
- Fast and lightweight
- PIN protection (4-10 digits if enabled)


**分发版本：** 2025.03.18~ynh1

## 截图

![DumbDo 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://www.dumbware.io/>
- 上游应用代码库： <https://github.com/DumbWareio/DumbDo>
- YunoHost 商店： <https://apps.yunohost.org/app/dumbdo>
- 报告 bug： <https://github.com/YunoHost-Apps/dumbdo_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/dumbdo_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbdo_ynh/tree/testing --debug
或
sudo yunohost app upgrade dumbdo -u https://github.com/YunoHost-Apps/dumbdo_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
