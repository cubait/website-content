## 概述
CUBA WebDAV扩展组件为CUBA应用程序提供强大的功能，可以协同处理各种格式的文档。

插件通过标准的CUBA文件存储API使用WebDAV协议。此外，还提供UI组件，将WebDAV的功能开放给GUI级别，同时也提供REST API，让用户能操控第三方客户端的文件存储。

关键功能：
* 在MS Office（或者其他支持WebDAV的应用程序）中能从服务器无缝的打开、编辑和保存文档，无需繁琐的手动保存到本地磁盘然后上传回服务器。
* 在通用CUBA UI能使用的可视化组件，用来处理文件和版本。
* 完全支持协同工作和文件版本控制，可从客户端应用程序和CUBA UI进行管理。
* 可配置的冲突解决策略。
* 通过与CUBA平台安全子系统的完全集成，轻松实现文件访问控制管理。
* 使用静态链接从外部系统访问文件。
* REST API.

文件和版本存储在标准CUBA文件存储之上，因此不需要外部WebDAV服务器。

### 自动迁移

如果您已经有一个应用程序，存储文件，并希望使用WebDAV功能进行增强，这很容易实现。该扩展组件包含迁移工具，用于启用和禁用WebDAV对数据模型中现有文件描述符的支持。

### 许可

该扩展组件使用组织级许可，包括：

* 不限数量的开发人员，服务器和项目。
* 访问源码仓库。
* 作为应用程序的一部分无限制地分发该扩展组件的权利。
* 订阅期间的所有升级。
* 订阅到期后继续使用以前下载的版本的权利。

Studio和扩展组件试用版中包含WebDAV[的试用版](https://www.cuba-platform.com/store#/store/studio-trial)