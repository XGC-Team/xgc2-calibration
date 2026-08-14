# xgc2-calibration

Public XGC-Team aggregator for calibration products. Each tool stays in its
own repository; this tree only pins the checkouts used by the product catalog.

| Path | Repository | Branch |
| --- | --- | --- |
| `camera-calibration` | [xgc2-camera-calibration](https://github.com/XGC-Team/xgc2-camera-calibration) | `main` |
| `lidar-imu-calibration` | [xgc2-lidar-imu-calibration](https://github.com/XGC-Team/xgc2-lidar-imu-calibration) | `main` |

Clone recursively:

```bash
git clone --recurse-submodules git@github.com:XGC-Team/xgc2-calibration.git
```

The main catalog mounts this repository at
`products/ros1/perception/calibration`.
