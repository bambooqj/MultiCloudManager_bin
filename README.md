**MultiCloudManager v1.1.0 - 发布版 README**

统一管理 10 个云平台资源的跨平台桌面应用

**支持平台**  
Windows 10+ | macOS 10.15+ | Linux (Ubuntu 18.04+)

**支持云平台**  
AWS · Azure · Google Cloud · 阿里云 · 腾讯云 · 华为云 · Oracle Cloud · DigitalOcean · Vultr · Cloudflare

**下载地址**  
[MultiCloudManager](https://github.com/bambooqj/MultiCloudManager_bin/releases/download/1.1.0/MultiCloudManager-1.1.0-x64.exe)

**快速开始**  
1. 下载对应平台的安装包  
2. 安装/解压后启动程序  
3. 首次启动 → 设置 6 位 PIN 码  
4. 进入「凭证管理」添加云平台密钥  
5. 系统自动验证权限 → 即可使用  

**凭证支持方式**  
- AWS: Access Key ID + Secret  
- Azure: Tenant ID + Client ID + Client Secret  
- GCP: Service Account JSON  
- 阿里云 / 腾讯云 / 华为云: AK + SK  
- Oracle: Tenancy/User OCID + Fingerprint + Private Key  
- DigitalOcean / Vultr: API Token  
- Cloudflare: API Token  

**主要功能**  
- 统一主机、存储、数据库、网络、DNS、LB、CDN、IAM、监控视图  
- 凭证 AES-256 加密本地存储 + PIN 保护  
- 操作全量审计日志  
- 所有数据不上传云端  

**数据存储位置**  
- Windows: %APPDATA%\multi-cloud-manager\  
- macOS: ~/Library/Application Support/multi-cloud-manager/  
- Linux: ~/.config/multi-cloud-manager/  

**免责声明**

本工具仅供合法的运维管理、安全渗透测试及研究使用，必须在获得明确授权的前提下使用。

使用本工具造成的任何直接或间接后果（包括但不限于数据泄露、系统损坏、法律责任、经济损失等），由使用者自行承担全部责任。

作者及开发者不对任何使用行为及其结果承担任何形式的责任或赔偿义务。

使用即表示您已阅读、理解并完全接受本免责声明。

**许可证**  
MIT License

**问题反馈**  
GitHub Issues: https://github.com/bambooqj/MultiCloudManager_bin/issues
