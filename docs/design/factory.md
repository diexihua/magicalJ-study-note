# 工厂模式

- 将 `new` 操作单独封装
- 遇到 `new` 时，就要考虑是否该用工厂模式

## 示例

你去购买汉堡，直接点餐、取餐，不会自己亲手做，商店要“封装”做汉堡的工作，做好直接给买者

## 场景

- jquery：$(`div`)
- React.createElement
- vue 异步组件

### jquery

$(`div`) 和 new $(`div`) 有何区别？

1. 书写麻烦，链式操作将成为噩梦
2. 一旦jquery名字变化，将是灾难性的

阅读经典lib（库）源码的意义

1. 学习如何实现功能
2. **学习设计思路**
3. 强制自己写代码，模仿，刻意练习
4. 自己写出优越的代码

创新与拿来主义：站在巨人的肩膀上

### React.createElement

创建的是一个实例，但是是谁的实例不知道，只能去看源码，是 Vnode 的实例，可以在 new Vnode 之前的一系列操作可以封装，否则需要交给用户，而且做任何更改用户不必关心

### vue 异步组件

返回的也是 Vnode 的实例
