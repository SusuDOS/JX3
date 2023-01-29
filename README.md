# 剑侠情缘网络版3

## 重置版霸刀宏

说明：会心高的情况下，比如`30%会心`，`狂意rage`一定比`刀气sun`消耗更快狂意将`/cast [rage<28|sun<30] 龙骧虎步`修改为`/cast [rage<30] 龙骧虎步`来减少节约字符，但会心不足会导致狂意倾斜过慢导致`刀气sun`消耗过快，此时需要两个判定。

当前版本为120等级第一赛季，惊鸿五刀蛇版本.

### ===紫色武器版===

```
----掐刀----`(反引号)
/fcast 雷走风切
/cast [skill_notin_cd:擒龙六斩] 松烟竹雾
/cast 擒龙六斩
/cast [last_skill=擒龙六斩] 秀明尘身
/cast 破釜沉舟
/cast 上将军印
/cast [rage<60] 龙骧虎步


-----秀明尘身-----N
/fcast 雷走风切
/cast 破釜沉舟
/cast [bufftime:尘身<0.42] 停止释放
/cast 上将军印
/cast [rage<30|sun<30] 龙骧虎步
/cast [bufftime:命中标记>3.0] 雪絮金屏


----雪絮金屏----N
/fcast 霜风刀法
/cast 坚壁清野
/cast 醉斩白蛇
/cast [skill_notin_cd:破釜沉舟&bufftime:含风>15.5] 秀明尘身
/cast 刀啸风吟
```


### ===橙武武器===


```
---掐刀---键位1--- 
/fcast 雷走风切
/cast [skill_notin_cd:擒龙六斩] 松烟竹雾
/cast 擒龙六斩
/cast [last_skill=擒龙六斩] 秀明尘身
/cast 破釜沉舟
/cast 上将军印
/cast [rage<60] 龙骧虎步


---秀明尘身---键位2---
/cast 破釜沉舟
/cast [bufftime:尘身<0.42] 停止释放
/cast 上将军印
/cast [rage<30|sun<30] 龙骧虎步
/cast [bufftime:命中标记>3.0] 雪絮金屏
/cast 龙骧虎步


---雪絮金屏---键位2---
/fcast 霜风刀法
/cast 坚壁清野
/cast [nobuff:以彼道] 醉斩白蛇
/cast [skill_notin_cd:破釜沉舟&bufftime:含风>15.5] 秀明尘身
/cast 刀啸风吟
```