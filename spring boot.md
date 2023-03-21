* [使用 initializer 快速创建项目](https://start.spring.io/)

# 依赖

在Spring框架中，依赖指的是一个类与其他类之间的关系。当一个类依赖于另一个类时，它需要使用另一个类的实例（对象）来执行某些操作。Spring框架通过依赖注入（Dependency Injection，简称DI）来管理和解决这些依赖关系，从而简化了开发人员处理复杂依赖关系的任务。

## Spring框架支持以下几种依赖注入方式：

1. 构造函数注入（Constructor Injection）：通过构造函数将依赖项传递给类的实例。这是一种不可变的注入方式，因为依赖项在对象创建时被设置，然后不能再更改。

2. Setter方法注入（Setter Injection）：通过使用setter方法将依赖项传递给类的实例。这是一种可变的注入方式，因为依赖项可以在对象创建后的任何时候更改。

3. 基于注解的注入：Spring支持使用注解（如@Autowired、@Resource等）来自动注入依赖项。这些注解可以与构造函数、setter方法或类属性一起使用，从而简化依赖注入的过程。

# 数据库

* Docker MySql