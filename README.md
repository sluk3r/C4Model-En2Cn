## Introduction

Ask somebody in the building industry to visually communicate the architecture of a building and you'll be presented with site plans, floor plans, elevation views, cross-section views and detail drawings. In contrast, ask a software developer to communicate the software architecture of a software system using diagrams and you'll likely get a confused mess of boxes and lines ... inconsistent notation \(colour coding, shapes, line styles, etc\), ambiguous naming, unlabelled relationships, generic terminology, missing technology choices, mixed abstractions, etc.

怎么可视化地有效沟通？问建筑行业的的兄弟时，如果对方在正规一点公司的话，一般会聊到怎么使用Site Plan图、层平面设计图、正视图、横截面图和详细图纸。要是问软件行业兄弟的话， 与建筑行业相反的是，会得到一堆摸不着手脑的框框和线、含义混淆的标识、模糊的命名、没有标识的相互关系等等等等。

![](https://c4model.com/img/sketch-1.jpg "A software architecture sketch")

![](https://c4model.com/img/sketch-2.jpg "A software architecture sketch")

![](https://c4model.com/img/sketch-3.jpg "A software architecture sketch")

![](https://c4model.com/img/sketch-4.jpg "A software architecture sketch")

As an industry, we do have the Unified Modeling Language \(UML\), ArchiMate and SysML, but asking whether these provide an effective way to communicate software architecture is often irrelevant because many teams have already thrown them out in favour of much simpler "boxes and lines" diagrams. Abandoning these modelling languages is one thing but, perhaps in the race for agility, many software development teams have lost the ability to communicate visually.

整个行业来看，我们有UML、ArchiMate和SysML， 不过，要是问问身边同事，上面的工具是不是给大家的软件工作带来沟通上的便利，得到的答案往往不乐观：很多团队早就不使用这么复杂的东东， 转而使用的更简单的”框框和线“。抛弃那些看似复杂的画图工具看着潇洒，不过，在崇尚敏捷高效的时代背景下，很多团队因没能图形化地沟通、产出效率一直提不起来。

### Maps of your code

The C4 model was created as a way to help software development teams describe and communicate software architecture, both during up-front design sessions and when retrospectively documenting an existing codebase. It's a way to create maps of your code, at various levels of detail, in the same way you would use something like Google Maps to zoom in and out of an area you are interested in.

**代码的导航图**

C4模型正是为了解决上面的两难选择而设计出来的，它可以帮助软件开发团队描述并沟通软件架构，在软件设计的前期和基于现在软件反向地汇总文档时都好使。 C4模型是创建代码的导航图， 可以提供不同层级的导航图。使用Google Maps体会下， 我们可以选中一个地区灵活地放大或缩小地查看。

就像源码一样，通过Google的街景视图， 我们可以看到很低级别的精确查看。

如果放大些的话，我们可方便地导航到一个陌生的地方。

再进一步放大的话，可以看到更多的周遭环境，而这一切以前咱可能没有意识到。

使用不同级别的视图，我们可以对不一样的听众说出不一样的故事。

![](https://c4model.com/img/map-1.jpg "Google Street View")

Like source code, Google Street View provides a very low-level and accurate view of a location.

![](https://c4model.com/img/map-2.jpg "Google Maps")

Navigating an unfamiliar environment becomes easier if you zoom out though.

![](https://c4model.com/img/map-3.jpg "Google Maps")

Zooming out further will provide additional context you might not have been aware of.

![](https://c4model.com/img/map-4.jpg "Google Maps")

Different levels of zoom allow you to tell different stories to different audiences.

Although primarily aimed at software architects and developers, the C4 model provides a way for software development teams to efficiently and effectively communicate their software architecture, at different levels of detail, telling different stories to different types of audience, when doing up front design or retrospectively documenting an existing codebase.

