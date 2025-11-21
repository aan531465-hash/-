
# 自动统计 - 班级未上交统计小工具（GitHub Pages 部署）

部署说明：将仓库发布为 GitHub Pages（`main` 分支，根目录），即可获得在线访问地址：
`https://<你的GitHub用户名>.github.io/自动统计/`

使用步骤（快速）：
1. 在 GitHub 上新建仓库，仓库名填写 `自动统计`。
2. 将仓库设置为公开（Public）。
3. 上传 `index.html` 到仓库根目录（或将本 ZIP 解压并上传所有文件）。
4. 在仓库页面选择 Settings → Pages → Branch: `main`，Folder: `/ (root)`，保存。
5. 几分钟后访问 `https://<你的GitHub用户名>.github.io/自动统计/` 查看页面。

说明：页面中可上传任意班级名单（Excel，含姓名/学号），也可粘贴名单。支持姓名或学号匹配、多任务统计、下载未交名单。数据保存在浏览器 localStorage。

示例班级名单文件（已包含在本 ZIP）： `/mnt/data/4班名单.xlsx`
