<p> </p>
<p><span style="color:#843fa1">启凡科创开源官方Q群：216066270(配套上位机在群文件，开源平台仅能上传50M内）</span></p>
<p> </p>
<p><span style="color:#2dc26b"><strong><span style="color:#3598db">最新日志（gitee全开源固件，更多历史查阅gitee工程文档）：</span></strong></span></p>
<p>###  ** VER:V1.0.9 Release<br>#  ** D:2024-6-29</p>
<p>###  新增<br>#  新增鼠标APP，可对触摸板模式鼠标灵敏度进行管理<br>#  专用上位机QF-ZERO-TOOL更新至V1.0.4</p>
<p>###  修复<br>#  修复自动息屏时无法保存亮度值的问题</p>
<p>###  调整<br>#  调整部分APP内背景色为纯黑<br>#  调整鼠标指针样式，防止纯黑时看不到指针</p>
<p><br>###  ** VER:V1.0.8 Release<br>#  ** D:2024-6-28 </p>
<p>###  新增：<br>#  新增配套固件更新上位机，一键无脑更新固件<br>#  新增经典扫雷小游戏<br>#  新增2048小游戏<br>#  新增设置内部可调整自动息屏时长，可查看固件版本<br>#  新增两个官方基础表盘<br>#  触屏新增触摸板模式，通过系统键值对即可开启<br>#  LVGL更新至V8.4.0<br>#  新增下拉状态栏控制中心<br>#  新增手电筒功能（控制中心）<br>#  新增截屏功能（目前仅添加了按钮，暂未适配功能，需求貌似不大）<br>#  新增在表盘界面下单击按键息屏<br>#  新增一些键值对通信指令<br>#  新增APP菜单快捷创建接口,可参考设置APP编写方法进行菜单类APP创捷创建</p>
<p>###  调整：<br>#  更新app管理器，添加用户数据指针功能<br>#  更新触摸驱动<br>#  优化桌面菜单风格<br>#  优化APP加载、退出动画体验<br>#  去掉双击屏幕调整亮度，移动至下拉状态栏控制中心内<br>#  双击按键返回桌面在游戏模式时禁用，由游戏自身响应功能，游戏可通过键值对通知系统是否为游戏<br>#  优化时钟APP界面风格<br>#  优化电子木鱼返回桌面时不会再增加点击数<br>#  一些小细节调整</p>
<p>##  修复：<br>#  修复注册的带UI的APP数量为0时无法开机的bug<br>#  修复APP内自动息屏时不会通知APP进行close导致的数据丢失的bug<br>#  解决工程在Linux下编译头文件大小写报错的问题<br>#  修复表盘在切换时文本会有短暂显示为框框的bug<br>#  其他小细节修复</p>
<p>#  tip：桌面左右滑动即可切换表盘</p>
<p> </p>
<p><span style="color:#2dc26b"><strong><span style="color:#3598db">其余所有更新说明均置于Gitee仓库内的更新日志</span></strong></span></p>
<p> </p>
<p><span style="color:#2dc26b"><strong><span style="color:#3598db">2023-8-31  完全开源的软件</span></strong></span></p>
<p><span style="color:#2dc26b"><strong><span style="color:#3598db">本项目软件部分完全开源至Gitee且长期不定时更新，内含较完整的说明文档帮助快速上手开发结构，希望大家能一起完善添加更多APP，如果遇到使用开源的软件的bug，请及时到交流群内反馈，开源链接(含主副处理器）:<a href="https://gitee.com/deng-hongxiang/qf_-zero_-v2_-software" target="_blank">https://gitee.com/deng-hongxiang/qf_-zero_-v2_-software</a></span></strong></span></p>
<p> </p>
<p><span style="color:#2dc26b"><strong><span style="color:#3598db"><span style="color:#e03e2d">2023-6-13 外壳V1.2<br></span></span></strong></span></p>
<p><span style="color:#3598db">     对比V1.1外壳，做出以下调整：</span><br>         1）<span style="color:#e03e2d">厚度减小0.4mm</span>到10.6mm<br>         2）采用<span style="color:#e03e2d">PCB</span>或自己裁切的铝片（厚度均为<span style="color:#e03e2d">0.8mm</span>）<span style="color:#e03e2d">作为后盖</span>，安装方式为<span style="color:#e03e2d">4颗M1.4*3.5的沉头自攻螺丝</span>！切记，<span style="color:#e03e2d">螺丝很重要</span>！相关的PCB和铝片螺丝孔位置需要<span style="color:#e03e2d">自行</span></p>
<p><span style="color:#e03e2d">                做好沉 孔</span>倒角处理。<br>         3）<span style="color:#e03e2d">正面斜面角度改大</span>，由原来的45°倒角增大到60°(附近，具体忘了），观感个人认为有所提升<br>         4）<span style="color:#e03e2d">后盖PCB文件在开源工程页面有提供</span>，铝片需要自行建模去CNC或者导出PCB外形层进行激光雕刻</p>
<p> </p>
<p><span style="color:#e03e2d">材料说明</span>：<br>         需要使用 <span style="color:#e03e2d"> 尼龙激光烧结</span>（嘉立创就有，但是要注意提醒那边<span style="color:#e03e2d">不要进行任何缩放</span>，不然可能工厂擅自放大了一点回来松垮垮的）   <span style="color:#e03e2d"><span style="color:#3598db">或</span>类ABS、类尼龙（更推荐）树脂进行</span><br>         <span style="color:#e03e2d">光固化</span>打印，普通树脂打螺丝（V1.2）和扣后盖（V1.1）会碎，FDM打印的几乎不能用，不在考虑范围内，如果需要CNC金属，需要对模型进行一定修改</p>
<p> </p>
<p><span style="color:#2dc26b"><strong><span style="color:#e03e2d">2023-5-16 固件V1.0.3</span><span style="color:#3598db"><br>        </span></strong><span style="color:#3598db">ESP32-S3：</span><span style="color:#3598db"><br>              <span style="color:#e03e2d">  修改：</span>步数显示改为<span style="color:#e03e2d">电池电压显示</span><br>               <span style="color:#e03e2d"> 优化：</span>屏幕刷新率由90降低至77帧，<span style="color:#e03e2d">降低显示竖纹</span>提升观感<br>                         <span style="color:#e03e2d"> 记忆</span>功德数、屏幕亮度、表盘界面，息屏唤醒后<span style="color:#e03e2d">保留原有状态</span><br>                          指针表盘中心点<span style="color:#e03e2d">对齐优化</span><br>        HC32：<br>            无</span></span></p>
<p> </p>
<p> </p>
<p><span style="color:#2dc26b"><strong><span style="color:#e03e2d">2023-5-4  固件V1.0.2</span><span style="color:#3598db"><br>            </span></strong><span style="color:#3598db"><span style="color:#e03e2d"><strong>新增：</strong></span><span style="color:#b96ad9">赛博修仙</span>--&gt;数字表盘左滑进入，随时随地积攒功德</span><span style="color:#3598db"><br>                      <span style="color:#b96ad9">POP猫</span>--&gt;指针表盘右滑进入，随时随地阿巴阿巴<br>           <span style="color:#e03e2d"> 修改：</span>指针表盘的圆弧震动测试关闭，修仙和阿巴阿巴均可有震动反馈<br>            <span style="color:#e03e2d">优化：</span>屏幕刷新率由60帧提升到<span style="color:#e03e2d">90帧</span>，纵享新丝滑<br>                       <span style="color:#e03e2d">息屏唤醒时间打骨折</span>，由原来的1.7s左右优化到200ms以内</span></span></p>
<p> </p>
<p><span style="color:#2dc26b"><span style="color:#000000">2023-4-26 固件V1.0.1</span><strong><br>   <span style="color:#e03e2d"> 新增：</span></strong>HC32的串口全双工<span style="color:#e03e2d">中断死机</span>问题<span style="color:#e03e2d">解决</span>，可以<span style="color:#e03e2d">稳定</span>当手表日常<span style="color:#e03e2d">佩戴看时间</span>使用了，目前测试暂时<span style="color:#e03e2d">再未</span>出现过<span style="color:#e03e2d">死机</span></span></p>
<p> </p>
<p>2023-4-23 <span style="color:#e03e2d">固件V1.0.0</span><br>   <strong><span style="color:#e03e2d"> 新增：</span></strong></p>
<p>              ESP32S3-<span style="color:#e03e2d">手表显示时间功能固件</span>，适配LVGL官方手表demo为240*240分辨率，界面适配为楷体中文，目前<span style="color:#e03e2d">仅可用于看时间和电池电量</span>，</p>
<p>                     其余 功能暂未适配<br>              HC32-电源管理、RTC时钟、IIC设备扫描<br>             <span style="color:#e03e2d">屏幕亮度、振动器操作</span>，数字表盘左下角arc更改亮度，指针表盘arc设置震动</p>
<p>       <span style="color:#e03e2d">      V22原理图和PCB</span>，对比V21多了一颗电容，具体（<span style="color:#3598db">抽风的违禁词识别</span>）位置打了V21板子的同学可以去原理图看一下根据提示加上去就行，<span style="color:#e03e2d">无需重新打板</span>   </p>
<p>             <span style="color:#e03e2d">版本特性：<span style="color:#843fa1">超低功耗</span></span>，充满电正常使用看时间，预计最少可用2个月</p>
<p>             <span style="color:#e03e2d">已知问题</span>：有一定概率HC32硬件死机，它的串口功能暂未做半双工适配，死机后用<span style="color:#e03e2d">串口助手重启HC32</span>即可</p>
<p> </p>
<p><strong><span style="color:#3598db">下载步骤：</span></strong><br>    如没<span style="color:#e03e2d">装</span>过CH343的<span style="color:#e03e2d">驱动</span>，需要安装一下，只装了CH340的驱动仅能识别COM口，下载会报错，驱动在资料包里有<br>    <span style="color:#e03e2d">ESP32S3</span>：按照ESP32S3的<span style="color:#e03e2d">固件包内</span>的配置步骤使用<span style="color:#e03e2d">download tool进行烧录下载</span>，烧录结束后点击stop后使用提供的<span style="color:#e03e2d">串口助手按照提示重启一下</span>ESP32S3<br>    <span style="color:#e03e2d">HC32</span>：按照配置内容使用<span style="color:#e03e2d">XHSC</span>下载器选中固件<span style="color:#e03e2d">HEX</span>进行下载即可，烧录结束后使用提供的<span style="color:#e03e2d">串口助手按照提示重启一下<span style="color:#000000">HC32</span></span></p>
<p> </p>
<p><strong><span style="color:#3598db">配置步骤：</span></strong>（<span style="color:#2dc26b">发送指令和扫描设备期间手需要一直触摸屏幕保持手表常亮</span>）<br>   <span style="background-color:#ffffff;color:#e03e2d"> 配置时间：</span>通过串口助手发送格式为：如<span style="color:#e03e2d">(time230423113605)</span>，括号为<span style="color:#e03e2d">英文</span>状态下的，time指设置时间，23为23年，04为四月，23日，11时，36分，05秒，每一个参数<span style="color:#e03e2d">固定占2位，不足补0</span>，发送完后时间立即更新至显示，日期需息屏重新唤醒后才会更新<br>    <span style="color:#e03e2d">扫描IIC设备：</span>发送指令<span style="color:#e03e2d">(scan)</span>,括号为英文状态下的，通过<span style="color:#e03e2d">扫描</span>设备可以知道磁力计、imu、气压计、库仑计<span style="color:#e03e2d">焊接是否存在问题</span></p>
<p> </p>
<p><span style="color:#3598db"><strong>关于外壳：</strong></span></p>
<p>    1）<span style="color:#ba372a">23-4-17</span>更新了V1.1版本外壳，<span style="color:#ba372a">优化了按键部分</span>，解决了V1.0版本的偶尔回弹卡顿不舒服的问题</p>
<p>    2）一个比较好的打印方案：采用<span style="color:#ba372a">黑色类尼龙树脂打印</span>，实测效果非常好，完全<span style="color:#ba372a">解决了刚性树脂易碎、起白色痕迹的缺点</span>，打印出来只需要对支撑点进行<span style="color:#ba372a">简单打磨</span>即可，<span style="color:#ba372a">无需精细打磨和喷漆</span>等操作就能获得一个非常好的效果，后盖安装也完全ok<span style="color:#ba372a">不再怕卡扣碎裂</span>，<span style="color:#ba372a">缺点</span>就是类尼龙树脂<span style="color:#ba372a">比较贵</span>（50元250克），为了这个外壳我甚至买了台光固化。。。</p>
<p> </p>
<p><strong><span style="color:#3598db">关于硬件：</span></strong></p>
<p>    1）<span style="color:#ba372a">新增了V2.2的PCB和原理图</span>，这些小细节的优化会让体验提升很多，发现了HC32L110的一个硬件bug：串口开启中断的情况下，全双工发数据非常容易触发死机，这点就非常难受了，软件上只能做半双工用了</p>
<p>    2）<span style="color:#ba372a">程序烧录：</span>按住按键即可烧录副处理器HC32（不按是烧录ESP32S3），HC32烧录完后不会自动复位重启，需要用<span style="color:#ba372a">串口助手uartassist</span>开关一下<span style="color:#ba372a">RTS信号</span>重启HC32</p>
<p>    3）屏幕使用的型号是 <span style="color:#ba372a">8080接口 带TP IF10</span>，就是触摸盖板狗啃的一样那款，搜<span style="color:#e03e2d">1.28寸触摸</span>就行</p>
<p>    4）使用的<span style="color:#ba372a">电池是R40350V 435mah 3.85V圆形电池</span></p>
<p><span style="color:#ba372a">    <span style="color:#000000">5）使用的表带：插针式20mm宽度表带全通用</span></span></p>
<p><span style="color:#ba372a"><span style="color:#000000">    6）使用的振动器：0820  直径8mm，厚度2mm的扁平振动器</span></span></p>
<p><span style="color:#ba372a"><span style="color:#000000">    7）<strong>焊接注意要点：</strong><span style="color:#e67e23">①</span>所有元器件焊接完成后再焊振动器，振动器上面贴的双面胶和海绵都要刮掉减小厚度，<span style="color:#e67e23">②</span>中龟按键平整的一面向着屏幕，四个脚悬空用锡焊到焊盘上，<span style="color:#e67e23">③</span>在焊接按键和振动器时，将PCB和元件放在平整的平面上压紧焊以保证接触屏幕的一面平整</span></span></p>
<p><span style="color:#ba372a"><span style="color:#000000">    7）<strong>组装流程：<span style="color:#e67e23">①</span></strong>先装按键，<span style="color:#e67e23">②</span>屏幕先斜着放入排线一侧，然后平缓装好，<span style="color:#e67e23">③</span>主板贴屏幕那一面，所有裸露的焊盘必须清理得非常平整没有锡的毛刺，然后使用油性马克笔或其他带有一定绝缘作用的笔涂黑焊点，有条件的可以上阻焊油，但是一定要确保平整不会抵住屏幕，<span style="color:#e67e23">④</span>主板先对准按键的凹槽放入按键那里，然后右边C口那里用力按进去就行，注意屏幕排线，<span style="color:#e67e23">⑤</span>扣上屏幕排线，<span style="color:#e67e23">⑥</span>电池有口的一面刚好放C口那里，把两根电源线并排理好，高度弄平不然会抵住后盖，<span style="color:#e67e23">⑦</span>后盖先对齐屏幕排线那一侧的两个卡扣推进去卡住，然后用小拇指指甲等比较软的东西依次把另外两个卡扣卡进去，<span style="color:#e03e2d">下面有步骤图</span></span></span></p>
<p> </p>
<p><strong><span style="color:#3598db">硬件资源：</span></strong></p>
<p>    1）<span style="color:#ba372a">ESP32-S3 </span>为核心主控，负责复杂的运算与交互处理，默认为<span style="color:#ba372a">8M Psram + 32M flash</span>组合</p>
<p>    2）<span style="color:#ba372a">HC32L110C6UA</span>为<span style="color:#ba372a">副处理器</span>，负责处理低功耗任务</p>
<p>    3）<span style="color:#ba372a">LSM6DSL 六轴姿态传感器</span>，低功耗与多功能并存</p>
<p>    4）<span style="color:#ba372a">QMC5883L 三轴磁力计</span>，配合LSM6DSL可实现九轴姿态融合</p>
<p>    5）<span style="color:#ba372a">BMP280 气压计</span>，可实现海拔高度和环境温度的测量</p>
<p>    6）<span style="color:#ba372a">CW2015 库仑计</span>，精确统计电池电量</p>
<p>    7）带电容触摸屏的<span style="color:#ba372a">1.28寸240*240分辨率圆形屏幕</span></p>
<p>    8）<span style="color:#ba372a">振动器</span></p>
<p>    9）<span style="color:#ba372a">3.85V锂电</span>池充放电管理、保护</p>
<p>  </p>
<p><span style="color:#3598db"><strong>设计特色：</strong></span></p>
<p>    1）<span style="color:#ba372a">主、副处理器均可由充电的TYPE-C接口烧录程序</span>，不用反复更改任何硬件，一口多用</p>
<p>    2）<span style="color:#ba372a">超低待机功耗</span>，关机状态下可低至14uA，不开运动功能待机在30uA附近</p>
<p>    3）接近商品级的<span style="color:#ba372a">外观设计</span></p>
<p>  </p>
<p><span style="color:#3598db"><strong>关于软件：</strong></span></p>
<p>    1）<span style="color:#e03e2d">因制作难度较高，几乎不存在投机者倒卖的现象，故软件也进行了完全开源</span></p>
<p>    2）此项目设计目标是作为我<span style="color:#e03e2d">个人</span>智能家居或遥控无人机等的体感遥控器或触屏中央控制器，并不针对其他人，请<span style="color:#e03e2d">有需求的勿提</span>，<span style="color:#e03e2d">自行</span>修改或自己设计</p>
<p>    3）此手表可以作为学习开发智能手表的<span style="color:#e03e2d">开发板</span>使用</p>
<p>    4）项目框架采用<span style="color:#e03e2d">所有应用层可分离去耦</span>方式，APP之间通过提供的键值对通信库进行所有内容交换，同时也构建了<span style="color:#e03e2d">清晰易懂的结构框架</span>，让参与者能快速上手</p>
<p>    5）软件框架内提供了<span style="color:#e03e2d">详细的说明手册</span>，针对一些规范和注意事项都有注明，进一步降低入门上手难度</p>
<p> </p>
<p><strong><span style="color:#3598db">一些效果图：</span></strong></p>
<p><strong><span style="color:#3598db"><img src="//image.lceda.cn/oshwhub/9d3e076281924d03bda0d8eed68816a0.jpg" alt="" width="800" height="600"></span></strong></p>
<p><strong><span style="color:#3598db"><img src="//image.lceda.cn/oshwhub/c6ae1f4025ed44b399f4007ee7512ff1.jpg" alt="" width="500" height="641"><img src="//image.lceda.cn/oshwhub/0f7ecbacaba64975a3317e192783cf3c.jpg" alt="" width="500" height="678"></span></strong></p>
<p> </p>
<p><strong><span style="color:#3598db"><img src="//image.lceda.cn/oshwhub/05e449333b0345859dd3e5b6a779ebc1.jpg" alt="" width="500" height="642"><img src="//image.lceda.cn/oshwhub/05773c9d0a3c4f21b6a051aca1818a98.jpg" alt="" width="500" height="667"></span></strong></p>
<p><strong><span style="color:#3598db"><img src="//image.lceda.cn/oshwhub/0446212f75a046f79cd95e2a174fcb55.jpg" alt="" width="500" height="657"><img src="//image.lceda.cn/oshwhub/aa3629049f9449faadaae5f6cdfa1e27.jpg" alt="" width="500" height="664"></span></strong></p>
<p><img src="//image.lceda.cn/pullimage/49B7dtOnxVURBmWeTwbomOWxAInv52zXJr5Pimkb.jpeg" alt="" width="500" height="837"></p>
<p><img src="//image.lceda.cn/pullimage/ngyrZXG0JhHcscYDY4pWETWR3sOuisjxivr3Tqqy.jpeg" alt="" width="500" height="769"><img src="//image.lceda.cn/pullimage/wsXj5dk3qzVT5NEHrtSSNqsSzkhjaCkeyGmtrazK.jpeg" alt="" width="500" height="760"></p>
<p> </p>
<p> </p>
<p><strong><span style="color:#3598db"><img src="//image.lceda.cn/pullimage/gEcFnmfsAw8HODMRPf5B07M7IkrbRSfSrPjxE8Ni.jpeg" alt="" width="500" height="470"><img src="//image.lceda.cn/pullimage/0eZlOsf4yNThTwVD4UVdHJv6S4ykRYq8QzQHnwO9.jpeg" alt="" width="500" height="470"></span></strong></p>
<p><img src="//image.lceda.cn/pullimage/qBzDMftGW5n2YWeBrm19CtDAsVYecVg4LD59ITWk.jpeg" alt="" width="500" height="500"><img src="//image.lceda.cn/pullimage/5K7AHR0UY0ixuFHYecbC2mRj88jInWStjWV1R9oE.jpeg" alt="" width="500" height="381"></p>
<p><img src="//image.lceda.cn/pullimage/vwdvBmlcJfjfEPgA1QHEzbj7QIAr2aaRxYDFUGxH.jpeg" alt="" width="500" height="515"><img src="//image.lceda.cn/pullimage/YAfhwpBEGgFAwVg9I788oYk8POFU7KAJHqHtUIxY.jpeg" alt="" width="500" height="539"><img src="//image.lceda.cn/pullimage/DcurhQULliotAMqH7E47ZKHSDTVOP2Po8JNTDkCd.jpeg" alt="" width="500" height="438"><img src="//image.lceda.cn/pullimage/G1iSHkNBjNYf1tBnOC0vpKLo23AfY7RysfkVcs4B.jpeg" alt="" width="500" height="579"><img src="//image.lceda.cn/pullimage/TKSl0Vg6nuKzzIncxGDeKe24mSAgdtpJQsdf7dNN.jpeg" alt="" width="500" height="397"></p>
<p> </p>
<p> </p>
<p><span style="font-size:48px">V1.2（左边）V1.1（右边）外壳对比（尼龙树脂）</span></p>
<p><img src="//image.lceda.cn/pullimage/vhqbYSsn1VtoWr149zj91lYsQsllGhTvJ7q67Mjj.jpeg" alt="" width="921" height="765"></p>
<p> </p>
<p> </p>
<p> </p>
<p> </p>
<p> </p>
<p> </p>            
How to use：

At editor, open the document via: Top menu - File - Open - EasyEDA... , and select the json file, then open it at the editor, you can save it into a project.


如何使用：

打开编辑器，通过：顶部菜单 - 文件 - 打开 - 立创EDA... ，选择 json 文件打开在编辑器，你可以保存文档进工程里面。