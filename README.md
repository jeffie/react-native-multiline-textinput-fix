# bugfix to RN android mutiline TextInput  can't use soft keybord returnKey to create a newline (RN 安卓的 textinput 组件 mutiline 无法使用软键盘换行的bugfix)
> 据说是 0.44+ 开始的bug，目前项目是0.47.1仍然存在。临时解决方案来自于某个外国小伙伴用selection位置判别光标位置的奇技淫巧。我在此基础上做了一点封装和完善。

> 用StyleSheet格式化props style，以读取minHeight以及height属性
## extra feature (额外功能)

- autoHeight 此属性可使组件输入以及初始化时高度自适应

## how to use (怎样使用)

```<MultilineTextInput defaultValue={this.state.text} onChangeText={text => setState({text})} />```


## when to fixed (何时被修复)


在此[issue](https://github.com/facebook/react-native/issues/12717)被修复

it was fixed at [issue](https://github.com/facebook/react-native/issues/12717)




