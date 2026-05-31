# 上线说明

这个项目是纯前端静态网站，直接托管 `index.html` 即可上线。

## 推荐方式：Netlify Drop

1. 打开 https://app.netlify.com/drop
2. 将整个项目文件夹拖进去
3. 等待生成公开访问链接

适合第一版验证，不需要写代码。

## 也可以使用 Vercel

1. 新建一个 Vercel 项目
2. 上传或导入这个文件夹
3. Framework 选择 Other
4. Build Command 留空
5. Output Directory 留空或填写 `.`

## 对外版本隐私边界

- 用户照片只在浏览器本地处理。
- 当前版本没有账号、没有云端存储、没有服务器图片上传。
- 刷新页面通常会保留浏览器本地暂存；清除浏览器缓存后可能丢失。
