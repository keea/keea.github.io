---
layout: post
title:  PaletteSwap
category: Shader
description: 그래픽스 중간 과제
---

<script src="/game/NoEntry/TemplateData/UnityProgress.js"></script>
<script src="/game/NoEntry/Build/UnityLoader.js"></script>
<script>
var gameInstance = UnityLoader.instantiate("gameContainer", "/game/PaletteSwap/Build/web.json", {onProgress: UnityProgress});
</script>
<div class="webgl-content">
<div id="gameContainer" style="width: 100%; height: 100%"></div>
<div class="footer">
<div class="webgl-logo"></div>
<div class="fullscreen" onclick="gameInstance.SetFullscreen(1)"></div>
<div class="title">PaletteSwap 1.0.0</div>
</div>


