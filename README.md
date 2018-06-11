# react-full-page
一个基于Vue的简版chart组件，欢迎大家去Issues提出宝贵意见。

# Install

    $ npm install vue-simple-chart

# Usage

### A basic usage
```javascript
import VueSimpleChart from 'vue-simple-chart'

### Template
```html
<vue-simple-chart :list="list" @close="onChartClose"></vue-simple-chart>
```

### Default Data
```javascript
data () {
  return {
    list: [
      {name: 'a', val: 1},
      {name: 'b', val: 2},
      {name: 'c', val: 3, selected: true},
      {name: 'd', val: 4, selected: true},
      {name: 'e', val: 5, correct: true},
    ]
  }
}
```

### methods
methods: {
  onChartClose() {
    console.log('关闭chart')
  }
}

# Example

    $ git clone https://github.com/zhishaofei3/vue-simple-chart
    $ npm install
    $ npm start

Local documentation will then be available at `http://localhost:8080`.
