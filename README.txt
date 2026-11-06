推这三样到 GitHub Pages 即可：
  index.html        （公开版，含章节锁与数据快照）
  hero-dark.mp4
  hero-light.mp4

推送：
  cd 这个目录
  git init && git add . && git commit -m "deploy"
  git branch -M main
  git remote add origin https://github.com/0603wangxiao/<仓库名>.git
  git push -u origin main

然后仓库 Settings → Pages → Source 选 main / (root)

注意：静态托管下没有 8899/8898 服务，
      页面用内嵌快照（asof 2026-11-04），不会实时更新。
