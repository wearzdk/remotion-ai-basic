# Remotion AI 视频生产模板

<p align="center">
  <a href="https://github.com/remotion-dev/logo">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/remotion-dev/logo/raw/main/animated-logo-banner-dark.apng">
      <img alt="Animated Remotion Logo" src="https://github.com/remotion-dev/logo/raw/main/animated-logo-banner-light.gif">
    </picture>
  </a>
</p>

面向 AI 的 Remotion 视频生产模板，预装了丰富的可视化与动画库，可直接用于程序化视频生成。

## 命令

**安装依赖**

```console
bun install
```

**启动预览**

```console
bun run dev
```

**渲染视频**

```console
bunx remotion render
```

**升级 Remotion**

```console
bunx remotion upgrade
```

## 预装包说明

### Remotion 核心与扩展

| 包名                                        | 用途                             |
| ------------------------------------------- | -------------------------------- |
| `remotion` / `@remotion/cli`                | 核心渲染引擎与 CLI 工具          |
| `@remotion/captions`                        | 字幕/CC 文字轨道渲染             |
| `@remotion/google-fonts`                    | Google 字体按需加载              |
| `@remotion/layout-utils`                    | 文字排版工具（自动换行、测量等） |
| `@remotion/lottie`                          | 播放 Lottie JSON 动画文件        |
| `@remotion/media` / `@remotion/media-utils` | 音视频素材处理与时长获取         |
| `@remotion/media-parser`                    | 解析音视频元数据                 |
| `@remotion/paths`                           | SVG 路径动画工具                 |
| `@remotion/shapes`                          | 内置几何图形组件（矩形、圆形等） |
| `@remotion/tailwind-v4`                     | Tailwind CSS v4 集成             |
| `@remotion/three`                           | Remotion 与 Three.js 桥接层      |
| `@remotion/zod-types`                       | Remotion Props 的 Zod 类型定义   |
| `remotion-bits`                             | Remotion 社区组件库              |

### 3D 渲染

| 包名                 | 用途                                 |
| -------------------- | ------------------------------------ |
| `@react-three/fiber` | React 版 Three.js 渲染器，做 3D 场景 |
| `@react-three/drei`  | Three.js 常用工具与预制组件          |

### 动画

| 包名            | 用途                                  |
| --------------- | ------------------------------------- |
| `framer-motion` | 声明式 React 动画库，支持复杂过渡效果 |
| `gsap`          | 高性能时间轴动画引擎，适合精细编排    |
| `simplex-noise` | 柏林噪声生成，用于有机感的程序化动画  |

### 数据可视化

| 包名                | 用途                                          |
| ------------------- | --------------------------------------------- |
| `recharts`          | 基于 D3 的 React 图表库（折线、柱状、饼图等） |
| `d3-shape`          | D3 底层图形计算（曲线、面积、弧形路径）       |
| `react-simple-maps` | 地理地图可视化组件                            |

### 代码展示

| 包名                              | 用途                       |
| --------------------------------- | -------------------------- |
| `codehike` / `@code-hike/lighter` | 代码高亮与分步代码演示动画 |
| `react-syntax-highlighter`        | 代码语法高亮渲染           |

### 数学与图标

| 包名           | 用途               |
| -------------- | ------------------ |
| `react-katex`  | LaTeX 数学公式渲染 |
| `lucide-react` | 高质量 SVG 图标库  |

### 样式

| 包名          | 用途                                                 |
| ------------- | ---------------------------------------------------- |
| `tailwindcss` | 原子化 CSS 框架（配合 `@remotion/tailwind-v4` 使用） |

## 文档

- [Remotion 基础概念](https://www.remotion.dev/docs/the-fundamentals)
- [Remotion API 文档](https://www.remotion.dev/docs)
