* property 
	需要注意的几个事项 :
	* lazy 
	* ? / !
	* 命名

	顺序
	1. IBOutlet
	2. let
	3. lazy 
	4. 普通的属性
	5. 计算属性
	6. bool 值 用 is 打头 后面跟一个状态 或者 名词

* life circle 
	view controller life circle
	init / deinit

* notification 
 	* 通知的 命名要规范 具体规范再定 k + class name + method name
	* addNotification
	* removeNotification

* private method
	config UI
	fetch network data

* IBAction
	手势: didTaped 
	button: somethingBtnClicked

* datesource
	# tableView 中 需要 注意的是 如果能写成 属性的 就不要写在 datesource 中了
	
* delegate

* custom protocol 
	SegueHandlerType UIStoryboardSegue 的 id 太随意的 建议: push / pop / show 加 view controller class name


1. father VC / parent VC 这种写成代理吧
能用 let 用 let
能用 lazy 用 lazy
能不写 类型 就不写



