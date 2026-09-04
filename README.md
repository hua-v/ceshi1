<img width="1305" height="1197" alt="屏幕截图 2026-09-04 112407" src="https://github.com/user-attachments/assets/e9407f81-1bf9-4511-a0ec-bc9e5dc3db9a" /><img width="2552" height="1127" alt="屏幕截图 2026-09-04 112215" src="https://github.com/user-attachments/assets/ac3109f5-98ed-40c3-9488-69375e5ccb4d" />
更改草快渲染距离，起始10000.结束15000，使草在10000以外缓慢剔除直到15000消失
<img width="2475" height="1158" alt="屏幕截图 2026-09-04 112336" src="https://github.com/user-attachments/assets/3422de5d-5975-4c4f-be65-f2a94efb7fdc" />
根据添加的平面来确定水平面往上一段距离为沙滩地形
<img width="2081" height="1142" alt="屏幕截图 2026-09-04 112315" src="https://github.com/user-attachments/assets/dad3adc8-6d2a-4063-863d-e83d68edfa33" />
<img width="2483" height="1043" alt="屏幕截图 2026-09-04 112515" src="https://github.com/user-attachments/assets/7f78425e-5806-48e3-980b-07e8a2010c01" />
不使用大片的水体建模改用湖水的，关闭其影响地形的选项，然后投放到整个地图，可以使水下有视野受阻的效果
<img width="1305" height="1197" alt="屏幕截图 2026-09-04 112407" src="https://github.com/user-attachments/assets/29f0af7d-2c82-487a-9010-c2f4e1a99ad8" />
根据计算地形的法线，平滑度（smooth）来求其倾斜度（大于某个值将铺上岩石地形，反之为草地地形），以及树木使用程序化植物生成之前，先要调节树木本身的参数（根据倾斜度来判断能否生长，以及离水平面的高度来计算生成的种类）
<img width="2026" height="1071" alt="屏幕截图 2026-09-04 112631" src="https://github.com/user-attachments/assets/2d50ea0a-bce4-491c-8b60-ad98debd6547" />
这个是通过按键1，2，3，g来控制手持为物品栏哪个物品（显示种类），以及按g丢出物品时计算物品将往何处运动的蓝图
这之后应该和角色蓝图及动画蓝图相连接来告诉角色按下按键应该干什么，但是我把这些写到引擎原本的角色上了T_T
