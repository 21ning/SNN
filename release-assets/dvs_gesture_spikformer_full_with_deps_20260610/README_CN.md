# DVS Gesture Spikformer 完整依赖包

这里是完整包的 GitHub 分卷版本，包含：

- DVS Gesture Spikformer 训练/评估脚本
- `external/spikformer/cifar10dvs` 官方模型代码
- `external/spikformer_deps` 本地依赖目录
- best checkpoint
- training history / metadata
- 中文 README

由于完整压缩包为 117MB，普通 GitHub 仓库会阻止超过 100MB 的单文件，所以这里拆成 3 个分卷：

```text
dvs_gesture_spikformer_full_with_deps_20260610.tar.gz.part-00  50MB
dvs_gesture_spikformer_full_with_deps_20260610.tar.gz.part-01  50MB
dvs_gesture_spikformer_full_with_deps_20260610.tar.gz.part-02  17MB
```

## 合并

```bash
cat dvs_gesture_spikformer_full_with_deps_20260610.tar.gz.part-* > dvs_gesture_spikformer_full_with_deps_20260610.tar.gz
```

## 校验

```bash
sha256sum -c SHA256SUMS.txt
```

期望 SHA256：

```text
e54c4ad0ba6fab6575823a17d6d0b1da1a035bb48ebe2f4bd175062d69d4cc19
```
