## 软件流程中的“图”

  1. 图，是一种模型的阐述；是理清复杂关系的有效方法。
  2. [软件工程中的各种图](http://www.tuicool.com/articles/b26JRj)
    * 静态模型图：类图、对象图、包图、组件图、部署图。
    * 动态模型图：用例图、时序图、协作图、状态图、活动图。
  3. [软件工程中的图](http://www.cnblogs.com/bukudekong/archive/2012/05/05/2484498.html)

### 需求设计

  1. 业务流程图

  2.

### 产品设计


### 软件设计 （这样的分类，并不好，要修正@fallenink）（或者：流程图、对象关系图？哎，也不好）

  1. 泳道图 (Swimlane Flowcharts)

  2. 用例图（用例过程图，用例模型图？）
    * 也被称为用户模型图，是从软件的需求分析的到最终实现的第一步，它是从客户角度来描述系统功能的。它包含三个基本组件：参与者 ( 使用系统的人或事物 ) 、用例 ( 代表系统的某项完整的功能，在图形中使用椭圆型表示 ) 、关系 ( 泛化关系、扩展关系、包含关系 ) 。

  3. 对象图
    * 对象图是类图的实例，用于显示系统执行时的一个可能的快照。即在某一个时间系统上可能出现的样子，对象图用带有下滑线的对象名称表示对象。

  3. 类图
    * 类图是面向对象系统建模中最常用的，也是定义其他图的基础。它主要是用来显示系统中的类，接口及他们之间的关系。类图中包含的主要元素有类、接口、和关系。其中的 关系有关联关系、泛化关系、依赖关系、实现关系 。在类图中也可以包含注释和约束。

  4. 数据流图

  5. 调用关系图

  6. 程序流程图

  7. 时序图
    * * 时序图用于描述对象之间的传递信息的时间顺序。即用例中的行为顺序。当执行一个用例时，时序图中的每一条消息对应了一个类中操作或者引起转换的触发事件。时序图是一个而微大关系图。纵轴表示时间时间轴向下延伸。横轴代表协作中的各个独立对象。对象存在时。消息用从一个对象的生命线到另个对象的生命线的箭头表示。箭头以时间的顺序在图中上下排列。

  8. 活动图
    * 活动图本质上就是流程图。它用于描述系统的活动，判定点和分支等。活动中的动作状态，原子的、不可已中断的动作。并在此动作完成后向另一个动作转变。分支与合并。分支在软件系统中很常见：用于表示对象类具有的条件行为。用一个布尔型的表达式真假来判定动作的流向，合并有两个如转换一个出转换。分支有一个如转换两个出转换。分叉与汇合：分叉又来描述并发线程。每个分叉可以有一个输入的转换和两个或多个输出转换。汇合代表两个或多个并发控制流的同步发生。当所有流都到达汇合点后，程序才能继续前进。泳道：泳道将活动图中的活动划分为若干组。并将每一组指定给负责这组活动的业务组织。在活动图中，泳道使用垂直的实线绘制。

  9. 状态图
    * 状态图包括状态、转换、初始状态、终止状态。

  10. 协作图
    * 也叫做合作图，是一种交互图。时序图主要侧重于对象之间的消息传递在时间上的先后关系。而协作图表达对象之间的交互过程及对象之间的关联关系。    

  15. 组件图
    * 8. 组件图：组件图用来建立系统中各种组件之间的关系。各个组件通过功能组织在一起。 JavaBean ， ejb ， jsp 都是组件。在 UML 中，组件使用左侧有两个小矩形的矩形来表示。 组件图用来设计系统的整个架构。

  16. 包图
    * 由包与包之间的关系组成，包的图标就如同一个带标签的文件夹。

  17. 部署图
    * 部署图是用来帮助开发者了解软件中各种组件驻留在什么硬件位置，以及这些硬件之间的相互关系。

### 测试


???
