# WebGL

- WebGL 1.0基于OpenGL ES 2.0
- WebGL 2.0基于OpenGL ES 3.0
- WebGL 2規範的發展始於2013年，並於2017年1月完成。該規範基於OpenGL ES 3.0。首度實作在Firefox 51、Chrome 56和Opera 43中
- OpenGL ES：OpenGL for Embedded Systems
- OpenGL：Open Graphics Library

index.html: 从canvas 2d开始
```html
<!DOCTYPE html>

<html>
  <head>
    <meta charset="utf-8" />
    <title>webgl</title>
    <style>
      * {
        margin: 0;
        padding: 0;
      }
    </style>
    <script src="https://cdn.bootcdn.net/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script type="text/javascript">
      $(() => {
        let canvas = $('#canvas1').get(0);
        let ctx = canvas.getContext('2d');
        ctx.fillStyle = 'rgba(0, 0, 255, 1.0)';
        ctx.fillRect(120, 10, 150, 150);
      });
    </script>
  </head>
  <body>
    <canvas id="canvas1" width="400" height="400" style="background-color: #e8e8e8;">
      Please use a browser that supports canvas tag
    </canvas>
  </body>
</html>
```

