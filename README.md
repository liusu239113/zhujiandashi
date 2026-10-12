# zhujiandashi

ForgeTaxCrack Unity 项目还原（解包/反编译/安全报告）。

## 完整包
在 Releases (v1.0.0) 以分卷方式提供（因 GitHub 单文件 100MB 限制）：

- ForgeTaxCrack.7z.part_aa (80MB)
- ForgeTaxCrack.7z.part_ab (80MB)
- ForgeTaxCrack.7z.part_ac (80MB)
- ForgeTaxCrack.7z.part_ad (20MB)

### 合并（Windows cmd）
```
copy /b ForgeTaxCrack.7z.part_aa+ForgeTaxCrack.7z.part_ab+ForgeTaxCrack.7z.part_ac+ForgeTaxCrack.7z.part_ad ForgeTaxCrack.7z
```
### 合并（Linux/macOS）
```
cat ForgeTaxCrack.7z.part_* > ForgeTaxCrack.7z
```

### 校验
size = 272702548 bytes
md5  = 8f5730e89e794f5162cae3d0bb0ae4de
