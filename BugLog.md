# BugLog

|State|IssueID|Description|
|---|---|---|
|Fixed|ERRO2024072401|Dublicate组件时，实例中的组件未Dublicate，导致出现编辑蓝图中被Dublicate的组件的属性时，找不到实例中对应的组件，出现Null异常|
|Adopted|SUGG2024072601|组件监视器宽度在使用滚轮或者打字的时候不稳定|
|Fixed|ISSU2024072602|组件边框过大阻挡编辑视野|
|Fixed|ISSU2024072603|无法在选中组件上创建组件，需要使用鼠标功能才能取消选中|
|Fixed|ISSU2024072604|误删组件后使用CTRLz复原后误删的组件排序错误|
|Fixed|ISSU2024072605|组件监视器中无法将下面的组件排序至上面的组件下|
|Fixed|ISSU2024072606|组件监视器中无法将组件排序至最顶层|
|Fixed|ISSU2024073001|蓝图作者和项目作者后面的分号会随着保存打开越来越多|
|Fixed|ISSU2024080101|组件的变量不跟随组件复制一同复制|
|Fixed|ERRO2024080102|只要打开实例点一下编辑区域就卡退|
|Fixed|ISSU2024082601|文本组件不渲染生僻字，例如：“𬑡”|
|Fixed|ISSU2024090501|点进新建项目后没有返回键|
|Adopted|SUGG2024090502|输入新建项目名可以让其全选以便修改和删除|
||SUGG2024090601|可以设置更简便的使用教程，比方说插入箭头说明用途|
|Adopted|SUGG2024090602|同意条款一个用户或者一台设备只用同意一次就可以，不用每次都点同意（修改条款）|
|Adopted|SUGG2024090701|新建以后可以将下一步箭头改为文字版放在右下，箭头不明显|
|Adopted|SUGG2024090702|项目设置可以把左侧的栏目设为常驻，更加直观看出总概，更加方便进行卡牌设计|
|Adopted|SUGG2024090703|“标签组件”将“布局”放在相对靠前的位置|
||SUGG2024091101|添加`<hyperlink>`标签,悬浮预览卡片|
|Adopted|SUGG2024091401|左侧图标在光标移到时可以显示名称|
||SUGG2024091402|图标组件可以弄一个和文字组件一样的更明显的模拟表现|
|Adopted|SUGG2024092201|为表格导出成功添加提示|
|Fixed|ISSU2024092201|项目文件因为转移导致的异常，建议改为打开ezp文件后立即修改ProjecfLocation|
|Adopted|SUGG2024092301|Enter键结束键入组件名|
|Adopted|SUGG2024092601|预览从原来的渲染图片改为直接渲染控件，大体量控件集合改为虚拟化|
|Adopted|SUGG2024100101|侧边栏改为默认展开|
|Adopted|SUGG2024100102|蓝图编辑器卡牌视图默认处于中心|
|Adopted|SUGG2024100103|蓝图编辑器添加“展示边框”按钮|
||ISSU2024100101|组件树改为直接拖动排序|
|Adopted|SUGG2024100104|为文本添加对齐属性|
|Adopted|SUGG2024100201|添加软件级自动保存及恢复、异常退出检查|
||SUGG2024100301|组件自动吸附|
|Fixed|ERRO2024100401|双击创建组件发生bug|
|Fixed|ISSU2024100501|点击返回主页的按钮会弹出无关窗口|
||SUGG2024100601|完善导出页面，自动排版，保存到PNG或PDF，或直接发送到系统打印服务|
|Fixed|ISSU2024100901|EZML的`<br>`标签工作不正常|
|Fixed|ISSU2024101001|打印布局时即便页面刚好被占满还是会新建另一对空白页|
||ERRO2024101001|空引用异常 at EZcarddotNet.Widget.get_WidgetPath() in D:\Projects\EZcard\EZcarddotNet\EZcarddotNet\Classes\Widget.cs:line 768 at EZcarddotNet.Widget.IsChildOf(Widget child, Widget parent) in D:\Projects\EZcard\EZcarddotNet\EZcarddotNet\Classes\Widget.cs:line 1286|
||ERRO2024101002|空引用异常 at EZcarddotNet.Classes.ViewModels.BluePrintDesignerViewModel.HandleTreeRectMouseLeave(Widget widget) in D:\Projects\EZcard\EZcarddotNet\EZcarddotNet\Classes\ViewModels\BluePrintDesignerViewModel.cs:line 1119|
||SUGG2024101101|构造“快速EzCard设计语言（QED）”，用于读取并快速生成卡牌组件|
|Adopted|SUGG2024101701|图像资源改为相对路径|
|Adopted|SUGG2024101701|添加Ctrl+S保存快捷键|
||SUGG2024111901|为图像组件添加色相属性|
|Adopted|SUGG2024111902|组件添加“设为卡牌大小”|
||SUGG2024121801|为图像组件添加枚举属性，使属性可以快速在范围内的图像中单选|
||ISSU2024121801|自定义组件页面添加“删除组件”按钮|
||ISSU2024121802|为图像资源管理器添加“创建文件夹”按钮|
|Fixed|ISSU2024121803|蓝图库双击打开蓝图时，编辑器窗口不会自动置顶|
||SUGG2024121802|为示例编辑编辑器添加`ctrl`/`shift`的多选操作，以便同时编辑多个实例|
||SUGG2024121803|为实例视图添加“创建多个实例”按钮|
|Adopted|SUGG2024121804|将蓝图编辑器从底部移到左侧|
||SUGG2025010101|为文本内图标加入微调|

