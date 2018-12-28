## 时间戳格式化插件

### 使用说明
``` bash
# 安装依赖
npm install time-formating --save

# 项目引用
import timeFormating from 'time-formating'
Vue.prototype.$timeformater = timeFormating

# 组件中使用
this.$timeformater('1528094422381') // 2018-06-04 14:40:22
this.$timeformater('1528094422381','YYYY-MM-DD hh:mm:ss') // 2018-06-04 14:40:22
this.$timeformater('1528094422381','YYYY-MM-DD hh-mm-ss') // 2018-06-04 14-40-22
this.$timeformater('1528094422381','YYYY/MM/DD') // 2018/06/04
this.$timeformater('1528094422381','YYYY/MM/DD hh:mm:ss') // 2018/06/04 14:40:22
this.$timeformater('1528094422381','YYYY/MM/DD hh-mm-ss') // 2018/06/04 14-40-22
```

