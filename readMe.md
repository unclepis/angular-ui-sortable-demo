# 工程说明
angular-ui-sortable demo,刚好项目上用到这个，要做一个自定义界面，组件根据排序自适应，随便写个demo看看怎么玩

# 依赖
需要jquery，jquery－ui和angularJs 1.3以上版本

# 布局说明
使用flex布局，左侧flex－direction按照column分布的上下结构，右侧使用flex－wrap让其铺满右侧空白区域

# 进展
目前只完成了简单拖拽排序，后续需要完善右侧div不能拖拽，左侧div可以拖拽排序，目前想到的办法就是在angular－ui－sortale提供的update，start,stop的回调函数中做逻辑处理；也想尝试一下draggable属性是否可用