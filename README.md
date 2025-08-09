---

### **Claude-Gemini-Style-Switch**
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

**中文：**
#### ✨ 主要功能
- **Claude官网字体**: 将页面字体替换为`ui-serif`等优雅衬线字体。
- **智能排除**: 自动排除按钮、图标等UI元素，保持界面美观。
- **代码字体保护**: 保持代码块的等宽字体不变。
- **欢迎词主题色**: 将"你好，用户名"等欢迎词改为Claude主题色。
- **多语言支持**: 支持中文、英文、法文、西班牙文等多种语言。
- **一键切换**: 随时开启/关闭字体效果。

####  界面元素
- **切换按钮**: 页面右上角的橙色圆角按钮。
- **提示信息**: 切换时显示的状态提示。
- **右键菜单**: 油猴右键菜单中的快捷命令。

**English:**
#### ✨ Key Features
- **Claude Official Font**: Replaces the page font with elegant serif fonts like `ui-serif`.
- **Smart Exclusion**: Automatically excludes UI elements such as buttons and icons to maintain a clean interface.
- **Code Font Protection**: Keeps the monospaced font for code blocks unchanged.
- **Welcome Message Theme**: Changes welcome messages like "Hello, [username]" to Claude's theme color.
- **Multi-language Support**: Supports various languages including Chinese, English, French, and Spanish.
- **One-click Toggle**: Easily enable or disable the font effect at any time.

####  UI Elements
- **Toggle Button**: An orange, rounded button in the top-right corner of the page.
- **Status Message**: Displays a status notification when the font is toggled.
- **Right-click Menu**: Provides quick commands in the Tampermonkey right-click menu.

---

### 使用方法 (How to Use)

