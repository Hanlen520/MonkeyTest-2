# MonkeyTest
用pyqt写的一个用来执行MOnkey测试的界面

触摸事件是一个down-up事件，它发生在屏幕上的某单一位置


动作事件由屏幕上某处的一个down事件、一系列的伪随机事件和一个up事件组成


轨迹事件由一个或几个随机的移动组成，有时还伴随有点击


"基本"导航事件由来自方向输入设备的up/down/left/right组成


“主要”导航事件通常引发图形界面中的动作，如：5-way键盘的中间按键、回退按键、菜单按键


“系统”按键事件由系统使用，如Home、Back、Start Call、End Call及音量控制键


其它类型事件包罗了所有其它类型的事件，如：按键、其它不常用的设备按钮、等等


启动Activity的百分比。在随机间隔里，Monkey将执行一个startActivity()调用，作为最大程度覆盖包中全部Activity的一种方法
