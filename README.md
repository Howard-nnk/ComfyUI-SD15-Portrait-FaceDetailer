# ComfyUI SD 1.5 Portrait Workflow with FaceDetailer

A ComfyUI text-to-image portrait workflow for SD 1.5 checkpoints. It uses FaceDetailer to refine facial details in generated images.

**Tested with:** Realistic Vision V6

## Requirements

- ComfyUI
- An SD 1.5 checkpoint
- ComfyUI-Impact-Pack
- ComfyUI-Impact-Subpack
- Face detection model: `bbox/face_yolov8m.pt`

## How to Use

1. Import `RealisticVision-FaceDetailer.json` into ComfyUI.
2. Install the required custom nodes and face detection model.
3. Select an SD 1.5 checkpoint in the Checkpoint Loader node. Realistic Vision V6 is the tested model.
4. Enter your positive and negative prompts, then click **Run**.

## Compatibility

This workflow was built and tested with Realistic Vision V6, an SD 1.5 checkpoint. Other SD 1.5 checkpoints may work, but results can vary and may require changes to prompts or settings. SDXL, Flux, and other model architectures are not confirmed compatible.

## Notes

This repository contains the workflow JSON only; it does not include checkpoint or detector model files. Download and use models and custom nodes according to their respective licenses.

---

# ComfyUI SD 1.5 人像工作流（含 FaceDetailer）

这是一个面向 SD 1.5 Checkpoint 的 ComfyUI 文生图人像工作流，使用 FaceDetailer 优化生成图像中的面部细节。

**已测试模型：** Realistic Vision V6

## 所需组件

- ComfyUI
- 一个 SD 1.5 Checkpoint
- ComfyUI-Impact-Pack
- ComfyUI-Impact-Subpack
- 人脸检测模型：`bbox/face_yolov8m.pt`

## 使用方法

1. 将 `RealisticVision-FaceDetailer.json` 导入 ComfyUI。
2. 安装所需的自定义节点和人脸检测模型。
3. 在 Checkpoint 加载器节点中选择一个 SD 1.5 模型；目前已测试的是 Realistic Vision V6。
4. 填写正向和负向提示词，然后点击“运行”。

## 兼容性

本工作流基于 Realistic Vision V6（SD 1.5）制作并完成测试。其他 SD 1.5 模型可能也能使用，但生成效果可能不同，或需要调整提示词和参数。SDXL、Flux 等其他模型架构尚未确认兼容。

## 说明

本仓库只提供工作流 JSON，不包含 Checkpoint 或检测器模型文件。下载和使用模型及自定义节点时，请遵守各自的许可条款。