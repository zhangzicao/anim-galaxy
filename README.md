# anim-galaxy
``` bash
基于canvas/css/img实现的一个星空动画。
```
[demo]( https://zhangzicao.github.io/anim-galaxy)

## 初始化
``` html
<div style="width: 1200px;height: 700px;position: relative;overflow: hidden;margin: 20px auto;">

    <div class="canvas-container">
      <canvas class="canvas-galaxy" id="galaxyCanvas" width="1200px" height="900px"></canvas>
      <div class="planet-wrap">
        <div class="planet planet-2"></div>
        <div class="planet planet-3"></div>
        <div class="planet planet-8"></div>
        <div class="planet planet-9"></div>
        <div class="planet planet-10"></div>
        <div class="planet planet-11"></div>
        <div class="planet planet-12"></div>
        <div class="planet planet-13"></div>
        <div class="planet planet-14"></div>
        <div class="planet planet-15"></div>
        <div class="planet planet-16"></div>
      </div>
      <canvas class="canvas-milky-way" id="galaxyMilkyWay" width="1200px" height="900px"></canvas>
      <div class="canvas-constellation-wrap">
        <canvas class="canvas-constellation" id="constellationCanvas" width="180" height="230"></canvas>
      </div>
      <div class="canvas-nebula-wrap">
        <div class="canvas-nebula-img"></div>
        <canvas class="canvas-nebula" id="nebulaCanvas" width="254" height="254"></canvas>
      </div>
      <canvas class="canvas-meteor" id="meteorCanvas"></canvas>
    </div>

</div>
```
``` javascript
renderGalaxy(document.getElementById('galaxyCanvas')) // 星空背景
renderMilkyWay(document.getElementById('galaxyMilkyWay')) // 星河
renderConstellation(document.getElementById('constellationCanvas')) //星座
nebulaAnim(document.getElementById('nebulaCanvas')) //黑洞
```

## 文档
[demo]( https://zhangzicao.github.io/anim-galaxy)
