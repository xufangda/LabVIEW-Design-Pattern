中介者模式 又叫调停者模式.

Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring toteach other explicitly, and it lets you vary theri interaction independently.

![before](http://incdn1.b0.upaiyun.com/2015/03/118de1e00034880d835a18c86ed4fda5.jpg)
![after](http://incdn1.b0.upaiyun.com/2015/03/c5bc6169f7d730306aa50f592754334e.jpg)

![mediator pattern](http://images.cnitblog.com/blog/449064/201411/072158245813715.jpg)

Mediator： 抽象中介者
Concrete Mediator: 具体中介者
Colleague: 同事角色

###优点
  - 减少类的依赖关系，把一对多的依赖关系，变为一对一的依赖关系。

###缺点
  - 中介者膨胀问题，原本的N个对象的相互依赖关系转换成为中介者与同事类的依赖关系。
  
  
