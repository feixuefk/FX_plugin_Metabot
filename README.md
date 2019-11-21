# FX_plugin_Metabot
A Metabot which can help you

<h2>运行环境</h2>
<p>
AA 11.3.0</br>
.NET 4.6
<p>
<h2>版本更新</h2>

1.1.0</br>
新增9个方法：</br>
findWindow_Hwnd</br>
findWindow_AllHwnd</br>
setWindowTitle</br>
active_Window</br>
move_Window</br>
show_Window</br>
hide_Window</br>
top_Window</br>
notop_Window</br>
</p>

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

<tr><td>findWindow_Hwnd</td><td>获取匹配条件的窗口句柄</td><td>传参：class,title</td><td>class:窗口类名，title:窗口标题</td></tr>
<tr><td>findWindow_AllHwnd</td><td>获取所有匹配条件的窗口句柄</td><td>传参：class,title</td><td>class:窗口类名，title:窗口标题</td></tr>
<tr><td>setWindowTitle</td><td>设置窗口标题</td><td>传参：hwnd,title</td><td>hwnd:窗口句柄，title:窗口标题</td></tr>
<tr><td>active_Window</td><td>激活窗口</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
<tr><td>move_Window</td><td>移动窗口</td><td>hwnd,X,Y</td><td>hwnd:窗口句柄，X:屏幕X坐标，Y:屏幕Y坐标</td></tr>
<tr><td>show_Window</td><td>显示窗口</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
<tr><td>hide_Window</td><td>隐藏窗口</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
<tr><td>top_Window</td><td>窗口置顶</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
<tr><td>notop_Window</td><td>窗口不置顶</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
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
