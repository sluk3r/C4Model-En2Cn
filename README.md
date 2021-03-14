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



虽说C4模型主要是帮助软件架构师和程序员，不过也可以帮助软件团队就软件架构问题高效沟通，不同层面上都可以、针对不同类型的听众讲不一样的侧重点，在软件开发初期或基于已有系统利用文档汇总时都能帮忙。



  
![](https://c4model.com/img/bigbankplc-SystemContext.png)

Level 1: A **System Context** diagram provides a starting point, showing how the software system in scope fits into the world around it.

第一级：系统

![](https://c4model.com/img/bigbankplc-Containers.png)

Level 2: A**Container**diagram zooms into the software system in scope, showing the high-level technical building blocks.

![](https://c4model.com/img/bigbankplc-Components.png)

Level 3: A**Component**diagram zooms into an individual container, showing the components inside it.

![](https://c4model.com/img/bigbankplc-Classes.png)

Level 4: A**code**\(e.g. UML class\) diagram can be used to zoom into an individual component, showing how that component is implemented.

[![](https://c4model.com/img/c4-overview.png "An overview of the C4 model")](https://c4model.com/img/c4-overview.png)

Different levels of zoom allow you to tell different stories to different audiences.

The C4 model is an "abstraction-first" approach to diagramming software architecture, based upon abstractions that reflect how software architects and developers think about and build software. The small set of abstractions and diagram types makes the C4 model easy to learn and use.



Abstractions
In order to create these maps of your code, we first need a common set of abstractions to create a ubiquitous language that we can use to describe the static structure of a software system. The C4 model considers the static structures of a software system in terms of containers, components and code. And people use the software systems that we build.

Abstractions

A software system is made up of one or more containers (web applications, mobile apps, desktop applications, databases, file systems, etc), each of which contains one or more components, which in turn are implemented by one or more code elements (e.g. classes, interfaces, objects, functions, etc).