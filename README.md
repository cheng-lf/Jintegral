# DIC散斑图像质量评估

这个项目是一个在线工具，用于评估DIC（数字图像相关）散斑图像的质量。用户可以上传一系列的散斑图像，系统会在线评估散斑质量并显示结果。

## 功能

- 拖放或选择文件上传多个散斑图像
- 在线评估散斑图像质量
- 显示每个图像的质量评分

## 技术栈

- 前端：HTML, CSS, JavaScript (jQuery)
- 后端：Python (Flask)
- 图像处理：OpenCV, NumPy, SciPy

## 部署

前端部署在Cloudflare Pages上，后端需要单独部署在支持Python的服务器上。

## 使用说明

1. 访问网站
2. 拖放文件到指定区域或点击选择文件
3. 等待评估结果显示

## 注意事项

请确保上传的是有效的DIC散斑图像，以获得准确的评估结果。
