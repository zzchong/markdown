# markdown
使用[Showdown](https://github.com/zzchong/markdown/tree/master/showdown-master "Showdown")来实现markdown 转 html

## 引入showdown
````
 <script type="text/javascript" src="../showdown-master/dist/showdown.min.js" ></script>
````

## 使用showdown
````
 <script type="text/javascript">
        function convert(){
            let text = document.getElementById("content").value;
            let converter = new showdown.Converter();
            document.getElementById("result").innerHTML = converter.makeHtml(text);
        }
    </script>
````

