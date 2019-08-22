---
layout: post
title:  SceneTransitions
category: Shader
description: 씬 전환 효과
---

<script src="/game/PaletteSwap/SceneTransitions/UnityProgress.js"></script>
<script src="/game/PaletteSwap/Build/UnityLoader.js"></script>
<script>
var gameInstance = UnityLoader.instantiate("gameContainer", "/game/SceneTransitions/Build/SceneTransitions.json", {onProgress: UnityProgress});
</script>
<div class="webgl-content">
<div id="gameContainer" style="width: 100%; height: 100%"></div>
<div class="footer">
<div class="webgl-logo"></div>
<div class="fullscreen" onclick="gameInstance.SetFullscreen(1)"></div>
<div class="title">SceneTransitions 1.0.0</div>
</div>



