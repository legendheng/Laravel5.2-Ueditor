# Laravel5.2-Ueditor
laravel5.2利用第三方库Ueditor引入编辑器
### 第一步、解压ueditor.rar压缩包，把文件放在项目的resources的org目录下
### 第二步、在前端页面引入以下js，注意（路径一定要写对）
```javascript
<script type="text/javascript" charset="utf-8" src="{{asset('resources/org/ueditor/ueditor.config.js')}}"></script>
<script type="text/javascript" charset="utf-8" src="{{asset('resources/org/ueditor/ueditor.all.min.js')}}"> </script>
<script type="text/javascript" charset="utf-8" src="{{asset('resources/org/ueditor/lang/zh-cn/zh-cn.js')}}"></script>
<script id="editor" name="art_content" type="text/plain" style="width:500px;height:200px;"></script>
<script type="text/javascript">
  var ue = UE.getEditor('editor');    //实例化，不能少
</script>
```
