
This site is published at [](https://kmoonpei.github.io/react-tab/)

### 使用示例
`npm install @kmoonpei/react-tab`

````javascript
import Tabs from '@kmoonpei/react-tab';

<Tabs
  current_position={2}
  titles={['tit0', 'tit1', 'tit2', 'tit3']}
  contanierStyle={{ width: 300 }}
  currentBgColor={'#a3c'}
  list={[[0, 0, 0], [1, 1, 1], [2, 2, 2, 2, 2, 2, 2, 2, 2], [3, 3, 3, 3]]} />
```
|props|是否必传|Type|eg|说明|
| :----------: | :-----------:  | :-----------: | :-----------: | :-----------: |
|titles|是|Array|['tit0', 'tit1', 'tit2', 'tit3']|切换卡的表头组成的数组|
