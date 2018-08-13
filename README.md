
This site is published at [https://kmoonpei.github.io/react-tab/]

### 使用示例
首先，下载组件
```
npm install @kmoonpei/react-tab
```
然后，在react组件中引用如下：
```javascript
import Tabs from '@kmoonpei/react-tab';

<Tabs
  current_position={2}
  titles={['tit0', 'tit1', 'tit2', 'tit3']}
  contanierStyle={{ width: 300 }}
  currentBgColor={'#a3c'}
  list={[[0, 0, 0], [1, 1, 1], [2, 2, 2, 2, 2, 2, 2, 2, 2], [3, 3, 3, 3]]} />  
```
### 参数说明

  |props|是否必传|Type|eg|说明|
  | :----------: | :-----------:  | :-----------: | :-----------: | ----------- |
  |titles|是|Array|['tit0', 'tit1', 'tit2', 'tit3']|切换卡的表头组成的数组|
  |contanierStyle|否|Object|{width:300}|切换卡的最外层样式，默认宽度200|
  |current_position|否|Number|0|当前所在切换卡的下标|
  |currentBgColor|否|String|'#a3c'|当前所在切换卡的标题背景色，默认为'rgba(238,238,238,.5)'|
  |list|是|Array|[[0, 0, 0], [1, 1, 1], [2, 2], [3, 3, 3, 3]]|每个选项卡下的内容，无比与titles的数量保持一致，并且下标也一致，与其一一对应|
