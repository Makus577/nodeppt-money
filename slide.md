title: 投资从入门到放弃
speaker: 
plugins:
    - echarts
    - mermaid: {theme: forest}

<slide class="bg-black-blue aligncenter" image="https://images.unsplash.com/photo-1561414927-6d86591d0c4f?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60">

# 投资从入门到放弃 {.text-landing.text-shadow}

by  {.text-intro}


<slide :class='size-70 aligncenter'>

## 货币历史
---
![](http://localhost:8080/images/barter.jpeg)

物物易换

<slide :class='size-70 aligncenter'>

## 货币历史
---
![](http://localhost:8080/images/Shell.jpeg)

贝币
<slide :class='size-70 aligncenter'>

## 货币历史
---
![](http://localhost:8080/images/money.jpeg)

金属货币
<slide :class='size-70 aligncenter'>

## 货币历史
---
![](http://localhost:8080/images/paper.jpeg)

纸币

<slide :class='size-70 aligncenter'>

## 货币历史
---
![](https://images.unsplash.com/photo-1579533182070-465cbaebe75f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=600&q=60)

人民币
<slide :class='size-70 aligncenter'>

## 为什么货币的种类从贝币变到现在的纸币？


<slide :class='size-30 aligncenter'>

* 一方面是因为制作成本
* 另一方面是因为社会的商品数量会增多


<slide class="bg-black-blue aligncenter" image="https://images.unsplash.com/photo-1554672723-d42a16e533db?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60">

## 通货膨胀 {.text-landing.text-shadow}
<slide :class='size-70 aligncenter'>

## 举个🌰
---
在一个小岛上只有100个商品，岛上流通的总货币是500元

那么每个商品的单价是5元 {.animated.delay-1s}

<slide :class='size-70 aligncenter'>
## 如果商品数保持不变
---
总货币上涨到600元

每个商品的单价是6元 {.animated.delay-1s}

<!-- mermaid
graph TD;
    A-.A向B花200买入一头猪.->B;
    B-.A向B花200买入三只鸡.->C;
    C-.A向B花200买入六条鱼.->A;
产生的价值就有一头🐷、三只🐔和六条🐟 -->


<slide :class='size-70 aligncenter'>
## 如果总货币保持不变
---
如果商品数量增加到125个

每个商品的单价是4元 {.animated.delay-1s}

<slide :class='size-70 aligncenter'>

## 那么我国的通货膨胀率是多少呢？
<slide :class='size-70 aligncenter'>

## M2增长率 - GDP增长率 
---
## 7% {.animated.delay-1s}

<slide :class='size-60 aligncenter'>

## 通货膨胀下的资金变化
---
```echarts {style="height:100%;width:100%;"}
{
    xAxis: {
        type: 'category',
        boundaryGap: false,
        data: ['0','第1年', '第2年', '第3年', '第4年', '第5年', '第6年', '第7年', '第8年', '第9年', '第10年']
    },
    yAxis: {
        name:'（万）',
        type: 'value',
    },
    series: [{
        data: [10,9.3,8.65,8.04,7.48, 6.956,6.47,6.02,5.596,5.2,4.84],
        type: 'line',
        label: {
                normal: {
                    show: true,
                    position: 'top'
                }
            },
    }]
}
```

<slide :class='size-70 aligncenter'>

## 如何解决通货膨胀带来的问题呢？
---

<slide :class='size-70 aligncenter'>

## 不能攒钱，而是攒资产

---
资产就是给你带来被动收入的 {.animated.delay-1s}

<slide :class='size-70 aligncenter'>


## 资产类型
---
* 活期
* 定期
* 黄金
* 基金
* 股票
* 其它 


<slide class="bg-black-blue aligncenter" image="https://images.unsplash.com/photo-1549421263-6064833b071b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60">
## 股票指数 {.text-landing.text-shadow}

<slide class="bg-black-blue aligncenter" image="https://images.unsplash.com/photo-1534469650761-fce6cc26ac0d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60">

## 美国交易所
---
  * 1790年，成立第一所**费城交易所**
  * 1792年，24位经纪人在纽约华尔街68号前签署 **「梧桐树协议」**
  * 1863年，正式改名为**纽约证劵交易所**






<slide :class='size-70 aligncenter'>

* 道琼斯指数
* 标准普尔指数
* 纳斯达克指数
<slide :class='size-70 aligncenter'>

* 上证综合指数500
* 深证成本指数

<slide :class='size-70 aligncenter'>

## 熔断


<slide :class='size-70 aligncenter'>


<slide class="aligncenter" image="https://images.unsplash.com/photo-1591696205602-2f950c417cb9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60">

## 指数基金

<slide :class='size-50 aligncenter'>

## 举个🌰
---

* 每次定投100元，按照计算份额的话，分别是：
100/1+100/0.6+100/0.8+100/1 = 492
* 一次买入400元，那么最后的份额是400
```echarts {style="height:100%;width:100%;"}
{
    legend: {
        data: ['每月定投100元', '一次性买入400元', ]
    },
    xAxis: {
        type: 'category',
        data: ['1月', '2月', '3月', '4月']
    },
    yAxis: {
        name: 'A基金的市值',
        type: 'value'
    },
    series: [{
        name:'每月定投100元',
        data: [1,0.5,0.8,1],
        type: 'line'
    }, {
        name:'一次性买入400元',
        data: [1,1,1,1],
        type: 'line'
    }]
}
```

<slide :class='size-50 aligncenter'>

## 再举个🌰
---

* 每次定投100元，按照计算份额的话，分别是：
100/1+100/1.2+100/0.6+100/1 = 450
* 一次买入400元，那么最后的份额是400
```echarts {style="height:100%;width:100%;"}
{
    legend: {
        data: ['每月定投100元', '一次性买入400元', ]
    },
    xAxis: {
        type: 'category',
        data: ['1月', '2月', '3月', '4月']
    },
    yAxis: {
        name: 'A基金的市值',
        type: 'value'
    },
    series: [{
        name:'每月定投100元',
        data: [1,1.2,0.6,1],
        type: 'line'
    }, {
        name:'一次性买入400元',
        data: [1,1,1,1],
        type: 'line'
    }]
}
```


<slide :class='size-70 aligncenter'>
## 中国
---
  * 1891年，**上海掮客工会**
  * 1904年 **上海证券交易所**
  * 1984年，中国的第一只股票 **「飞乐音响股票」**
  * 1986年9月26日 **上海信托静安营业部**
  * 1990年11月26日 上海证劵交易所
  * 1990年12月1日  深圳证劵交易所
