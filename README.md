# 安吉旅行规划平台

一个基于高德地图API的智能旅行规划平台，提供路线规划、美食推荐、酒店预订和景点介绍等功能。

## 功能特色

- 🗺️ **智能导航**: 支持从无锡/南京到安吉天目山漂流的路线规划
- 🍽️ **美食推荐**: 展示当地特色餐厅和美食
- 🏨 **酒店预订**: 提供多种住宿选择和价格对比
- 🎯 **景点介绍**: 详细的旅游景点信息
- 🎵 **背景音乐**: 支持音乐播放和头像旋转动画
- 📱 **响应式设计**: 完美适配移动端和桌面端

## 部署到GitHub Pages

### 1. 创建GitHub仓库

1. 登录GitHub，点击右上角的 "+" 号，选择 "New repository"
2. 仓库名称建议使用：`anji-travel-platform`
3. 设置为 Public（公开）
4. 勾选 "Add a README file"
5. 点击 "Create repository"

### 2. 上传文件

1. 在仓库页面点击 "uploading an existing file"
2. 将以下文件拖拽上传：
   - `安吉旅行规划平台.html`
   - `assets/` 文件夹（包含头像图片）
   - 其他相关文件

### 3. 启用GitHub Pages

1. 进入仓库的 Settings 页面
2. 滚动到 "Pages" 部分
3. 在 "Source" 下选择 "Deploy from a branch"
4. 选择 "main" 分支和 "/ (root)" 文件夹
5. 点击 "Save"

### 4. 访问网站

几分钟后，您的网站将在以下地址可用：
```
https://[您的用户名].github.io/anji-travel-platform/安吉旅行规划平台.html
```

## 头像图片说明

当前头像使用的是本地图片 `assets/1.jpg`，部署到GitHub后：
- ✅ **头像会正常显示**：因为图片文件会一起上传到GitHub
- ✅ **旋转动画正常**：CSS动画不依赖外部资源
- ✅ **音乐联动功能**：头像旋转与音乐播放的联动功能完全保留

## 技术栈

- HTML5 + CSS3 + JavaScript
- 高德地图API
- 响应式布局
- CSS动画效果

## 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 注意事项

1. **高德地图API密钥**：当前使用的是测试密钥，建议申请自己的API密钥
2. **音乐播放**：由于浏览器安全策略，音乐需要用户交互后才能播放
3. **HTTPS要求**：GitHub Pages默认使用HTTPS，确保所有外部资源也使用HTTPS

## 本地开发

```bash
# 启动本地服务器
python -m http.server 8000

# 访问地址
http://localhost:8000/安吉旅行规划平台.html
```

## 许可证

MIT License

---

**享受您的安吉之旅！** 🎋✨