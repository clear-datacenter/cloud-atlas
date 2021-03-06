随着Apple Pay正式进入中国，NFC支付技术市场几乎瞬间引爆。然而，对于Android用户来说，其实很多手机硬件早已经支持了NFC，只是因为市场准入原因，Android Pay始终无法进入中国。

不过，招商银行从2015年10月开始，正式推出了NFC近场支付的服务，称为"一闪通•云闪付"。用户仅需一部具有NFC功能的安卓手机、一张招商银行信用卡、一个“掌上生活”App即可开通该业务;持卡人只需点亮手机屏幕靠近带有“闪付”标志的POS机即可完成消费。

# 扫一扫

速度：3到5秒闪付

“云闪付”操作极简单，与扫码支付相比，线下支付时不需要“解锁屏幕、打开App、找到相应菜单、向收银员出示二维码”等流程，只要点亮手机屏幕靠近带有“闪付”标志的POS机，听到“滴”的一声支付就完成了，因此，全程只需3到5秒。 

# NFC支付优点

* 制造成本低。只需要把一块NFC功能模块搭载到移动终端就可以使用。
* 安全性高。NFC通讯距离没有蓝牙远，速度没有蓝牙快，所以并不能取代蓝牙。但其短距离通信特征则成就了其天然的优势，对于移动支付来说，安全是最重要的。NFC刷卡手机支付需要在小于0.1M的范围内才能通信，并且只能点对点的通信，这保证在移动支付通信时数据传输的高度的保密性与安全性。只要终端设备在你的管理范围内，就不没有被盗刷的可能性。
* 便捷性好。传统钱包就是一个累赘，到哪时都需要带着，很不方便。而NFC刷卡手机拥有钱包功能，可以把所有卡片(银行卡、门禁卡、校园卡、会员卡、公交卡)统统都装在这部智能手机里面，给钱包减负，给自己减负，管理和使用起来更方便，轻松。
* 耗能低。它的耗电量远远小于蓝牙和红外装置，把NFC模块装载在智能手机里，不需要手机供电，一样可以使用。（抓住重点，没电，你也可以用！！）

# NFC公交卡充值

> 需要使用最近发行的新公交卡才有NFC功能

支付宝`城市一卡通`功能即使用NFC支付，不过根据产品帮助说明，显示只有重庆、青岛等6个城市发行的公交卡充值，对于魔都，则无法对公交卡充值。而且台州还支持一卡通的手机公交卡。

不过，由于NFC是开放协议，依然可以读取卡上的余额信息和卡号。

> [NFC手机支付，何时消灭公交卡？](http://tech.ifeng.com/speakout/detail_2014_06/26/37030697_0.shtml)

不过，上海公交公司自己开发了[上海交通卡](http://www.sptcc.com/Load_jiaotongkaxinwen.html#xinwen?jtk_new/jtk_p10_l23.json)手机应用，可以支持银联卡向交通卡充值。不过，手机充值只限“U”字母开头的交通卡，且必须使用带有NFC功能的安卓手机。

使用`Taginfo`可以看到NFC交通卡详细的信息。

小米5也内建了NFC功能，支持读卡、写卡、卡模拟，以及P2P模式。成功绑定公交卡后，就可以用小米5作为公交卡使用，并且支持充值。

> [一张图看懂小米5 NFC充公交卡！太方便了](http://news.mydrivers.com/1/472/472705.htm)

NFC的硬件部分并不复杂，由CLF（非接前端模块）、射频天线、SE（安全区域）三部分构成。只是读公交卡以及充值，CLF+天线就够了；如果还想把手机App做成电子公交卡（支持空中发卡和空中圈存），那么还需要SE部分。

读卡兼容问题，出在CLF的NFC芯片上。目前国内主流的手机NFC芯片供应商有恩智浦、博通、联发科、三星电子，恩智浦为业内份额第一，博通次之，联发科、三星电子更次，其中三星电子的量主要在Note 4这款机型上。

各家芯片公司在NFC的公开标准上，都会有自己的实现，比如有些更兼容老的标准，有的选用了标准内的不同方法，诸如此类等等。如果不能读卡，基本上可以确认是不同芯片之间实现方法不同所造成的兼容问题。

> [你的NFC手机为何不能读公交卡？](http://www.leiphone.com/news/201502/LVGgMGoCgSyOYZ74.html)

# 参考

* [招商银行信用卡推NFC“云闪付” 手机信用卡“合体”](http://www.yicai.com/mnews/2015/10/4701145.html)
* [Android 详解第三方介质交互之NFC,并且实现读你的交通卡，酒店房卡，学生证！](http://blog.csdn.net/ddwhan0123/article/details/47447251)
* [NFC手机支付，何时消灭公交卡？](http://tech.ifeng.com/speakout/detail_2014_06/26/37030697_0.shtml)
* [一张图看懂小米5 NFC充公交卡！太方便了](http://news.mydrivers.com/1/472/472705.htm)
* [你的NFC手机为何不能读公交卡？](http://www.leiphone.com/news/201502/LVGgMGoCgSyOYZ74.html)