2017-1-23 未发布
1、Table 组件修复当表格无数据时，并且有横向滚动条，表头下方也存在滚动条的bug  -- 已完成

2017-1-23 已发布
1、Table 组件优化复杂表头行合并时，会添加空行
2、Table 组件修复复杂表头非固定列没有 checkbox 的问题 #80
3、Table 组件合并单元格功能当设置了rowspan=1 和 colspan=1 则按照合并单元格处理

2017-1-16 已发布
1、Table 组件修复 checkbox 点击左上角位置偏移的 bug #82
2、Table 组件新增还原排序规则的方法 `resetOrder()` #81
3、Table 组件修复当表格配置了纵向自适应，出现横行滚动条的时候 ，横行滚动条高度会遮住最后一行表格 bug #79 #83
4、Table 组件修复横向滚动条没有显示完整的 bug #87
5、Table 组件修复自定义列通过 formatter 实现时，设置了overflowTitle 无效果的 bug #88


2017-12-19 已发布
1、Table 组件修复没有固定列时，分页数据无法回到顶部的bug
2、Table 组件修复复杂表头时，表头无checkbox bug
3、Table 组件新增取消选中当前行的方法 `clearCurrentRow()`

2017-12-18 已发布
1、table 组件 修复数据只有一条无法全选和取消全选的bug #65
2、table 组件 组件修复单击行样式数据变化后样不消失的bug #64

2017-12-12
1、table 组件 行单击事件名称由`on-row-click`改为`row-click`
2、table 组件 添加行双击击回调 `row-dblclick` #63
3、table 组件 添加表头单元格单击回调 `title-click`
4、table 组件 添加表头单元格双击回调 `title-dblclick`
5、table 组件 修复当有全选功能时，‘全不选择’没有触发回调的 bug #62
6、table 组件 优化当存在分页时，页码改变滚动条回到顶部

2017-12-4
1、table 组件支持通过设置属性sort-always允许排序只在升序和降序切换 #57
2、修复 table 组件 数据变化合并单元格样式错乱的问题 #60
3、修复 table 组件 固定左列偶尔无法触发滚动事件的bug
4、优化 table 组件 当有纵向自适应时并设置了最小高度时，表格内容高度小于‘最小高度’则以表格内容高度为准

2017-12-1
1、修复 table 组件左侧固定列绑定滚动事件失效的问题
2、优化 table 组件列滚动事件重复注册的问题
3、修复 table 组件 当 vue 路由切换导致列滚动事件失效的问题

2017-11-30
1、loading 效果位置优化，当有头部时，loading效果下移，否则垂直居中
2、loading 透明度允许外部传入，默认0.6（opacity）

2017-11-23 晚
1、修复 table 组件启用纵向自适应时会因为 document 有滚动条出现裂缝的bug

2017-11-23
1、优化 table 组件固定列时，固定列与非固定列之间有裂痕的问题

2017-11-22
1、修复 table 组件footer 汇总功能没有横向滚动条的bug
2、修复 table 组件自适应无滚动条的情况切换到小屏幕，有滚动条时，列没有自适应的bug



2017-11-21
1、新增 table 组件设置背景色功能
2、优化 table 组件行点击变色功能由状态管理形式改为状态管理与dom操作结合的形式（解决上万条数据行浮动卡顿、内存飙升的问题）
3、优化 table 组件行浮动变色功能由状态管理形式改为状态管理与dom操作结合的形式（解决上万条数据行浮动卡顿、内存飙升的问题）
4、优化 table 组件当没有checkbox 多选功能时关闭相关检查

2017-11-13
1、table 组件修复表格表框有缝隙的问题
2、table 组件高度未设置或者设置的高度大于实际表格高度时，表格高度自适应

2017-11-10
1、table 组件支持通过设置样式 `v-scrollbar-wrap` 订制滚动条样式

2017-11-9
1、table 组件天假属性`column-width-drag`控制是否打开列宽拖动功能
2、修复 table 组件列拖动结束后，页面元素无法选中的bug

2017-11-8
1、table 组件添加事件`on-custom-comp`实现子组件与父组件通讯的目的

2017-10-31
1、添加 [UMD](https://github.com/umdjs/umd) 版本，html 中可以直接通过 `<script>` 标签方式引入 #29 #22

2017-10-30

1、table组件支持 footer 汇总功能
2、修复table组件高度自适应会遮住最后一行内容的问题

2017-10-24
1、修复table组件单元格编辑后分页单元格内容不变化的问题 #24
2、废除单元格编辑格式化回调函数 `cell-edit-formatter`（破坏了响应式）
3、列宽拖动在IE9下失效的问题 #20
