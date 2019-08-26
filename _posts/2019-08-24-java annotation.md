---
layout: post
title: Java注解
tags: Class 对象
categories: Java
---

# Java注解
一切皆对象   类类型   
Class类，任何类都是Class类的对象    
编译和运行 
编译时刻加载类：静态加载类   
new 创建对象是静态加载类，在编译时刻就需要加载所有可能使用到的类。  
运行时刻加载类：动态加载类    
动态加载 Class c = Class.forName  在运行时刻加载 c.newInstance() 通过类类型创建对象  
功能性类可考虑使用动态加载   
涉及类Method、Field、Constructor等

方法的反射操作   
方法的名称和方法的参数唯一确定一个方法   
method.invoke(对象，参数列表)   

Java反射-泛型   
反射的操作都是编译之后的操作    
编译之后集合的泛型是去泛型化的   
集合的泛型只在编译阶段有效，由于防止输入错误    

## 参考：
https://www.imooc.com/learn/199
