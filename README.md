# siboteAI - AI图片生成与社区分享平台

这是一个基于React、TypeScript和Tailwind CSS构建的AI图片生成与社区分享平台。用户可以通过多种AI模型生成图片，浏览社区作品，并管理个人创作。

## 如何预览项目

### 方法一：使用开发服务器（推荐）

1. 确保您已安装Node.js（版本16或更高）和npm/pnpm
2. 在项目根目录运行以下命令安装依赖：

```bash
npm install
# 或
pnpm install
```

3. 启动开发服务器：

```bash
npm run dev
# 或
pnpm dev
```

4. 服务器启动后，在浏览器中访问 http://localhost:3000 即可预览项目

### 方法二：构建生产版本

如果您想预览生产版本的效果：

1. 安装依赖（同方法一）
2. 构建项目：

```bash
npm run build
# 或
pnpm build
```

3. 构建完成后，生成的静态文件将位于 `dist/static` 目录
4. 使用任何静态文件服务器预览构建结果，例如：

```bash
# 使用npx serve
npx serve dist/static

# 或使用Python的内置服务器
cd dist/static
python -m http.server
```

## 项目功能

- 🎨 **AI图片生成**：支持多种AI模型（豆包、Nano Banana、ComfyUI）
- 🌐 **社区分享**：浏览、搜索和点赞其他用户的作品
- 📁 **个人中心**：管理个人创作和收藏
- 🌓 **深色/浅色模式**：支持系统主题和手动切换
- 📱 **响应式设计**：适配桌面和移动设备

## 技术栈

- React 18+
- TypeScript
- Tailwind CSS
- Vite
- Framer Motion（动画效果）
- React Router（路由）
- Recharts（图表可视化）
- Sonner（提示组件）

## 快速开始

安装依赖：
```bash
npm install
# 或
pnpm install
```

开发模式：
```bash
npm run dev
# 或
pnpm dev
```

构建生产版本：
```bash
npm run build
# 或
pnpm build
```

## 注意事项

- 本项目使用模拟数据，所有图片均通过API生成
- 登录和注册功能为前端模拟实现
- 如需部署，请确保配置正确的静态文件服务