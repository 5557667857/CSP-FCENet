# CSP-FCENet
Cross Stage Partial Feature Complementarity and Enhancement for SAR Ship Detection


## Acknowledgements

This project is built upon [Ultralytics YOLO11 (v8.3.9)](https://github.com/ultralytics/ultralytics) and is released under the **AGPL-3.0 license**, following the upstream project's licensing terms.

## Usage

```python
from ultralytics import YOLO

model = YOLO("csp-fcenet.yaml")  # CSP-FCENet (CSP_FCM backbone + CSPOmniKernel neck + Detect_LSCD head)
model.train(data="your_dataset.yaml", epochs=300, imgsz=640)
```
