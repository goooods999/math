# 部署指南

## 🚀 手动部署到 goooods.github.io

由于需要GitHub认证，你可以通过以下方式手动部署：

### 方法1：网页上传
1. 访问你的GitHub仓库：https://github.com/goooods/goooods.github.io
2. 点击 "Add file" → "Upload files"
3. 拖拽以下文件到上传区域：
   - `math_calculator_web.html`
   - `README.md`
4. 添加提交信息："添加数学计算器网页"
5. 点击 "Commit changes"

### 方法2：GitHub Desktop
1. 安装GitHub Desktop应用
2. 克隆你的仓库：https://github.com/goooods/goooods.github.io
3. 将项目文件复制到本地仓库文件夹
4. 在GitHub Desktop中提交并推送

### 方法3：配置SSH密钥（推荐）
如果你经常使用Git，建议配置SSH密钥：

```bash
# 生成SSH密钥
ssh-keygen -t ed25519 -C "your_email@example.com"

# 添加到ssh-agent
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519

# 将公钥添加到GitHub
cat ~/.ssh/id_ed25519.pub
```

然后将显示的公钥添加到GitHub账户的SSH keys中。

## 🌐 访问你的网站

部署成功后，你的数学计算器将在以下地址可用：
**https://goooods.github.io/math_calculator_web.html**

## ✨ 功能特色

- 🎨 Apple风格设计
- 🎭 卡通字体标题
- 🧮 三个数字求和
- 📱 响应式设计
- ✨ 动画效果
- 🏷️ 专属水印

## 📋 文件清单

- `math_calculator_web.html` - 主程序文件
- `README.md` - 项目说明文档

## 🎮 使用方法

1. 打开网页：https://goooods.github.io/math_calculator_web.html
2. 在三个输入框中输入数字
3. 点击"计算和"按钮
4. 查看计算结果

---

**提示**：由于你的仓库名是 `goooods.github.io`，这会自动启用GitHub Pages，无需额外配置！