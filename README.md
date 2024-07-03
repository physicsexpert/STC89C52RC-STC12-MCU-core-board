# 项目简介
功能齐全的stc89c52rc单片机核心板，支持多种功能，所有io口均引出<br>
<img src=picture/5tWKvq7XPJnyzfxLQahjvPZsRGwXF6wkMBQEnq6U.jpeg width=50% />

## 立创开源平台链接：https://oshwhub.com/expert/89c52_copy

## 关于硬件
### 本项目采用嘉立创eda标准版设计，请使用嘉立创eda标准版软件导入工程
硬件功能：<br>
1.IO口全部引出，其中P0～P3采用双排针设计，可以一排向上一排向下，满足各种需求。所有排针定位准确，确定可以直接插入洞洞板和面包板。<br>
2.可以采用USB-C供电，CC引脚有5.1k电阻下拉到GND，保证所有充电头均可正常识别。除此之外，也可采用外接电源插入USB口旁的VIN和GND引脚即可。<br>
3.板上自带一组3.3V电源（横向蓝色排针）5V电源和GND也有预留外接口（黄色和黑色横向排针）<br>
4.串行烧录口单独引出（竖向蓝色排针）<br>
5.采用3225晶振，更加平整美观<br>
6.P0口全部预留上拉电阻焊盘，在PCB背面<br>
## 关于软件
软件代码采用江协科技开源的51单片机代码，链接：https://space.bilibili.com/383400717?spm_id_from=333.337.0.0<br>
使用KEIL5配置c51环境后导入代码后编译<br>
需要使用usb转串口模块配合stcisp上位机软件烧录代码<br>


