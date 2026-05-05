# 维什戴尔 Codex 宠物

这是给 Codex 浮动宠物 overlay 使用的自定义宠物包。角色名为 **维什戴尔**，整体是灰发、红黑恶魔角、橙黄色眼睛和小恶魔尾巴的 Q 版小恶魔少女，主色为黑、灰、红，适合小尺寸显示。

[English README](README.md)

## 预览

<p>
  <img src="media/vishdale-idle.gif" width="144" alt="维什戴尔待机动画" />
  <img src="media/vishdale-waving.gif" width="144" alt="维什戴尔挥手动画" />
  <img src="media/vishdale-jumping.gif" width="144" alt="维什戴尔跳跃动画" />
  <img src="media/vishdale-review.gif" width="144" alt="维什戴尔 review 动画" />
  <img src="media/vishdale-running.gif" width="144" alt="维什戴尔跑动动画" />
</p>

![维什戴尔动作总览](media/contact-sheet.png)

## 安装

把 `vishdale` 文件夹复制到：

```text
%USERPROFILE%\.codex\pets\vishdale
```

然后重启 Codex。如果没有自动切换，打开 Settings -> Appearance -> Pets，刷新自定义宠物列表，然后选择 **维什戴尔**。

自定义宠物 id 是：

```text
custom:vishdale
```

## 包内容

- `vishdale/pet.json` - Codex 宠物配置文件。
- `vishdale/spritesheet.webp` - 1536x1872 的宠物动作图集。
- `media/*.gif` - README 中使用的轻量动图预览。
- `media/contact-sheet.png` - 所有动作状态的图片总览。
- `qa/contact-sheet.png` - QA 用动作总览图。
- `qa/validation.json` - 图集校验结果。
- `qa/review.json` - 帧提取与审查结果。
- `source-assets-summary.json` - 源 GIF 与宠物动作状态的对应关系。

## 动作来源

- `idle`: `2.gif`
- `waiting`: `1.gif`
- `jumping`: `4.gif`
- `failed`: `6.gif`
- `review`: `3.gif`
- `running`: `5.gif`
- `running-right`、`running-left` 和 `waving` 沿用之前生成的宠物图集，因为它们更符合 Codex 对方向移动和挥手状态的需求。

## 说明

图集已按 Codex 宠物格式校验：8 列、9 行、每格 192x208 像素，未使用的格子保持透明。
