1.State总结
1.1 强烈注意
  1) 组件中render方法中的this为组件实例对象。
  2) 组件自定义的方法中this为undefined，如何解决：
    a.强制绑定this：通过函数对象的bind()
    b.箭头函数
  3) 状态数据，不能直接修改或更新，调用setState方法。

2.Prop
2.1
  1) ...运算符(展开运算符)：展开对象...p(等同与Name=汤昊,age=18,性别=男)，展开数组 let arr3 = [...arr1,...arr2]，展开函数入参function sum(...s){}
