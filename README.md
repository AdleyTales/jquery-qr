# jquery生成二维码插件

## 效果如下
![](images/example.gif)

## 代码如下

```js

    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <title></title>
      </head>
      <body>

        <div id="qrcode"></div>
        <button id='btn'>点击</button>

        <script src="jquery.js"></script>
        <script src="jquery.qrcode.min.js"></script>
        <script>

            $('#btn').on('click',function(){
              $('#qrcode').qrcode("http://www.baidu.com");
            });
        </script>
      </body>
    </html>

```
