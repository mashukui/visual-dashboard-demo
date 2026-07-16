# Python 可视化大屏聚合演示

一个基于 **pyecharts + Flask** 开发的可视化大屏演示项目，包含智慧城市、影视数据、社交媒体舆情等12个主题大屏。（本仓库用于演示大屏效果，未开源pyecharts代码）

## 在线演示

访问：[https://mashukui.github.io/visual-dashboard-demo/](https://mashukui.github.io/visual-dashboard-demo/)

## 技术栈

- Python / Flask
- pyecharts / ECharts
- GitHub Pages

## 本地运行

Flask 方式：

```bash
pip install flask
python app.py
```

静态预览：

```bash
python -m http.server 8000 --directory docs
```

## 说明

`templates/` 为 Flask 演示页面，`docs/` 为 GitHub Pages 部署版本。项目主要用于学习和效果展示。
