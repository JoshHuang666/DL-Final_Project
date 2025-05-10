# 🧠 GitHub 協作流程指南（4人團隊）

這份文件用來統一團隊 Git 操作規則，請所有成員遵照以下流程。

---

## 🧱 分支規則

| 分支名稱          | 用途                        |
|-------------------|-----------------------------|
| `main`            | 正式穩定版，用於部署         |
| `dev`             | 整合開發版本，所有功能先合併進來 |
| `feature/xxx`     | 個人開發功能分支（如：feature/josh-login） |

---

## 🚀 建立個人功能分支

```bash
git checkout dev
git pull origin dev
git checkout -b feature/你的名字-功能名稱
git push -u origin feature/你的名字-功能名稱
