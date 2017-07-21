# GoodHabit
 A good habit every month
 
## 简介
轻量h5应用，每月一个好习惯（这里是Node工程 ， FE工程 [Click here](https://github.com/DaemonYue/goodhabit)）

## 体验地址
git page

## 应用功能

- 每日为养成中的习惯打卡
- 按照时间轴查看习惯养成轨迹
- 查看 月度、季度、年度 习惯养成情况报表

## 规则说明

### 据说

> 在行為心理學中，人們把一個人的新習慣或新理念的形成並得以鞏固至少需要21天的現象，稱之為21天效應。也就是說，一個人的動作或想法，如果重覆21天就會變成一個習慣性的動作或想法。  
>
> 根據我國成功學專家易發久研究，習慣的形成大致分為三個階段：
> 
> 第一階段：1-7天左右。此階段表現為“刻意，不自然”，需要十分刻意地提醒自己。
> 
> 第二階段：7-21天左右。此階段表現為“刻意，自然”，但還需要意識控制。
> 
> 第三階段：21-90天左右。此階段表現為“不經意，自然”，無需意識控制。

当然这只是一种说法，姑且认为它是真的:new_moon_with_face:

### So, 我们为每个习惯设置了几个阶段， 

```
形成期 ：  1~21天，
巩固期 ：  21~90天，
稳定期 ：  90天后  
```

- 新建习惯后，进入形成期:smiley:
    - 每位用户只能有一个形成期的习惯，习惯进入巩固期后才可以添加新的习惯（求稳不求多啦）
    - 如果习惯实在坚持不下来，或者觉得这个习惯似乎没什么用or不适合自己，也可以终止习惯，终止的习惯也可以在时间轴中查看，不过如果要重启习惯，就要从零开始了哦

- 每个习惯打卡21天后，会自动进入巩固期:muscle:
    - 巩固期的习惯也需要继续打卡
    - 每位用户最多有两个巩固期的习惯
    - 巩固期的习惯超过一个时就不能添加新的习惯哦
    - 巩固期的习惯也可以终止，规则同形成期
    
- 每个习惯打卡90天后，会自动进入稳定期:sunglasses:
    - 稳定期的习惯不会出现在打卡列表里，不需要再打卡了
    - 习惯打到稳定器后半年内，我们会在每月1号提示你回顾一下之前的习惯哦
    