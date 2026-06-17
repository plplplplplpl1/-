# 网盘

数据集存储仓库。

## bridge_defect_yolo — 桥梁缺陷YOLO数据集（已标注）

- 图片：6308 张
- 标签：6308 个（YOLO txt 格式）
- 原始大小：4.35 GB
- 压缩格式：7z（mx=9 ultra）

### 合并分包

```bash
# Windows (cmd)
copy /b bridge_defect_yolo.7z.part_* bridge_defect_yolo.7z

# Linux / macOS / Git Bash
cat bridge_defect_yolo.7z.part_* > bridge_defect_yolo.7z
```

然后用 7-Zip 解压即可。
