# 浏览器端使用js读取文件中全部字符串

```html
<html>
    <body>

        <input type="file" id="fileinput" />
        <div id="readResult"></div>

        <script type="text/javascript">
            function readSingleFile(evt) {
                //Retrieve the first (and only!) File from the FileList object
                var f = evt.target.files[0];

                if (f) {
                    var r = new FileReader();
                    r.onload = function (e) {
                        var contents = e.target.result;
						console.log(contents);
                        document.getElementById("readResult").innerHTML = contents;
                    }
                    r.readAsText(f);
                } else {
                    alert("Failed to load file");
                }
            }

            document.getElementById('fileinput').addEventListener('change', readSingleFile, false);

        </script>

    </body>
</html>
```





