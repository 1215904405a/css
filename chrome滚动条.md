
## chrome 滚动条

::-webkit-scrollbar {

	width: 10px;/*竖向滚动条的宽度*/
	
	height: 10px;/*横向滚动条的高度*/
	
}

/*滚动条轨道的样式*/

::-webkit-scrollbar-track {

	-webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.3);
	
	-webkit-border-radius: 10px;
	
	border-radius: 10px;
	
}

/*滚动条轨道内滑块的样式*/

::-webkit-scrollbar-thumb {

	-webkit-border-radius: 10px;
	border-radius: 10px;
	background: rgba(155,155,155,0.8);
	-webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.5);
	
}

/*当焦点不在当前区域滑块的状态（具体为什么要加这句有点忘了，记得是跟刷新时有关）*/

::-webkit-scrollbar-thumb:window-inactive {

	background: rgba(155,155,155,0.4);
	
}
