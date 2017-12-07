# 工程说明
angular-ui-sortable demo,刚好项目上用到这个，要做一个自定义界面，组件根据排序自适应，随便写个demo看看怎么玩

# 依赖
需要jquery，jquery－ui和angularJs 1.3以上版本

# 布局说明
使用flex布局，左侧flex－direction按照column分布的上下结构，右侧使用flex－wrap让其铺满右侧空白区域

# 功能说明
1.左侧两颗树poleTree和normalTree可以通过左侧按钮控制切换隐藏出现，同时gis地图块可以自适应
2.树可以拖过拖拽在界面上自定义布局，由于业务需要，中间的gis地图只能在中间，树可以分在两侧或者在一侧按照上下布局或者隐藏
3.由于是demo，就随便写了一个controller，没有搞成组件，详细见代码备注