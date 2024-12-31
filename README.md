# My Resume - Taro + React 小程序

## 项目简介
这是一个基于 **Taro + React** 开发的简历小程序，使用了以下技术栈：
- **React**: 前端开发的核心框架。
- **Taro**: 多端开发框架，用于生成微信小程序。
- **TypeScript**: 提供类型安全。
- **Vite**: 快速的现代化构建工具。
- **NutUI**: 京东推出的小程序组件库，快速构建美观界面。
- **Tailwind CSS**: 实用优先的 CSS 框架，快速实现响应式布局。
- **Zustand**（可选）: 轻量状态管理库，管理项目状态。

## 项目特性
1. 响应式布局，适配多端设备。
2. 精美的 UI 界面，展示个人简历和项目。
3. 模块化开发，方便扩展。
4. 现代化的构建工具，开发体验流畅。

## 技术栈
| 技术      | 描述                             |
|-----------|----------------------------------|
| React     | 核心开发框架，支持组件化开发。     |
| Taro      | 多端支持框架，生成小程序/H5 应用。 |
| TypeScript| 类型安全，提高代码可靠性。         |
| Vite      | 构建工具，提升开发和构建速度。     |
| NutUI     | 美观的 UI 组件库，适配小程序。     |
| Tailwind  | CSS 框架，快速布局和响应式设计。   |

## 快速开始

### 1. 克隆项目
```bash
git clone <项目地址>
cd my-resume
```

### 2. 安装依赖
```bash
yarn install
```

### 3. 启动开发环境
运行以下命令启动微信小程序开发环境：
```bash
yarn dev:weapp
```

### 4. 构建小程序
打包小程序：
```bash
yarn build:weapp
```

### 5. 打开微信开发者工具
1. 打开[微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)。
2. 选择 `dist` 文件夹作为项目目录。
3. 预览并调试小程序。

## 项目结构
```plaintext
src/
├── app.config.ts      # 全局配置文件
├── app.scss           # 全局样式文件
├── pages/             # 页面目录
│   ├── index/         # 首页
│   │   ├── index.tsx  # 首页逻辑
│   │   ├── index.scss # 首页样式
│   └── ...            # 其他页面
├── components/        # 公共组件
├── store/             # 状态管理（Zustand 或其他）
└── assets/            # 静态资源
```

## 项目功能模块
1. **个人信息展示**：
   - 姓名、头像、自我介绍。
2. **技能展示**：
   - 使用图表展示技术栈熟练度。
3. **项目经验**：
   - 动态卡片，展示项目名称、描述和技术栈。
4. **联系方式**：
   - 邮箱、电话、一键复制等功能。

## 常用命令
| 命令             | 描述                       |
|------------------|--------------------------|
| `yarn dev:weapp` | 启动微信小程序开发环境。     |
| `yarn build:weapp` | 构建微信小程序文件。         |
| `yarn dev:h5`    | 启动 H5 开发环境（可选）。    |
| `yarn build:h5`  | 构建 H5 应用（可选）。        |

## 部署
1. 执行 `yarn build:weapp` 生成小程序文件。
2. 在微信开发者工具中上传代码。
3. 提交审核并发布。

## 常见问题
1. **`yarn` 命令未找到**：
   - 请确保已安装 Yarn（可通过 `npm install -g yarn` 安装）。
2. **微信开发者工具无法识别项目**：
   - 确保 `dist` 目录为选择的项目路径。
3. **样式冲突**：
   - 确保 Tailwind CSS 和 NutUI 的样式引入正确。

## 学习资源
- [Taro 官方文档](https://taro-docs.jd.com/)
- [React 官方文档](https://react.dev/)
- [NutUI 官方文档](https://nutui.jd.com/react/#/start)
- [Tailwind CSS 官方文档](https://tailwindcss.com/)
- [微信小程序开发文档](https://developers.weixin.qq.com/miniprogram/dev/framework/)

## 贡献
如果你对该项目有任何建议或改进意见，欢迎提交 PR 或 Issue！

---
感谢使用本项目，希望它能帮助你在求职中脱颖而出！

