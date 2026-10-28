# sugarangel 复刻站

对 [sugarangel.neocities.org](https://sugarangel.neocities.org/) 的完整本地复刻——一个 kawaii / webcore 风格的个人主页。

## 页面

| 文件 | 内容 |
|---|---|
| `index.html` | 首页：标题动画、导航、欢迎语、FAQ、访客计数器、站点统计、更新日志、致谢、好友按钮跑马灯、DOG 守卫挂件 |
| `about.html` | 关于页：站长介绍、兴趣爱好、网页主人统计 |
| `newblog.html` | 博客页：4 篇日志（2023–2025） |
| `error.html` | 错误提示页 |

## 本地预览

```bash
cd sugarangel-site
python -m http.server 8899
# 浏览器打开 http://127.0.0.1:8899/index.html
```

也可以直接双击 `index.html` 打开，但外部小组件（计数器、webring 等）在 `file://` 协议下不会加载，推荐用上面的方式。

## 说明

- 全部素材（43 张图片 / GIF、4 套像素与手写字体、CSS、JS）已从原站下载并本地化，不依赖原站服务器，离线完整可用
- 保留了原站的视觉细节：粉色蝴蝶结平铺背景、奶油边框容器、自定义鼠标指针、旧式滚动条、像素字体
- 原站引用的两个 adilene.net webring 资源已失效，复刻版中已移除；FC2 计数器、imood 心情组件等改为 https 引用

## 版权

站内所有图片、字体、文案的版权归原站作者所有，此仓库仅供个人学习与技术参考。
