# CCNU_Design Pattern
## CCNU_Course_Design Pattern  homework

+ **设计模式作业一**
  + 什么是用例？ 它有什么作用？  
  +  一个用例图包括哪些元素？这些元素间的关系有哪些类型？试解释这些关系，并举例说明（画出用例图）。  
  +  什么类？UML类图包括哪些部分？  
  +  类之间有哪些关系? 请分别举例说明。   



+ **设计模式作业二**
  + 好的系统设计应该具备哪些性质？试分别给出解释
  + 面向对象设计设计的原则有那些？它们是什么关系？
  + 什么是单一职责原则？试举例说明单一职责原则的优点
  + 什么是里氏代换原则？为什么说“子类可以扩展父类的功能，但不能改变父类原有的功能”？试举例说明
  + 什么是依赖倒置原则？试举例说明你对依赖倒置原则的理解。



+ **设计模式作业三**
  + 讨论：正方形是否是长方形的子类？（结合里氏代换原则）。
  + 合面向对象程序设计原则，谈谈对类和接口“粒度”的理解。
  + 有人将面向对象设计原则简单归为三类：
    +   封装变化点
    + 对接口进行编程
    + 多使用组合，而不是继承
  + 请查阅相关资料，结合本章的内容，谈谈对这三条原则的理解。



+ **设计模式作业四（设计模式概述）**
  + 设计模式有哪些优点？
  + 请查阅相关资料，了解在JDK类库设计中使用了哪些设计模式，在何处使用了何种模式？（至少2个）
  + 除了设计模式之外，目前有不少人在从事“反模式”的研究，请查阅相关资料，了解何谓“反模式”，以及研究“反模式”的意义。



+ **设计模式作业五（创建型模式一）**
  + 试画出简单工厂模式的模式结构图，并对模式进行分析。  
  + 试画出工厂方法模式的模式结构图，并对模式进行分析。  
  + 现需要设计一个程序来读取多种不同类型的图片格式，针对每一种图片格式都设计个图片读取器( ImageReader)，如GIF图片读取器( GifReader)用于读取GIF格式的图片、JPG图片读取器( Jpgreader)用于读取JPG格式的图片。图片读取器对象通过图片读取器工厂ImageReaderFactory来创建，ImageReaderFactory是一个抽象类，用于创建图片读取器的工厂方法，其子类 GifReaderFactory和  JpgReaderFactory用于创建具体的图片读取器对象。使用工厂方法模式实现该程序的设计。  
    + （画出模式结构图，并进行解析）  



+ **设计模式作业六（创建者模式二）**  

  + 试画出抽象工厂模式的模式结构图，并对模式进行分析。  

  + 试画出建造者模式的模式结构图，并对模式进行分析。

  + 计算机包括内存（RAM）,CPU等硬件设备，根据图中的”产品等级结构--产品族“示意图，使用抽象工厂模式实现计算机设备创建过程并绘制出相应的类图。

    + （画出模式结构图，并进行解析） 

      ![image](https://github.com/baobaotql/CCNU_DesignPattern/blob/master/课后题目/pic1.png)  



+ **设计模式作业七（创建者模式三）**
  + 设计一个客户类 Customer, 其中客户地址存储在地址类 Address中, 用浅克隆和深克隆分别实现 Customer对象的复制并比较这两种克隆方式的异同。绘制类图并编程实现。
  + 使用单例模式的思想实现多例模式，确保系统中某个类的对象只能存在有限个，如两个或三个，设计并编写代码实现一个多例类。  



+ **设计模式作业八（结构型模式一）**
  + 试画出适配器模式实例的结构图和实现代码，并对模式进行分析  

  + 试画出桥接模式实例的结构图和实现代码，并对模式进行分析  

  + 使用Java语言实现一个双向适配器实例，使得猫可以学狗叫，狗可以学猫抓老鼠，绘制相应类图并使用代码编程模拟    

    

+ **设计模式作业九（结构型模式二）**

  + 试画出组合模式实例的结构图和实现代码，并对模式进行分析  

  + 组合模式分为透明式的组合模式和安全式的组合模式  

  +  下图是某教育机构的组织结构图。在该教育机构的OA系统中可以给各级办公室下发公文，现采用组合模式设计该机构的结构，绘制相应的类图并编程模拟实现。在客户端 中模拟下发公文。  

    ![image](https://github.com/baobaotql/CCNU_DesignPattern/blob/master/课后题目/pic2.png)  




+ **设计模式作业十（结构型模式三）**  
  + 结合实例，绘制外观模式实例结构图（类图），用面向对象编程语言实现该模式，并对模式进行分析。  
  + 结合实例，绘制享元模式实例结构图（类图），用面向对象编程语言实现该模式，并对模式进行分析。  
  + 结合实例，绘制代理模式实例结构图（类图），用面向对象编程语言实现该模式，并对模式进行分析。
  + 应用软件所提供的桌面快捷方式是快速启动应用程序的代理。桌面快速方式一般使用一张小图片（Picture）来表示，通过调用快捷方式的run()方法将调用应用软件（Appication）的run方法。使用代理模式模拟该过程，试绘制类图并编程实现。  



+ **设计模式作业十一（行为型模式一）**

  + 结合实例，绘制责任链模式实例结构图（类图），用面向对象编程语言实现该模式，并对模式进行分析  

  + 结合实例，绘制命令模式实例结构图（类图），用面向对象编程语言实现该模式，并对模式进行分析。  

  + 在军队中,一般根据战争规模的大小和重要性由不同级别的长官( Officer)来下达作战命令,情报人员向上级递交军情(如敌人的数量),作战命令需要上级批准,如果直接上级不具备下达命令的权力,则上级又传给上级,直到有人可以决定为止。现使用职责链模式来模拟该过程,客户类Client)模拟情报人员,首先向级别最低的班长(Banzhang)递交任务书(Mission),即军情,如果超出班长的权力范围,则传递给排长(Paizhang),排长如果也不能处理,则传递给营长(Yingzhang),如果营长也不能处理,则需要开会讨论。  

    设置这几级长官的权力范围分别是：  

    + 敌人数量<10,班长下达作战命令  

    + 10≤敌人数量<50,排长下达作战命令  

    + 50≤敌人数量<200,营长下达作战命令  
    + 敌人数量≥200,需要开会讨论再下达作战命令  



+ **设计模式作业十二（行为型模式二）**
  + 结合实例，绘制迭代器模式实例结构图（类图），用面向对象编程语言实现该模式，并对模式进行分析  
  + 结合实例，绘制中介者模式实例结构图（类图），用面向对象编程语言实现该模式，并对模式进行分析  
  + 某教务管理系统中一个班级（Class）包含多个学生（Student）,使用Java内置的迭代器实现对学生信息的遍历，要求按学生的年龄由大到小的次序输出学生信息。用java语言模拟实现过程。    