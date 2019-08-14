---
layout: post
title:  PaletteSwap
category: Shader
description: 팔레트 스왑
---

<script src="/game/PaletteSwap/TemplateData/UnityProgress.js"></script>
<script src="/game/PaletteSwap/Build/UnityLoader.js"></script>
<script>
var gameInstance = UnityLoader.instantiate("gameContainer", "/game/PaletteSwap/Build/PaletteSwap.json", {onProgress: UnityProgress});
</script>
<div class="webgl-content">
<div id="gameContainer" style="width: 100%; height: 100%"></div>
<div class="footer">
<div class="webgl-logo"></div>
<div class="fullscreen" onclick="gameInstance.SetFullscreen(1)"></div>
<div class="title">PaletteSwap 1.0.0</div>
</div>


