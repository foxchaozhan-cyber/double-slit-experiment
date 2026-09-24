# Physics Lab · 物理实验室

Interactive physics pages for middle school students. Each page is a single self-contained HTML file: open it in any modern browser, no build or install needed. Start from `index.html`; the bar at the top links to the other experiments.

| Page | File |
| --- | --- |
| The Double-Slit Mystery | `index.html` |
| 卫星为什么不会掉下来？ | `gravity-orbit/index.html` |

## The Double-Slit Mystery

An interactive animation that explains the double-slit experiment to middle school students.
It is a single file, `index.html`. Open it in any modern browser; you don't need to build or install anything.

The lesson has four steps. Before each result is shown, students predict what they think will happen:

1. **Marbles** – particles make two stripes.
2. **Water waves** – waves interfere and make many stripes.
3. **Electrons, one at a time** – each electron lands as a single dot, but together the dots build up interference stripes.
4. **Take a peek** – turn on a detector at the slits and the stripes disappear.

Below the animation there is a short "what it means" section, a timeline of real experiments, a glossary, and discussion questions for teachers.
The patterns are simplified to make them clear.

## 卫星为什么不会掉下来？

`gravity-orbit/index.html` 是中文页面。地球在画面中央，小球从地面以上 1000 km 处水平发射。学生先调整初速度、猜结果（落回地球 / 绕地球飞 / 飞离地球），再发射验证。

- 轨迹用二维牛顿万有引力模型逐步计算（速度 Verlet 积分），不是预设动画。
- 画面显示黄色轨迹、蓝色速度箭头和橙色引力箭头（指向地心），旧轨迹变淡保留，方便对比。
- 页面上写明了简化假设：二维、忽略大气阻力、地球不动不自转、只考虑地球引力、时间加速。
- 这个高度的关键速度：约 7.08 km/s 以下撞地，约 7.35 km/s 为圆轨道，约 10.40 km/s 以上逃逸。
