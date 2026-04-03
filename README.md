# Cloudflare Tunnel 优化版 - 官网

这是一个静态网站，展示 Cloudflare Tunnel 优化版的使用说明。

## 如何访问

### 本地访问

```bash
# 进入目录
cd cloudflare-tunnel-website

# 启动本地服务器
python3 -m http.server 8080

# 访问 http://localhost:8080
```

### 公网访问

使用 cloudflare-tunnel-optimized 项目生成隧道：

```bash
# 克隆项目
git clone https://github.com/nananyunxi/cloudflare-tunnel-optimized.git
cd cloudflare-tunnel-optimized

# 启动隧道
./scripts/start-quick.sh 8080
```

启动后会显示公网访问地址，例如：
`https://xxxxx.trycloudflare.com`

## 官网内容

- 项目介绍
- 核心特性
- 优化说明
- 不同系统使用说明
- 常见问题

## 技术栈

- 纯 HTML/CSS/JavaScript
- 响应式设计，支持手机和 PC
- 无需后端服务器

## 许可证

MIT License