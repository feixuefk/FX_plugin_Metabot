# FX_plugin_Metabot
A Metabot which can help you

<h2>运行环境</h2>
<p>
AA 11.3.0</br>
.NET 4.6
<p>
<h2>版本</h2>
<p>首发版本号：</br>
1.0.0</br>
FX_Plugin_Metabot</p>

<h2>功能</h2>
<h4>Win_event类：</h4>
<table>
<thead>
<tr><th>接口</th><th>功能</th><th>传参</th><th>描述</th></tr>
</thead>
<tbody>
<tr><td>moveTo</td><td>鼠标移动</td><td>传参：X,Y</td><td>X:屏幕X坐标，Y:屏幕Y坐标</td></tr>
<tr><td>leftDwon</td><td>鼠标左键按下</td><td>无需参数</td><td></td></tr>
<tr><td>leftUp</td><td>鼠标左键弹起</td><td>无需参数</td><td></td></tr>
<tr><td>rightDwon</td><td>鼠标右键按下</td><td>无需参数</td><td></td></tr>
<tr><td>rightUp</td><td>鼠标右键弹起</td><td>无需参数</td><td></td></tr>
</tbody>
</table>

<h4>System类：</h4>

<table>
<thead>
<tr><th>接口</th><th>功能</th><th>传参</th><th>描述</th></tr>
</thead>
<tbody>
<tr><td>ChangeDisp</td><td>改变屏幕分辩率</td><td>传参：X,Y</td><td>X:屏幕分辨率X大小，Y:屏幕分辨率Y大小</td></tr>
<tr><td>getScreenWidth</td><td>获取屏幕分辨率宽度</td><td>无需参数</td><td></td></tr>
<tr><td>getScreenHeight</td><td>获取屏幕分辨率高度</td><td>无需参数</td><td></td></tr>
<tr><td>getScreenWH</td><td>获取屏幕分辨率宽度/高度</td><td>无需参数</td><td></td></tr>
</tbody>
</table>

<h4>Date类：</h4>
<table>
<thead>
<tr><th>接口</th><th>功能</th><th>传参</th><th>描述</th></tr>
</thead>
<tbody>
<tr><td>getNow</td><td>获取当前日期时间：YYYYMMDD HHMMSS</td><td>无需参数</td><td></td></tr>
<tr><td>getNowW</td><td>获取当前日期时间：YYYY/MM/DD HH:MM:SS</td><td>无需参数</td><td></td></tr>
<tr><td>getNowQ</td><td>获取当前日期时间：YYYY-MM-DD HH:MM:SS</td><td>无需参数</td><td></td></tr>
<tr><td>getTime_dot</td><td>获取当前时间：HH:MM:SS</td><td>无需参数</td><td></td></tr>
<tr><td>getTime</td><td>获取当前时间：HHMMSS</td><td>无需参数</td><td></td></tr>
<tr><td>getDate</td><td>获取当前日期：YYYYMMDD</td><td>无需参数</td><td></td></tr>
<tr><td>getDateW</td><td>获取当前日期：YYYY/MM/DD</td><td>无需参数</td><td></td></tr>
<tr><td>getDateQ</td><td>获取当前日期：YYYY-MM-DD</td><td>无需参数</td><td></td></tr>
</tbody>
</table>