**中文：**
#### 基本操作
1. **访问Gemini**: 打开 [https://gemini.google.com](https://gemini.google.com/)。
2. **查看按钮**: 页面右上角会出现一个橙色的"默认字体"按钮。
3. **启用字体**: 点击按钮切换为"Claude字体"。
4. **享受体验**: 页面字体立即切换为Claude官网同款字体。

#### 快捷操作
- **快捷键**: `Ctrl + Shift + F` 快速切换字体。
- **右键菜单**: 右键点击页面 → Tampermonkey → 对应选项。

#### 状态说明
| 按钮文字 | 状态说明 | 效果 |
|:---:|:---:|:---|
| Claude字体 | 已启用 | 使用衬线字体 + Claude主题色 |
| 默认字体 | 已关闭 | 使用系统默认字体 |

**English:**
#### Basic Usage
1. **Visit Gemini**: Open [https://gemini.google.com](https://gemini.google.com/).
2. **Check the Button**: An orange "Default Font" button will appear in the top-right corner.
3. **Enable Font**: Click the button to switch to "Claude Font".
4. **Enjoy the Experience**: The page font will immediately switch to the Claude official style.

#### Shortcuts
- **Hotkey**: Use `Ctrl + Shift + F` to quickly toggle the font.
- **Right-click Menu**: Right-click the page → Tampermonkey → Corresponding option.

#### Status Description
| Button Text | Status Description | Effect |
|:---:|:---:|:---|
| Claude Font | Enabled | Uses serif font + Claude theme color |
| Default Font | Disabled | Uses the system's default font |

---

### 效果展示 (Effect Preview)

**中文：**
#### 字体变化
- **启用前**: 使用系统默认的无衬线字体（如Arial、微软雅黑），欢迎词显示为Google默认蓝色。
- **启用后**: 切换为优雅的衬线字体（Georgia、Times New Roman等），行高调整为1.7，阅读更舒适，欢迎词变为Claude主题橙色（#da7756）。

#### 保护元素
脚本会智能保护以下元素不受影响：
- ✅ 所有按钮和控件
- ✅ 代码块和代码片段
- ✅ 图标和SVG元素
- ✅ 导航栏和工具栏
- ✅ 输入框和表单控件

**English:**
#### Font Changes
- **Before Enabling**: Uses the system's default sans-serif font (e.g., Arial, Microsoft YaHei), and the welcome message is Google's default blue.
- **After Enabling**: Switches to elegant serif fonts (Georgia, Times New Roman, etc.), the line height is adjusted to 1.7 for more comfortable reading, and the welcome message changes to Claude's theme orange (#da7756).

#### Protected Elements
The script intelligently protects the following elements from being affected:
- ✅ All buttons and controls
- ✅ Code blocks and snippets
- ✅ Icons and SVG elements
- ✅ Navigation bars and toolbars
- ✅ Input fields and form controls

---

### 设置说明 (Settings)

**中文：**
#### 自动保存
脚本会自动记住你的选择：
- 启用字体后，下次访问Gemini会自动应用。
- 关闭字体后，会保持默认状态。

#### 页面适应
- **SPA支持**: 支持Gemini的单页面应用架构。
- **自动检测**: 页面跳转时自动重新应用设置。
- **动态加载**: 支持内容动态加载的页面。

**English:**
#### Auto-save
The script automatically remembers your choice:
- After enabling the font, it will be automatically applied on your next visit to Gemini.
- If you turn it off, it will remain in the default state.

#### Page Adaptability
- **SPA Support**: The script supports Gemini's single-page application (SPA) architecture.
- **Auto-detection**: Settings are automatically reapplied when navigating between pages.
- **Dynamic Loading**: It supports pages with dynamically loaded content.

---

### 高级功能 (Advanced Features)

**中文：**
#### 多语言欢迎词支持
脚本支持识别以下语言的欢迎词并应用Claude主题色：
- **中文**: 你好、您好
- **英文**: Hi、Hello、Welcome
- **法文**: Bonjour
- **西班牙文**: Hola
- **意大利文**: Ciao
- **德文**: Guten Tag
- **日文**: こんにちは
- **韩文**: 안녕하세요

#### 响应式设计
脚本支持不同屏幕尺寸：
- **桌面端**: 完整功能，按钮位于右上角。
- **移动端**: 按钮自动调整大小和位置。

**English:**
#### Multi-language Welcome Message Support
The script recognizes welcome messages in the following languages and applies the Claude theme color:
- **Chinese**: 你好、您好
- **English**: Hi, Hello, Welcome
- **French**: Bonjour
- **Spanish**: Hola
- **Italian**: Ciao
- **German**: Guten Tag
- **Japanese**: こんにちは
- **Korean**: 안녕하세요

#### Responsive Design
The script supports various screen sizes:
- **Desktop**: Full functionality with the button located in the top-right corner.
- **Mobile**: The button automatically adjusts its size and position.

---

### 故障排除 (Troubleshooting)

**中文：**
#### 常见问题
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

#### 兼容性
**支持的浏览器**:
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Edge 80+
- ✅ Safari 14+

**支持的系统**:
- ✅ Windows 10/11
- ✅ macOS 10.15+
- ✅ Linux (Ubuntu, CentOS等)

**English:**
#### FAQs
**Q: What if the script isn't working?**
A:
1. Make sure Tampermonkey is enabled.
2. Check that the script is installed and active.
3. Refresh the Gemini page and try again.

**Q: The button isn't showing up?**
A:
1. Wait a few seconds for the page to fully load.
2. Check if an ad blocker is blocking it.
3. Try refreshing the page.

**Q: The font isn't changing?**
A:
1. Click the button to ensure the status is "Claude Font".
2. Check if your browser supports the specified fonts.
3. Try clearing your browser cache and retrying.

**Q: The welcome message color isn't changing?**
A:
1. This is a known issue related to the page's structure.
2. The main font feature is not affected.
3. We will continue to optimize this in future versions.

#### Compatibility
**Supported Browsers**:
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Edge 80+
- ✅ Safari 14+

**Supported Systems**:
- ✅ Windows 10/11
- ✅ macOS 10.15+
- ✅ Linux (Ubuntu, CentOS, etc.)

---

### 更新日志 (Changelog)

**中文：**
#### v1.5.0 (当前版本)
- ✨ 新增欢迎词Claude主题色功能。
-  支持多语言欢迎词识别。
-  优化DOM检测机制。
-  修复页面切换时的状态丢失问题。

#### v1.4.0
- ✨ 添加Claude官网字体支持。
-  优化按钮样式和位置。
- ⚡ 提升页面加载性能。

**English:**
#### v1.5.0 (Current Version)
- ✨ Added a feature to change the welcome message to Claude's theme color.
-  Supports multi-language welcome message recognition.
-  Optimized the DOM detection mechanism.
-  Fixed the issue of losing state when switching pages.

#### v1.4.0
- ✨ Added support for the Claude official font.
-  Optimized button style and position.
- ⚡ Improved page loading performance.

---

### 使用技巧 (Tips)

**中文：**
1. **最佳体验**: 建议在大屏幕设备上使用，字体效果更明显。
2. **护眼模式**: 配合浏览器的深色模式使用效果更佳。
3. **快捷切换**: 使用快捷键 `Ctrl + Shift + F` 可以快速切换。
4. **长文本阅读**: 启用后特别适合阅读AI生成的长回答。

**English:**
1. **Best Experience**: For the best visual effect, it is recommended to use the plugin on a large screen.
2. **Eye Protection Mode**: The effect is even better when used with your browser's dark mode.
3. **Quick Toggle**: Use the hotkey `Ctrl + Shift + F` to quickly switch fonts.
4. **Long Text Reading**: It's especially great for reading long AI-generated answers.

---

### 技术支持 (Technical Support)

**中文：**
如果在使用过程中遇到问题：
1. **检查版本**: 确保使用的是v1.5.0版本。
2. **查看控制台**: 按F12打开开发者工具查看错误信息。
3. **重新安装**: 删除旧版本脚本，重新安装最新版本。
4. **清除数据**: 在Tampermonkey中重置脚本数据。

**English:**
If you encounter any issues during use:
1. **Check the Version**: Make sure you are using version v1.5.0.
2. **Check the Console**: Press F12 to open the developer tools and check for any error messages.
3. **Reinstall**: Delete the old version of the script and reinstall the latest one.
4. **Clear Data**: Reset the script data in Tampermonkey.

---

*最后更新: 2025年8月*
*Last updated: August 2025*
