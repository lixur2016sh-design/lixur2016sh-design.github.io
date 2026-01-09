
# mYi介 的兴趣空间（GitHub Pages 初始化包）

零基础部署步骤（约 3 分钟）：

## 1）创建仓库（用户主页形式，推荐）
- 登录 GitHub，新建公开仓库，名称必须是：`lixur2016sh-design.github.io`

## 2）上传文件
- 将此项目中的所有文件上传到仓库的根目录（index.html / styles.css / assets / README.md）。

## 3）启用 GitHub Pages
- 进入仓库 **Settings → Pages**
- **Build and deployment** 中，Source 选择 **Deploy from a branch**
- Branch 选择主分支（如 `main`），文件夹路径选择 `/root`
- 保存后等待 1–3 分钟，访问站点：`https://lixur2016sh-design.github.io`

## 4）常用自定义
- 替换 `assets/` 里的图片（头像、兴趣卡片、相册、cover）
- 在 `index.html` 中更新社交链接（邮箱/微博/B站等）
- 如需自定义域名：仓库根目录新增 `CNAME` 文件，内容写你的域名，如 `example.com`

## 目录结构
```
index.html
styles.css
assets/
  avatar.jpg
  interest_photography.jpg
  interest_music.jpg
  interest_travel.jpg
  interest_diy.jpg
  gallery_1.jpg ... gallery_5.jpg
  cover.jpg
```
