# FX_plugin_Metabot
A Metabot which can help you

<h2>运行环境</h2>
<p>
AA 11.3.0</br>
.NET 4.6</br>
Office Excel 2016</br>
<p>
  
<h2>版本更新</h2>

<p>2020年2月2日：v1.2.1</br>
新增：</br>
FindIEWindow</br>

<p>2019年12月05日：v1.2.0</br>
新增：</br>
Office Excel接口</br>
OpenXLS</br>
ReadCell</br>
WriteCell</br>
SaveChange</br>
SelectSheet</br>
QuitXLS</br>
</p>

<p>2019年12月03日：v1.1.1</br>
新增：</br>
NewDateOfFormat</br>
</p>

<p>2019年11月22日：v1.1.0</br>
新增：</br>
FindWindow_Hwnd</br>
FindWindow_AllHwnd</br>
SetWindowTitle</br>
Active_Window</br>
Move_Window</br>
Show_Window</br>
Hide_Window</br>
Top_Window</br>
Notop_Window</br>
</p>
<p>2019年11月14日：首发版本v1.0.0</br>
FX_Plugin_Metabot</p>

<h2>功能</h2>

<h4>Win_Event类：</h4>
<table>
<thead>
<tr><th>接口</th><th>功能</th><th>传参</th><th>描述</th></tr>
</thead>
<tbody>
<tr><td>MoveTo</td><td>鼠标移动</td><td>传参：X,Y</td><td>X:屏幕X坐标，Y:屏幕Y坐标</td></tr>
<tr><td>LeftDwon</td><td>鼠标左键按下</td><td>无需参数</td><td></td></tr>
<tr><td>LeftUp</td><td>鼠标左键弹起</td><td>无需参数</td><td></td></tr>
<tr><td>RightDwon</td><td>鼠标右键按下</td><td>无需参数</td><td></td></tr>
<tr><td>RightUp</td><td>鼠标右键弹起</td><td>无需参数</td><td></td></tr>
<tr><td>FindWindow_Hwnd</td><td>获取匹配条件的窗口句柄</td><td>传参：class,title</td><td>class:窗口类名，title:窗口标题</td></tr>
<tr><td>FindWindow_AllHwnd</td><td>获取所有匹配条件的窗口句柄</td><td>传参：class,title</td><td>class:窗口类名，title:窗口标题</td></tr>
<tr><td>SetWindowTitle</td><td>设置窗口标题</td><td>传参：hwnd,title</td><td>hwnd:窗口句柄，title:窗口标题</td></tr>
<tr><td>Active_Window</td><td>激活窗口</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
<tr><td>Move_Window</td><td>移动窗口</td><td>hwnd,X,Y</td><td>hwnd:窗口句柄，X:屏幕X坐标，Y:屏幕Y坐标</td></tr>
<tr><td>Show_Window</td><td>显示窗口</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
<tr><td>Hide_Window</td><td>隐藏窗口</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
<tr><td>Top_Window</td><td>窗口置顶</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
<tr><td>Notop_Window</td><td>窗口不置顶</td><td>传参：hwnd</td><td>hwnd:窗口句柄</td></tr>
<tr><td>FindIEWindow</td><td>获取IE内层窗口</td><td>传参：hwnd</td><td>hwnd:父窗口句柄</td></tr>
</tbody>
</table>

<h4>System类：</h4>
<table>
<thead>
<tr><th>接口</th><th>功能</th><th>传参</th><th>描述</th></tr>
</thead>
<tbody>
<tr><td>ChangeDisp</td><td>改变屏幕分辩率</td><td>传参：X,Y</td><td>X:屏幕分辨率X大小，Y:屏幕分辨率Y大小</td></tr>
<tr><td>GetScreenWidth</td><td>获取屏幕分辨率宽度</td><td>无需参数</td><td></td></tr>
<tr><td>GetScreenHeight</td><td>获取屏幕分辨率高度</td><td>无需参数</td><td></td></tr>
<tr><td>GetScreenWH</td><td>获取屏幕分辨率宽度/高度</td><td>无需参数</td><td></td></tr>
</tbody>
</table>

<h4>Date类：</h4>
<table>
<thead>
<tr><th>接口</th><th>功能</th><th>传参</th><th>描述</th></tr>
</thead>
<tbody>
<tr><td>NewDateofFormat</td><td>以指定方式返回当前时间,如：YYYYMMDD HHMMSS</td><td>s_style：输出格式</td><td>如：yyyy/MM/dd HH:mm:ss等</td></tr>
<tr><td>GetNow</td><td>获取当前日期时间：YYYYMMDD HHMMSS</td><td>无需参数</td><td></td></tr>
<tr><td>GetNowW</td><td>获取当前日期时间：YYYY/MM/DD HH:MM:SS</td><td>无需参数</td><td></td></tr>
<tr><td>GetNowQ</td><td>获取当前日期时间：YYYY-MM-DD HH:MM:SS</td><td>无需参数</td><td></td></tr>
<tr><td>GetTime_dot</td><td>获取当前时间：HH:MM:SS</td><td>无需参数</td><td></td></tr>
<tr><td>GetTime</td><td>获取当前时间：HHMMSS</td><td>无需参数</td><td></td></tr>
<tr><td>GetDate</td><td>获取当前日期：YYYYMMDD</td><td>无需参数</td><td></td></tr>
<tr><td>GetDateW</td><td>获取当前日期：YYYY/MM/DD</td><td>无需参数</td><td></td></tr>
<tr><td>GetDateQ</td><td>获取当前日期：YYYY-MM-DD</td><td>无需参数</td><td></td></tr>
</tbody>
</table>

<h4>Office Excel类：</h4>
<table>
<thead>
<tr><th>接口</th><th>功能</th><th>传参</th><th>描述</th></tr>
</thead>
<tbody>
<tr><td>OpenXLS</td><td>打开指定xls|xlsx文件</td><td>传参：path,visible</td><td>path:文件路径，visible：是否可见[0：不可见/1：可见]</td></tr>
<tr><td>SelectSheet</td><td>选择指定工作表</td><td>传参：sheetname</td><td>sheetname:工作表名</td></tr>
<tr><td>ReadCell</td><td>读取指定单元格</td><td>传参：row,column</td><td>row:行,column：列</td></tr>
<tr><td>WriteCell</td><td>写入指定单元格</td><td>传参：row,column,value</td><td>row:行,column：列,value:值</td></tr>
<tr><td>SaveChange</td><td>保存当前状态</td><td>无需参数</td><td></td></tr>
<tr><td>QuitXLS</td><td>退出已打开的xls|xlsx文件</td><td>无需参数</td><td></td></tr>
</tbody>
</table>
