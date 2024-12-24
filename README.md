# OCR文字识别工具

一个基于百度OCR API的截图文字识别工具。

## 功能特点

- 快捷键截图识别（默认 Alt+D）
- 自动复制到剪贴板
- 系统托盘运行
- 日志记录和查看

## 使用前准备

1. **获取百度OCR API密钥**
   - 访问[百度AI开放平台](https://console.bce.baidu.com/ai/)
   - 注册/登录账号
   - 创建应用，获取 APP_ID、API_KEY 和 SECRET_KEY

2. **安装必要环境**
   - 安装 [Python 3.11](https://www.python.org/downloads/) 或更高版本
   - 运行 `install.bat` 安装依赖

## 使用方法

### 方式一：直接运行

1. 运行 `run.bat`
2. 在程序界面填入百度OCR的配置信息
3. 点击"启动服务"
4. 使用快捷键（默认Alt+D）进行截图识别
5. 识别结果会自动复制到剪贴板

### 方式二：使用打包版本

1. 下载 Release 中的打包版本
2. 解压后运行 `OCR文字识别工具.exe`
3. 填入配置信息并使用

## 快捷键说明

- `Alt+D`：开始截图（可在界面中自定义）
- `右键点击`：取消截图
- `ESC`：取消截图

## 系统托盘

- 程序可以最小化到系统托盘
- 右键点击托盘图标可以：
  - 显示主窗口
  - 退出程序

## 常见问题

1. **无法启动服务**
   - 检查百度OCR配置是否正确
   - 确保网络连接正常

2. **截图无法识别**
   - 确保截图区域包含文字
   - 尝试调整截图范围

3. **程序闪退**
   - 检查是否安装了所有依赖
   - 查看日志文件了解详细错误信息

## 开发相关

### 环境要求

- Python 3.11+
- 依赖包：见 requirements.txt

### 构建方法

## 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

## 联系方式

如有问题或建议，请：
1. 提交 Issue
2. 发起 Pull Request