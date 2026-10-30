# 2026 山西物理压轴题 · 3D 互动讲解

把 **2026 年高考物理陕晋青宁卷（山西）第 15 题** 做成了一个可以直接打开、也可以分享链接的 3D 互动网页。

> 在线访问：**__PAGES_URL__**

## 页面内容

- 可旋转、缩放、自动旋转的 3D 场景
- 三幕讲解：电场过孔 → 磁场折返 → 电压扫描
- 拖动电压 \(U\)，实时显示两条粒子轨迹、Q 反弹和 P 上撞击点
- 播放 / 暂停 / 拖动进度 / 分阶段跳转
- 桌面和手机自适应
- 完整题目、关键公式和参考答案

## 直接打开

下载或克隆仓库后，双击 `index.html` 即可离线打开；无需安装、无需构建，也没有 CDN 依赖。

## GitHub Pages

本仓库使用 GitHub Pages 直接从 `main` 分支根目录发布：

1. 打开仓库 **Settings → Pages**
2. Source 选择 **Deploy from a branch**
3. Branch 选择 **main**，目录选择 **/ (root)**
4. 保存后等待约 1 分钟

页面地址：

```text
https://<你的用户名>.github.io/shanxi-physics-3d/
```

`.nojekyll` 已包含，GitHub Pages 会按静态文件原样发布，不会经过 Jekyll 处理。

## 文件说明

```text
index.html   完整页面：HTML + CSS + 3D 引擎 + 交互逻辑，全部内联
cover.png    1200×630 分享封面图
.nojekyll    告诉 GitHub Pages 不要用 Jekyll 处理
README.md    本说明
```

`index.html` 是单文件应用，除分享封面外不需要其他资源。建议使用较新的 Chrome、Edge、Safari 或 Firefox。

## 题目与答案

- (1) \(\sin\theta = 3/5\) 或 \(4/5\)
- (2) \(y = 2L/5\) 或 \(4L/5\)
- (3)
  - \(U \ge 2mv_0^2/q\)：均无法打到 P 右侧
  - \(0<U<16mv_0^2/(17q)\) 或 \(U=2mv_0^2/q\)：1 个撞击点
  - \(16mv_0^2/(17q)<U<2mv_0^2/q\)：2 个撞击点

\(U=16mv_0^2/(17q)\) 为擦板临界；页面按“擦到即吸收”计为 1 个撞击点。

---

教学演示页面。原题版权归命题方。
