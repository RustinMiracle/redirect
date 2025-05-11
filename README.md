# 通用应用链接重定向服务

这是一个通用的 GitHub Pages 服务，用于将 HTTP 链接重定向到各种应用程序的 URI 协议。

## 支持的应用程序

- Obsidian (`obsidian://`)
- OmniFocus (`omnifocus://`)
- Notion (`notion://`)
- Evernote (`evernote://`)
- Bear (`bear://`)
- Craft (`craft://`)
- Drafts (`drafts://`)
- Things (`things://`)
- Todoist (`todoist://`)
- TickTick (`ticktick://`)

## 使用方法

1. 将应用程序名称和 URI 作为参数添加到 URL 中：

```
https://[您的GitHub用户名].github.io/[仓库名]/?app=obsidian&uri=adv-uri?uid=dda40d33-a4d2-4caa-ab2a-dfc36093a482
```

2. 访问该链接后，将自动重定向到对应的应用程序。

## 示例

- Obsidian 链接：
```
https://[您的GitHub用户名].github.io/[仓库名]/?app=obsidian&uri=open?vault=MyVault&file=MyNote
```

- OmniFocus 链接：
```
https://[您的GitHub用户名].github.io/[仓库名]/?app=omnifocus&uri=task/123456
```

- Notion 链接：
```
https://[您的GitHub用户名].github.io/[仓库名]/?app=notion&uri=page/123456
```

## 部署步骤

1. Fork 这个仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择 main 分支作为源
4. 等待几分钟后，您的重定向服务就会生效

## 功能特点

- 支持多种应用程序的 URI 协议
- 自动检测应用是否已安装
- 提供应用下载链接
- 美观的错误提示界面
- 响应式设计，支持移动设备

## 注意事项

- 确保目标应用程序已经安装在您的设备上
- 链接中的特殊字符需要进行 URL 编码
- 建议使用 HTTPS 链接以确保安全性
- 某些应用程序可能需要特定的 URI 格式，请参考相应应用的文档 