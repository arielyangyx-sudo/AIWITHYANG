# AIWITHYANG — 个人作品集网站

Ariel Yang 的个人作品集网站：AI Agent 工作流设计、生成式视频创作与数字营销实践。

**在线访问**：GitHub Pages 发布后地址为 `https://<你的用户名>.github.io/<仓库名>/`

## 本地预览

无需任何构建工具，直接双击 `index.html` 即可在浏览器打开；或启动任意静态服务器：

```bash
cd AIWITHYANG_fixed
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 项目结构

```
AIWITHYANG_fixed/
├── index.html      # 单文件网站（HTML + CSS + JS，零外部依赖）
└── assets/         # 图片（webp/png/jpg）与视频（mp4）
```

## 特性

- 单文件架构，零 CDN 依赖，断网可运行
- 中英双语切换（右上角 EN / 中文）
- 图片双击放大灯箱
- 响应式布局，移动端自适应
- 视频已压缩至网页友好体积（faststart 流式加载）

## License

代码以 MIT 协议开源。网站中的个人作品素材（图片、视频）版权归 Ariel Yang 所有，未经授权请勿转载使用。
