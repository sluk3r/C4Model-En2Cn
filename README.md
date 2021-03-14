## Introduction

Ask somebody in the building industry to visually communicate the architecture of a building and you'll be presented with site plans, floor plans, elevation views, cross-section views and detail drawings. In contrast, ask a software developer to communicate the software architecture of a software system using diagrams and you'll likely get a confused mess of boxes and lines ... inconsistent notation \(colour coding, shapes, line styles, etc\), ambiguous naming, unlabelled relationships, generic terminology, missing technology choices, mixed abstractions, etc.

怎么可视化地有效沟通？问建筑行业的的兄弟时，如果对方在正规一点公司的话，一般会聊到怎么使用Site Plan图、层平面设计图、正视图、横截面图和详细图纸。要是问软件行业兄弟的话， 与建筑行业相反的是，会得到一堆摸不着手脑的框框和线、含义混淆的标识、模糊的命名、没有标识的相互关系等等等等。

![](/assets/import.png)

As an industry, we do have the Unified Modeling Language \(UML\), ArchiMate and SysML, but asking whether these provide an effective way to communicate software architecture is often irrelevant because many teams have already thrown them out in favour of much simpler "boxes and lines" diagrams. Abandoning these modelling languages is one thing but, perhaps in the race for agility, many software development teams have lost the ability to communicate visually.

整个行业来看，我们有UML、ArchiMate和SysML， 不过，要是问问身边同事，上面的工具是不是给大家的软件工作带来沟通上的便利，得到的答案往往不乐观：很多团队早就不使用这么复杂的东东， 转而使用的更简单的”框框和线“。抛弃那些看似复杂的画图工具看着潇洒，不过，在崇尚敏捷高效的时代背景下，很多团队因没能图形化地沟通、产出效率一直提不起来。



### Maps of your code

The C4 model was created as a way to help software development teams describe and communicate software architecture, both during up-front design sessions and when retrospectively documenting an existing codebase. It's a way to create maps of your code, at various levels of detail, in the same way you would use something like Google Maps to zoom in and out of an area you are interested in.



**代码的导航图**

C4模型正是为了解决上面的两难选择而设计出来的，它可以帮助软件开发团队描述并沟通软件架构，在软件设计的前期和基于现在软件反向地汇总文档时都好使。 打个比方，

