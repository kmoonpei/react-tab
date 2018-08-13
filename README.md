
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
### 使用示例
`npm install @kmoonpei/react-tab`

````markdown
import Tabs from '@kmoonpei/react-tab';

<Tabs
  current_position={2}
  titles={['tit0', 'tit1', 'tit2', 'tit3']}
  contanierStyle={{ width: 300 }}
  currentBgColor={'#a3c'}
  list={[[0, 0, 0], [1, 1, 1], [2, 2, 2, 2, 2, 2, 2, 2, 2], [3, 3, 3, 3]]} />
```
