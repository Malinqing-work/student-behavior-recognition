# Student-behavior-recognition

## 如何使用
- `python>=3.8`
- `pip install ultralytics==8.1.0` or `git clone --branch v8.1.0 --single-branch https://github.com/ultralytics/ultralytics.git`
- `pip install pyside6 chardet`
- `pip install torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113`
- `python main.py`


## 项目功能
- ✅ 图片推理
- ✅ 视频推理
- ✅ 摄像头推理
- ✅ RTSP 推流
- ✅ 检测任务推理
- ✅ Pytroch (.pt) 格式模型推理
- ✅ ONNX (.onnx) 格式模型推理
- ✅ 模型选择
- ✅ 置信度/阈值调整
- ✅ 延迟调整
- ✅ 保存推理结果

## 注意事项
- 如果想使用自己的模型，您需要先使用 `ultralytics` 来训练 yolov8 模型，然后将训练好的 `.pt/.onnx/.engine` 文件放入 `models/*` 文件夹。
- 如果模型是改进的，请将你整个项目文件导入。
- 如果选择保存结果，结果会保存在 `./run` 路径中。
- UI 设计文件是 `home.ui`，如果修改它，您需要使用 `pyside6-uic home.ui > ui/home.py` 命令来重新生成 `.py` 文件。
- 资源文件是 `resources.qrc`，如果您修改了默认图标，需要使用 `pyside6-rcc resources.qrc > ui/resources_rc.py` 命令来重新生成 `.py` 文件。


