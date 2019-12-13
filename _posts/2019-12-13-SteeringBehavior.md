---
layout: post
title:  SteeringBehavior
category: AI
description: 조정행동
---

<script src="/game/SteeringBehavior/TemplateData/UnityProgress.js"></script>
<script src="/game/SteeringBehavior/Build/UnityLoader.js"></script>
<script>
var gameInstance = UnityLoader.instantiate("gameContainer", "/game/SteeringBehavior/Build/SteeringBehavior.json", {onProgress: UnityProgress});
</script>
<div class="webgl-content">
<div id="gameContainer" style="width: 100%; height: 100%"></div>
<div class="footer">
<div class="webgl-logo"></div>
<div class="fullscreen" onclick="gameInstance.SetFullscreen(1)"></div>
<div class="title">SteeringBehavior 1.0.2</div>
</div>




