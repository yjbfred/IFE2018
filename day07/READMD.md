# CSS布局

## position

## float

## flex

## 两栏自适应布局(高度不知)
+ 左30%右70%
+ 左宽度已知，右宽度自适应
+ 右宽度已知，左宽度自适应 
+ 七种方案
    - 双inline-block+calc方案
    - 双浮动+calc方案
    - float+margin-left方案
    - absolute+margin-left方案
    - float+BFC方案
    - flex方案
    - grid方案
## 三栏自适应布局

+ 左固定，右固定，中间自适应
+ 左固定，中间固定，右自适应
+ 四种方案
    - 圣杯布局和双飞翼布局(利用负margin值，中间盒子放在前面)
    - 双float布局(中间盒子放在最后面)
    - 双absolute布局(中间盒子放在最后面)
    - flex布局