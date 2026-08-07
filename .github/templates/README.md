# 🛠️ APK 构建 Workflow 模板库

按项目类型分开维护，遇到对应类型直接复制到 `.github/workflows/` 使用。

## 模板列表

| 模板文件 | 适用类型 | 适用项目 |
|---|---|---|
| `build-native-apk.yml` | 原生 Kotlin/Compose Android（Gradle） | 橘瓣 OrangeChat |
| `build-capacitor-apk.yml` | Web 前端 + Capacitor 壳 | Miya、玄鲸 freeapp、手抓糯米机 SullyOS |

## 快速使用

```bash
# 原生 Gradle 项目
cp .github/templates/build-native-apk.yml .github/workflows/

# Capacitor 项目
cp .github/templates/build-capacitor-apk.yml .github/workflows/
```

改好分支名/参数后 push 即自动构建，APK 在 Actions artifact 中下载。

---

*模板库最后更新时间：2026-08-07 00:44 UTC*
