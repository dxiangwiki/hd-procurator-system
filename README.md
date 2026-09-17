# 汉东省人民检察院 案件信息查询系统 · 影视拍摄交互原型

> **版本：** 2026 · 作者：dxiangwiki
> **在线体验：** GitHub Pages / Netlify

---

## ⚠️ 重要免责声明

**本项目仅为影视剧拍摄仿真演示原型，全部内容均为虚构，不代表真实的检察、政法业务系统。**

- 所有案件、人名、账号、监控信息均来自电视剧《人民的名义》的剧情创作，无任何真实案件或人员信息；
- 严禁用于真实办案、伪造公文、电信诈骗、非法用途；
- 仅用于影视拍摄现场电脑屏幕实拍，替代传统静态图片 P 图，解决「演员操作鼠标画面不动、打字与屏幕不同步」等穿帮问题。

---

## 项目介绍

很多影视剧里的电脑屏幕画面，都是后期用静态图片 P 上去的，演员在现场点鼠标、敲键盘没有真实反馈，很容易穿帮。

这个原型是一个**真实可点击的网页系统**：演员在拍摄现场的电脑上打开页面，可以真实地点击按钮、输入查询、等待加载、弹出弹窗、切换菜单，镜头直接实拍屏幕原生画面，真实感大幅提升，还能减少后期合成工作量。

### 功能模块

| 模块 | 说明 |
| --- | --- |
| 干警登录 | 预填账号，点击登录进入系统 |
| 案件卷宗 | 案件列表，点击「查看卷宗」弹出立案决定书 |
| 嫌疑人档案 | 按姓名查询在案嫌疑人详细信息 |
| 出入境查询 | 输入姓名查询，带联查加载动画，调出出境记录 |
| 资金流水 | 涉案账户冻结状态 + 交易明细表格 |
| 监控调阅 | 点击画面加载监控录像（REC 标识 + 时间水印） |
| 法律文书 | 常用办案文书模板，点击查看弹窗 |

---

## 在线预览

- **GitHub Pages：** `https://dxiangwiki.github.io/hd-procurator-system/`
- **Netlify：** `https://hd-procurator-system.netlify.app`

---

## 本地运行

```bash
# 克隆仓库
git clone https://github.com/dxiangwiki/hd-procurator-system.git
cd hd-procurator-system

# 直接用浏览器打开，无需后端
open index.html   # macOS
# 或直接双击 index.html
```

---

## 部署教程

### GitHub Pages 部署

1. 在 GitHub 用户 `dxiangwiki` 下新建公开仓库 `hd-procurator-system`；
2. 上传 `index.html`、`README.md`、`LICENSE`、`.gitignore`；
3. 仓库 **Settings → Pages**，Source 选择 `main` 分支根目录，保存；
4. 等待 1~3 分钟自动生成在线地址。

### Netlify 部署

1. 登录 Netlify，选择 **Add new site → Import an existing project**；
2. 绑定 GitHub，授权选择 `hd-procurator-system` 仓库；
3. 直接部署，无需构建配置，自动生成 `https://hd-procurator-system.netlify.app`。

---

## License

MIT License，详见 [LICENSE](./LICENSE) 文件。仅供影视演示与学习使用。
