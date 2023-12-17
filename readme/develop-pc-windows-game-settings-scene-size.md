---
description: 在Unity开发游戏之前我们需要明确，开发的游戏将在什么平台上运行，需要根据游戏运行平台，设置游戏的场景大小，以便在对应的平台的可视区域内显示。
---

# 开发PC Windows游戏设置场景大小 - Develop PC Windows game settings scene size

比如在游戏中加入 UI 类型的Game Object有的带有`Canvas`父级Game Object，在`Canvas`的`Inspect`中有一个`Canvas Scaler`下有一个`UI Scale Mode`。此时你将需要选择`Scale with Screen Size` 缩放的时候需要一个参考分辨率。而参考分辨率就是最开始设置的分辨率大小，而分辨率最好是当前选择开发平台的最主流的分辨率。

### 配置步骤 - Configuration Steps

1. 找到叫Game的模块的标签，向右找到Display的下拉框旁，有Free Aspect的下拉框，点击下拉框。如果下来框中已经存在1920x1080那就点击此选项，需要确认宽为1920高为1080的配置。（Find the label of the module called Game. Go to the right and find the drop-down box of Free Aspect next to the Display drop-down box. Click on the drop-down box. If 1920x1080 already exists in the box, click this option. You need to confirm the configuration of width 1920 and height 1080.）
2. 如果没有1920x1080的选项，点击加号手动添加最好设置标题为1920x1080方便以后开发找到，设置宽度为1920且高度为1080，点击确定。（If there is no 1920x1080 option, click the plus to manually add it. It is best to set the title to 1920x1080 for later development to find it. Set the width to 1920 and the height to 1080, and click OK.）
