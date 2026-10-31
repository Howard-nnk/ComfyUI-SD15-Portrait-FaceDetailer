# Realistic Vision Portrait Workflow with FaceDetailer

A ComfyUI text-to-image workflow based on Realistic Vision V6. FaceDetailer is used to refine facial details in the generated image.

## Requirements

- Realistic Vision V6 checkpoint
- ComfyUI-Impact-Pack
- ComfyUI-Impact-Subpack
- Face detection model: `bbox/face_yolov8m.pt`

## How to Use

1. Import `RealisticVision-FaceDetailer.json` into ComfyUI.
2. Make sure the required model and custom nodes are installed.
3. Select the Realistic Vision checkpoint in the Checkpoint Loader node.
4. Enter your positive and negative prompts, then click **Run**.

## Notes

This repository contains the workflow JSON only; it does not include model files. Download and use each model and custom node according to its own license.


translate 翻译：



# Realistic Vision 人像工作流（含 FaceDetailer）

这是一个基于 Realistic Vision V6 的 ComfyUI 文生图工作流，使用 FaceDetailer 优化生成图像中的面部细节。

## 需要准备

- Realistic Vision V6 模型
- ComfyUI-Impact-Pack
- ComfyUI-Impact-Subpack
- 人脸检测模型：`bbox/face_yolov8m.pt`

## 使用方法

1. 将 `RealisticVision-FaceDetailer.json` 导入 ComfyUI。
2. 确认所需模型和自定义节点已经安装。
3. 在 Checkpoint 节点选择 Realistic Vision 模型。
4. 填写正向、负向提示词，然后点击“运行”。

## 说明

本仓库只提供工作流 JSON，不包含模型文件。请根据模型和自定义节点各自的许可条款下载与使用。