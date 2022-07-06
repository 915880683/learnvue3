# day01

## vue中methods里面不能使用箭头函数

原因：箭头函数中的this指向的是父级作用域的上下文。严格模式下返回undefined