# react-chart-tooltip
react-chart-tooltip

### How to use
```javascript
import ToolTip from 'react-chart-tooltip';

<ToolTip />

```
### RadialBarChart Props
```javascript
{
  tooltip: {  // default
    show: true,
    formatter: (ringInfo) => {
      return `占比: ${ringInfo.percent*100}%`;
    }
  },
  tooltipStyle: {
    backgroundColor: 'rgba(0,0,0,0.65)',
    ...
  },
  x, // postiton.x
  y, // postiton.y
  info,
  title,
  width, // container width
  height, // container height
}
```
