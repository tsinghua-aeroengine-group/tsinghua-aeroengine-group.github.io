# 航空先进动力性能与稳定性课题组官网

这是清华大学航空发动机研究院“航空先进动力性能与稳定性课题组”的官方网站项目。网站基于 Hugo 与 Hugo Blox 构建，采用静态站点架构，内容清晰、加载快速、部署方便，也非常适合课题组长期维护与持续迭代。

当前网页已经围绕课题组展示进行了较完整的定制：整体宽度统一、浅绿与浅蓝的视觉风格克制舒适，中英文双语内容、研究成员、成果发表、活动相册、招募信息、联系方式、来访统计和网页编辑历史等模块都已形成较稳定的结构。

## 技术栈

- Hugo Extended：静态网站生成
- Hugo Blox：页面组件与主题基础
- Pagefind：站内搜索
- ClustrMaps 与 VerCount：来访地图和访问统计
- Markdown / HTML / SCSS：内容与样式维护

## 本地预览

```powershell
npm install
npm run dev
```

`npm run dev` 会先重新构建网站、刷新 Pagefind 搜索索引，然后启动 Hugo 本地预览服务。

## 正式构建

```powershell
npm run build
```

构建结果会输出到 `public/` 目录。

## 主要目录

| 路径 | 用途 |
| :--- | :--- |
| `content/_index.md` | 中文主页内容 |
| `content/_index.en.md` | 英文主页内容 |
| `content/members/` | 研究成员个人子页面 |
| `content/gallery/` | 活动相册子页面 |
| `content/history/` | 网页编辑历史页面 |
| `data/latest_research.yaml` | 最新研究文字信息 |
| `data/gallery.yaml` | 活动相册栏目配置 |
| `layouts/members/single.html` | 研究成员子页面模板 |
| `layouts/gallery/` | 活动相册页面模板 |
| `layouts/shortcodes/` | 最新研究、成果发表、活动相册等短代码 |
| `layouts/history/list.html` | 网页编辑历史页面模板 |
| `layouts/partials/achievements/` | 成果发表中英文内容 |
| `assets/scss/custom.scss` | 全站自定义样式 |
| `static/media/` | 网站图片与媒体资源 |
| `config/_default/` | Hugo 与 Hugo Blox 配置 |

## 图片放置约定

### 研究成员

- 成员主页头像：`static/media/members/`
- 成员个人页照片：`static/media/members/profiles/`

个人页面中的图片路径写在对应成员的 Markdown 文件中，例如：

```html
<img src="/media/members/profiles/ding-zechen.JPG" alt="丁泽琛" />
```

请注意文件名大小写，部署环境可能区分 `.jpg` 和 `.JPG`。

### 最新研究

最新研究图片放在：

```text
static/media/latest-research/研究编号/
```

例如：

```text
static/media/latest-research/202605-01/202605-01.png
```

文字信息维护在：

```text
data/latest_research.yaml
```

### 活动相册

每个相册对应一个文件夹：

```text
static/media/gallery/相册slug/
```

建议包含：

```text
cover.jpg
01.jpg
02.jpg
03.jpg
```

相册封面和标题配置维护在：

```text
data/gallery.yaml
```

相册子页面维护在：

```text
content/gallery/
```

## 内容维护提示

- 首页栏目主要在 `content/_index.md` 和 `content/_index.en.md` 中维护。
- 研究成员个人介绍在 `content/members/成员slug/index.md` 和 `index.en.md` 中维护。
- 成果发表内容在 `layouts/partials/achievements/zh.html` 和 `layouts/partials/achievements/en.html` 中维护。
- 样式微调优先查看 `assets/scss/custom.scss`，部分页面也有内联样式。
- 修改图片后如果预览没有更新，可以清理浏览器缓存，或删除 `resources/_gen/images/` 与 `public/` 后重新构建。

## 搜索说明

站内搜索使用 Pagefind。为了避免默认模板内容进入搜索结果，模板示例目录已通过构建配置禁用。中文搜索使用 Pagefind 的中文分词模式：

```json
"pagefind": "pagefind --site public --force-language zh"
```

## 项目特点

- 中英文双语展示，适合国际交流。
- 研究成员、成果发表、活动相册等学术团队核心内容结构清楚。
- 页面宽度和视觉语言统一，整体观感淡雅、稳定、专业。
- 静态网站无数据库依赖，维护成本低，部署可靠。
- 基于 Hugo 的内容组织方式非常适合科研团队长期积累成果与活动记录。

## 维护建议

每次较大修改后，建议执行：

```powershell
npm run build
```

确认无报错后再提交或部署。若只是日常预览，使用：

```powershell
npm run dev
```

这个网站已经从通用模板逐步打磨成一个有明确课题组气质的专业主页，后续只需要按既定目录补充内容和图片，就可以保持长期、稳定、漂亮地更新。
