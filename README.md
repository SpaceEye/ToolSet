# ToolsSet — 在线工具集 🎨

一套自包含的在线工具集，所有页面均为单个 HTML+CSS+JS 文件，无需外部依赖，可直接通过本地 HTTP 服务器访问。

---

## 🚀 访问地址

- **主页**: http://localhost:8081/index.html
- **局域网访问**: http://192.168.3.76:8081/

---

## 📋 可用工具

### 🎨 颜色与设计工具

| 工具 | 描述 |
|------|------|
| [颜色转换器](color-converter.html) | HEX、RGB、RGBA、HSL、HSLA 格式互转 |
| [色轮选择器](color-wheel.html) | 可视化色轮拖拽取色 |
| [对比度检查](contrast-checker.html) | 前后景色对比度与 WCAG 等级 |
| [渐变生成器](gradient-generator.html) | 创建 CSS 渐变并复制代码 |
| [互补色生成器](complementary-colors.html) | 互补、三角色等配色方案 |
| [配色理论](color-theory.html) | 配色方案与色彩理论速查 |

### 💻 编程辅助工具

| 工具 | 描述 |
|------|------|
| [JSON 格式化器](json-formatter.html) | JSON 格式化 / 压缩 / 校验 |
| [Base64 编解码器](base64.html) | Base64 编码 / 解码 |
| [URL 编解码器](url-encoder.html) | URL encode / decode |
| [时间戳转换器](timestamp-converter.html) | Unix 时间戳与日期互转 |
| [正则表达式测试器](regex-tester.html) | 实时正则匹配测试 |
| [哈希生成器](hash-generator.html) | SHA-1/256/384/512 哈希计算 |
| [UUID 生成器](uuid-generator.html) | 批量生成 v4 UUID |
| [字符串大小写转换](case-converter.html) | 8 种命名风格互转 |
| [进制转换器](radix-converter.html) | 二 / 八 / 十 / 十六进制互转 |
| [文本对比工具](diff-compare.html) | 行级 Diff 对比 |
| [Markdown 预览器](markdown-preview.html) | Markdown 实时渲染 |
| [JWT 解码器](jwt-decoder.html) | 解析 JWT 的 header / payload |
| [Cron 表达式解析器](cron-parser.html) | 解析 cron 并计算执行时间 |

### 🧰 网络与安全工具

| 工具 | 描述 |
|------|------|
| [HTML 实体编码/解码器](html-entities.html) | HTML 实体与字符互转 |
| [IP 地址计算器](ip-calculator.html) | 根据 CIDR 计算网络信息 |
| [密码生成器](password-generator.html) | 安全随机密码生成 |

### 🛠️ 开发者与设计工具

| 工具 | 描述 |
|------|------|
| [CSS 单位转换器](css-units.html) | px / rem / em / vw / vh 等互转 |
| [QR 二维码生成器](qrcode-generator.html) | 文本/URL 生成二维码图片 |
| [占位图片生成器](placeholder-image.html) | 生成带尺寸标注的占位图 |
| [代码片段格式化](code-formatter.html) | 简单代码缩进美化 |
| [CSV/表格转换器](csv-converter.html) | CSV、JSON、表格互转 |
| [单位换算器](unit-converter.html) | 长度/重量/温度/数据等多单位换算 |

### 📐 数学与几何工具

| 工具 | 描述 |
|------|------|
| [二维变换可视化](transform-2d.html) | 旋转/缩放/错切/平移实时可视化 + 变换矩阵 |
| [三维变换可视化](transform-3d.html) | 3D 旋转、透视投影、拖拽轨道观察 |
| [空间向量计算器](vector-calculator.html) | 点积/叉积/模长/夹角/垂直共线判定 |
| [几何计算器](geometry-calculator.html) | 16 种平面/立体图形面积体积公式计算 |

### 🎮 游戏工具箱

