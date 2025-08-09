### **Gemini-to-Claude-Converter**
A plugin to transform Gemini's UI and font style to mimic Claude's.

**Version:** 1.5.1
**License:** MIT

---

### 项目简介 (Project Introduction)

**中文：**
Gemini Claude字体切换器是一个油猴脚本，可以将Google Gemini网页的字体替换为Claude官网同款的优雅衬线字体，让你在使用Gemini时享受到更舒适的阅读体验。

**版本**: v1.5.1
**适用网站**: [https://gemini.google.com/](https://gemini.google.com/)*

**English:**
The Gemini-to-Claude-Converter is a Tampermonkey script that replaces the font on the Google Gemini webpage with the elegant serif font used on the official Claude website, providing a more comfortable reading experience.

**Version:** v1.5.1
**Applicable websites:** [https://gemini.google.com/](https://gemini.google.com/)*

---

### 安装步骤 (Installation Guide)

**中文：**

#### 1. 安装油猴插件
首先需要在浏览器中安装Tampermonkey（油猴）插件：
- **Chrome**: 在Chrome网上应用店搜索"Tampermonkey"
- **Firefox**: 在Firefox附加组件商店搜索"Tampermonkey"
- **Edge**: 在Edge加载项商店搜索"Tampermonkey"
- **Safari**: 安装"Tampermonkey Safari"

#### 2. 安装脚本
1. 安装好Tampermonkey后，点击浏览器工具栏中的油猴图标。
2. 选择"创建新脚本"。
3. 删除默认内容，粘贴完整的脚本代码。
4. 按 `Ctrl + S` 保存脚本。

**English:**

#### 1. Install Tampermonkey
First, you need to install the Tampermonkey browser extension:
- **Chrome**: Search for "Tampermonkey" in the Chrome Web Store.
- **Firefox**: Search for "Tampermonkey" in the Firefox Add-ons store.
- **Edge**: Search for "Tampermonkey" in the Edge Add-ons store.
- **Safari**: Install "Tampermonkey Safari".

#### 2. Install the Script
1. After installing Tampermonkey, click the icon in your browser's toolbar.
2. Select "Create a new script".
3. Delete the default content and paste the complete script code.
4. Press `Ctrl + S` to save the script.

---

### 功能特性 (Features)

#### ✨ 主要功能 (Key Features)
- **Claude官网字体**: 将页面字体替换为`ui-serif`等优雅衬线字体。
- **智能排除**: 自动排除按钮、图标等UI元素，保持界面美观。
- **代码字体保护**: 保持代码块的等宽字体不变。
- **欢迎词主题色**: 将"你好，用户名"等欢迎词改为Claude主题色。
- **多语言支持**: 支持中文、英文、法文、西班牙文等多种语言。
- **一键切换**: 随时开启/关闭字体效果。

####  界面元素 (UI Elements)
- **切换按钮**: 页面右上角的橙色圆角按钮。
- **提示信息**: 切换时显示的状态提示。
- **右键菜单**: 油猴右键菜单中的快捷命令。

---

### 使用方法 (How to Use)

#### 基本操作 (Basic Usage)
1. **访问Gemini**: 打开 [https://gemini.google.com](https://gemini.google.com/)。
2. **查看按钮**: 页面右上角会出现一个橙色的"默认字体"按钮。
3. **启用字体**: 点击按钮切换为"Claude字体"。
4. **享受体验**: 页面字体立即切换为Claude官网同款字体。

#### 快捷操作 (Shortcuts)
- **快捷键**: `Ctrl + Shift + F` 快速切换字体。
- **右键菜单**: 右键点击页面 → Tampermonkey → 对应选项。

#### 状态说明 (Status)
| 按钮文字 | 状态说明 | 效果 |
|:---:|:---:|:---|
| Claude字体 | 已启用 | 使用衬线字体 + Claude主题色 |
| 默认字体 | 已关闭 | 使用系统默认字体 |

---

### 效果展示 (Effect Preview)

#### 字体变化 (Font Changes)
- **启用前**: 使用系统默认的无衬线字体（如Arial、微软雅黑），欢迎词显示为Google默认蓝色。
- **启用后**: 切换为优雅的衬线字体（Georgia、Times New Roman等），行高调整为1.7，阅读更舒适，欢迎词变为Claude主题橙色（#da7756）。

#### 保护元素 (Protected Elements)
脚本会智能保护以下元素不受影响：
- ✅ 所有按钮和控件
- ✅ 代码块和代码片段
- ✅ 图标和SVG元素
- ✅ 导航栏和工具栏
- ✅ 输入框和表单控件

---

### 设置说明 (Settings)

#### 自动保存 (Auto-save)
脚本会自动记住你的选择：
- 启用字体后，下次访问Gemini会自动应用。
- 关闭字体后，会保持默认状态。

#### 页面适应 (Page Adaptability)
- **SPA支持**: 支持Gemini的单页面应用架构。
- **自动检测**: 页面跳转时自动重新应用设置。
- **动态加载**: 支持内容动态加载的页面。

---

### 高级功能 (Advanced Features)

#### 多语言欢迎词支持 (Multi-language Welcome Support)
脚本支持识别以下语言的欢迎词并应用Claude主题色：
- **中文**: 你好、您好
- **英文**: Hi、Hello、Welcome
- **法文**: Bonjour
- **西班牙文**: Hola
- **意大利文**: Ciao
- **德文**: Guten Tag
- **日文**: こんにちは
- **韩文**: 안녕하세요

#### 响应式设计 (Responsive Design)
脚本支持不同屏幕尺寸：
- **桌面端**: 完整功能，按钮位于右上角。
- **移动端**: 按钮自动调整大小和位置。

---

### 故障排除 (Troubleshooting)

#### 常见问题 (FAQs)
**Q: 脚本没有生效怎么办？**
A:
1. 确认Tampermonkey已启用。
2. 检查脚本是否正确安装和启用。
3. 刷新Gemini页面重试。

**Q: 按钮没有显示？**
A:
1. 等待几秒钟让页面完全加载。
2. 检查是否被广告拦截器屏蔽。
3. 尝试刷新页面。

**Q: 字体没有变化？**
A:
1. 点击按钮确保状态为"Claude字体"。
2. 检查浏览器是否支持指定的字体。
3. 清除浏览器缓存后重试。

**Q: 欢迎词颜色没有改变？**
A:
1. 这是已知问题，需要页面结构配合。
2. 主要字体功能不受影响。
3. 后续版本会继续优化。

#### 兼容性 (Compatibility)
**支持的浏览器**:
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Edge 80+
- ✅ Safari 14+

**支持的系统**:
- ✅ Windows 10/11
- ✅ macOS 10.15+
- ✅ Linux (Ubuntu, CentOS等)

---

### 更新日志 (Changelog)

#### v1.5.0 (当前版本)
- ✨ 新增欢迎词Claude主题色功能。
-  支持多语言欢迎词识别。
-  优化DOM检测机制。
-  修复页面切换时的状态丢失问题。

#### v1.4.0
- ✨ 添加Claude官网字体支持。
-  优化按钮样式和位置。
- ⚡ 提升页面加载性能。

---

### 使用技巧 (Tips)

1. **最佳体验**: 建议在大屏幕设备上使用，字体效果更明显。
2. **护眼模式**: 配合浏览器的深色模式使用效果更佳。
3. **快捷切换**: 使用快捷键 `Ctrl + Shift + F` 可以快速切换。
4. **长文本阅读**: 启用后特别适合阅读AI生成的长回答。

---

### 技术支持 (Technical Support)

如果在使用过程中遇到问题：
1. **检查版本**: 确保使用的是v1.5.0版本。
2. **查看控制台**: 按F12打开开发者工具查看错误信息。
3. **重新安装**: 删除旧版本脚本，重新安装最新版本。
4. **清除数据**: 在Tampermonkey中重置脚本数据。

---

*最后更新: 2025年8月*
