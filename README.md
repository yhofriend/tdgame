# 暮光军团 · Twilight Legion（试玩版）

军团战争式（Legion-TD-like）1v1 对战塔防，浏览器里直接玩，不用安装。

**在线试玩：** https://yhofriend.github.io/tdgame/

- 电脑用 Chrome 或 Edge 打开最好。手机、平板也能玩（横屏、竖屏都可以，双指缩放），但还没在真机上大量测试，体验以电脑为准。
- 有显卡加速时是 3D 画面；没有时会自动换成 2D 画面（同一批模型预先渲染），开局时会提示一次。设置里的「画面」可以手动切换，「画质」调低会更流畅。
- 第一次打开要下载几十 MB 资源，请等进度条走完。
- 离线版：在 [Releases](https://github.com/yhofriend/tdgame/releases/latest) 下载 `twilight-legion.html`（约 56 MB），双击用 Chrome 或 Edge 打开，不需要联网。

## 怎么玩

备战阶段在自己的路线上摆兵、升级、合成，只用金币（每波收入加上本路的击杀赏金）。开战后暮生者从裂隙涌出，漏过防线的怪会去打你的王座，王座的圣坛会反击。谁的王座先倒下谁输；打完 20 波还没分出胜负，再来最多 3 波「暮光潮汐」，之后比王座剩余血量。

第一局开局已经替你摆好两个同种兵，亲手放下第三个，三个会一起亮起（集结），然后自动开战；第一次放出集结技能时，施放者脚下会亮出同一个标记。

## 操作

- 招募：把兵牌拖到格子上；或者点一下兵牌，再连续点空格，一次放好几个。兵牌上写着买下后会怎样，比如「再招 1 名 → 三名斥候都能弹射」。
- 撤销：备战时点底部的撤销按钮或按 Ctrl+Z，撤掉上一次招募，全额退钱。
- 详情和成长：备战时点自己的兵，详情显示在底部（暂时替换商店），「成长」里只列现在能做的升级、合成、进化。交战时点兵，只在它脚下标出，底部显示它的技能和冷却。
- 情报：交战时顶部只显示当前波、剩余敌人和王座血量；备战时显示下一波的弱点，点弱点会在商店里标出能克制它的兵。

0.4 版改的是界面（就是上面这些），规则和 0.3 相同。0.3 是精简规则的测试版：去掉了第二种资源、工人、国王升级、战术卡、秘契和佣兵，派兵会在之后的版本里以兵营的形式回来。

## 反馈

欢迎在本仓库的 Issues 里写下感受和遇到的问题：哪里好玩、哪里看不懂、哪里卡顿或出错。附上截图、浏览器和设备（电脑或手机型号）最有帮助。

---

Legion-TD-style 1v1 tower defense that runs in the browser. Play online: https://yhofriend.github.io/tdgame/ — or download twilight-legion.html from Releases and open it in desktop Chrome or Edge (offline, no install). 3D with GPU acceleration, otherwise an automatic 2D mode. Test build 0.4 reworks the interface: drag a card or tap it and then tap cells to recruit, undo with Ctrl+Z, unit details and growth in the bottom bar, and a first-match opening instead of a tutorial. Feedback welcome in Issues.
