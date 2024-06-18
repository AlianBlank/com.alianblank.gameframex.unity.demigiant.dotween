# Unity的DoTween 动画插件

该库主要服务于 `https://github.com/AlianBlank/GameFrameX` 作为子库使用。

# 使用方式(三种方式)

1. 直接在 `manifest.json` 文件中添加以下内容
   ```json
      {"com.gameframex.unity.demigiant.dotween": "https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git"}
    ```
2. 在Unity 的`Packages Manager` 中使用`Git URL` 的方式添加库,地址为：https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git

3. 直接下载仓库放置到Unity 项目的`Packages` 目录下。会自动加载识别

# 改动功能

1. 增加 `link.xml` 的裁剪过滤

# 文档

http://dotween.demigiant.com/documentation.php

# 以下为原内容

DOTween and DOTween Pro are copyright (c) 2014-2018 Daniele Giardini - Demigiant

// IMPORTANT!!! /////////////////////////////////////////////
// Upgrading DOTween from versions older than 1.2.000 ///////
// (or DOTween Pro older than 1.0.000) //////////////////////
-------------------------------------------------------------
If you're upgrading your project from a version of DOTween older than 1.2.000 (or DOTween Pro older than 1.0.000) please follow these instructions carefully.

1) Import the new version in the same folder as the previous one, overwriting old files. A lot of errors will appear but don't worry
2) Close and reopen Unity (and your project). This is fundamental: skipping this step will cause a bloodbath
3) Open DOTween's Utility Panel (Tools > Demigiant > DOTween Utility Panel) if it doesn't open automatically, then press "Setup DOTween...": this will run the upgrade setup
4) From the Add/Remove Modules panel that opens, activate/deactivate Modules for Unity systems and for external assets (Pro version only)

// GET STARTED //////////////////////////////////////////////

- After importing a new DOTween update, select DOTween's Utility Panel from the "Tools/Demigiant" menu (if it doesn't open automatically) and press the "Setup DOTween..." button to activate/deactivate Modules. You can also access a Preferences Tab from there to choose default settings for DOTween.
- In your code, add "using DG.Tweening" to each class where you want to use DOTween.
- You're ready to tween. Check out the links below for full documentation and license info.

// LINKS ///////////////////////////////////////////////////////

DOTween website (documentation, examples, etc): http://dotween.demigiant.com
DOTween license: http://dotween.demigiant.com/license.php
DOTween repository (Google Code): https://code.google.com/p/dotween/
Demigiant website (documentation, examples, etc): http://www.demigiant.com

// NOTES //////////////////////////////////////////////////////

- DOTween's Utility Panel can be found under "Tools > Demigiant > DOTween Utility Panel" and also contains other useful options, plus a tab to set DOTween's preferences
