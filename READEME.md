ant design 组件学习
1.Button
  type=['primary','dashed','danger']或者不写type属性 控制button的类型背景色
  icon属性可以在button中插入icon,还可以在Button中使用Icon
  size属性控制button的大小['default','small','large']
  shape控制button的形状['circle']
  loading属性为button添加loading状态
  ghost属性是button背景变透明色
  Button.Group容器实现button组合：
  ```html
    <Button.Group>
    	<Button>button1</Button>
        <Button>button2</Button>
    </Button.Group>
  ```
  disabled属性
  <Button></Button>最终会被渲染为<button></button>并且除了Button的属性，其他属性都会直接传到button