| 工具 | 描述 |
|------|------|
| [Minecraft 经验计算器](mc-xp-calculator.html) | 升级经验计算 + 1-50 级附魔 XP 表 |
| [红石时钟计算器](mc-redstone-clock.html) | 比较器数量 → 循环周期/频率 |
| [LOL KDA 计算器](lol-kda.html) | 击杀/死亡/助攻比值 |
| [技能冷却计算器](lol-cdr.html) | 基础 CD × 冷却缩减 |
| [Valorant 跨射伤量分析](valorant-penetration.html) | 穿墙伤害衰减与击杀判断 |
| [Valorant 经济计算器](valorant-economy.html) | 下一回合资金预测 |
| [FPS 准星生成器](crosshair-generator.html) | 自定义参数生成 SVG 准星 |
| [T 级排行榜编辑器](tier-list-editor.html) | T0-T5 角色分级，导出文本 |
| [游戏工具箱（合集）](gaming-tools.html) | 以上工具的合集页（保留兼容） |

---

## 📁 文件结构

```
ToolsSet/
├── index.html                  # 工具集主页
├── base64.html                 # Base64 编解码器
├── case-converter.html         # 字符串大小写转换
├── code-formatter.html         # 代码片段格式化
├── color-converter.html        # 颜色转换器
├── color-theory.html           # 配色理论
├── color-wheel.html            # 色轮选择器
├── complementary-colors.html   # 互补色生成器
├── contrast-checker.html       # 对比度检查
├── crosshair-generator.html    # FPS 准星生成器
├── cron-parser.html            # Cron 表达式解析器
├── css-units.html              # CSS 单位转换器
├── csv-converter.html          # CSV/表格转换器
├── diff-compare.html           # 文本对比工具
├── geometry-calculator.html    # 几何计算器（面积/体积）
├── gaming-tools.html           # 游戏小工具（骰子/轮盘等）
├── gradient-generator.html     # 渐变生成器
├── hash-generator.html         # 哈希生成器
├── html-entities.html          # HTML 实体编码/解码器
├── ip-calculator.html          # IP 地址计算器
├── json-formatter.html         # JSON 格式化器
├── jwt-decoder.html            # JWT 解码器
├── lol-cdr.html                # 技能冷却计算器
├── lol-kda.html                # LOL KDA 计算器
├── markdown-preview.html       # Markdown 预览器
├── mc-redstone-clock.html      # 红石时钟计算器
├── mc-xp-calculator.html       # Minecraft 经验计算器
├── password-generator.html     # 密码生成器
├── placeholder-image.html      # 占位图片生成器
├── qrcode-generator.html       # QR 二维码生成器
├── radix-converter.html        # 进制转换器
├── regex-tester.html           # 正则表达式测试器
├── tier-list-editor.html       # T 级排行榜编辑器
├── timestamp-converter.html    # 时间戳转换器
├── transform-2d.html           # 二维变换可视化
├── transform-3d.html           # 三维变换可视化
├── unit-converter.html         # 单位换算器
├── url-encoder.html            # URL 编解码器
├── valorant-economy.html       # Valorant 经济计算器
├── valorant-penetration.html   # Valorant 跨射伤量分析
├── uuid-generator.html         # UUID 生成器
├── vector-calculator.html      # 空间向量计算器
├── hex-converter.py            # 命令行进制转换小工具（独立脚本）
├── .gitignore
└── README.md                   # 本说明文档
```

所有 HTML 工具页均为自包含单文件；`hex-converter.py` 是对应的命令行版本，可单独运行 `python3 hex-converter.py --help`。

---

## 🛠️ 本地启动

```bash
cd /home/hermes/ToolsSet
python3 -m http.server 8081 --directory /home/hermes/ToolsSet
```

（静态站无构建步骤，任意 HTTP 服务器指向本目录即可，如 `nginx root` 或 `python3 -m http.server`。）

---

## 📄 License

MIT — 免费用于个人和商业项目。
