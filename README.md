# bookmarks
以浏览器书签驱动的信息收集与导航 [Win软件 AI 开源项目 Web工具 炫酷网页 网盘资源 ...]  

<ul>{% for file in site.static_files %}{% if file.extname == ".html" %}
<li><a href="{{file.path | replace_first: '/', ''}}">{{file.path | replace_first: '/', ''}}</a></li>{% endif %}{% endfor %}
</ul>

请在你的浏览器中导入书签文件
