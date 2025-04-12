# 千早爱音与长崎素世互动网站

这是一个简单的互动网站，展示了千早爱音和长崎素世两个角色，并实现了一个有趣的互动效果。

## 功能介绍

- 主页展示左边的千早爱音和右边的长崎素世
- 中间上方显示粉色文字"呐呐，soyorin你喜欢我吗"
- 下方有"喜欢"和"不喜欢"两个按钮
- 点击"不喜欢"按钮时，该按钮会变小，而"喜欢"按钮会变大
- 连续点击三次"不喜欢"后，该按钮会消失，只剩下"喜欢"按钮
- 点击"喜欢"按钮时，会跳转到第二个页面，显示两个角色站在一起和粉色文字"soyorin，love♡～我也喜欢你"

## 部署指南

### 本地部署

1. 克隆或下载此仓库到本地
2. 使用任意HTTP服务器托管这些文件，例如：

   使用Python的简易HTTP服务器：
   ```
   python -m http.server 8080
   ```
   
   或使用Node.js的http-server：
   ```
   npm install -g http-server
   http-server -p 8080
   ```

3. 在浏览器中访问 `http://localhost:8080` 查看网站

### 服务器部署

1. 将所有文件上传到您的Web服务器（如Nginx、Apache等）的根目录
2. 确保服务器配置正确指向index.html作为默认页面
3. 通过您的域名访问网站

## 自定义

- 您可以替换images文件夹中的SVG文件为实际的角色图片（建议使用JPG或PNG格式）
- 可以在CSS中修改颜色、字体等样式以符合您的喜好

## 注意事项

- 当前使用的是SVG占位图，实际部署时请替换为真实的角色图片
- 网站已做响应式设计，适合在不同设备上查看