# AMD_modules
###符合AMD规范的模块集

更新日志：
-------------

###2016-07-19：
		
		创建项目，两个模块
		[goto_top](#goto_top)：监听窗口滚动位置 → 决定是否显示“返回顶部按钮”；并监听按钮的点击事件 → 返回窗口到顶部。（不含样式）
		window_resize(#goto_top)：监听窗口的resize事件

<a name="goto_top"></a> ###goto_top：
		// button_selector: 按钮选择器
		return function(button_selector) {};

###window_resize：
		// callback: 回调
		return function(callback) {};
