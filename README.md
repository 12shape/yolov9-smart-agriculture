 基于YOLOv9的智慧农业AI诊断系统
 计算机视觉 | 智慧农业 | 全栈项目

## 📖 项目简介
本项目是一套**完整的智慧农业AI解决方案**，基于YOLOv9目标检测算法实现农作物病虫害智能识别，集成环境监测、长势评估、产量预测、智能控制、数据可视化大屏为一体。
采用B/S架构+Flask MVC分层开发，前端打造高端紫色星空毛玻璃UI，全程可本地部署、实时演示。

## 🚀 核心功能
- ✅ YOLOv9病虫害精准识别（15类农作物病害）
- ✅ 作物长势智能评估
- ✅ 农业环境实时监测（温湿度/土壤/光照）
- ✅ 时序数据产量预测
- ✅ 智能设备自动控制
- ✅ 可视化数据大屏
- ✅ 历史数据管理

## 🛠️ 技术栈
- 后端：Python + Flask + SQLAlchemy
- AI模型：YOLOv9（目标检测）
- 前端：HTML/CSS/JS + Bootstrap + ECharts
- 数据库：SQLite
- 定时任务：APScheduler
- 部署：本地Windows/Linux

## 🎨 界面展示
紫色星空渐变UI + 毛玻璃效果，高端科技风，适配毕设/复试演示

## 📦 模型下载
训练好的YOLOv9病虫害模型：
https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov9-crop-disease-best.pt
下载后重命名为 best.pt 放入 core/ai_models/pest_detection/

## 🧩 运行方式
1. 安装依赖：pip install flask flask-login ultralytics opencv-python
2. 放入模型文件
3. 启动：python app.py
4. 浏览器访问：http://127.0.0.1:5000
