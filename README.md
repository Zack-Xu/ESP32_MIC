# Light Wizard ESP32音乐灯带扩展模块
### 该PCB包含了以下部分
—— 1. INMP621，高灵敏度全向数字麦克风

—— 2. 表面触摸按键

—— 3. 3-4线制灯带接口，KF128-2.54-4P螺丝接口

—— 4. NodeMCU-32S对应引脚排座

—— 5. 独立usb供电接口，不需要购买特殊电源


### 设计原因
  提高模块之间连接的稳定性——脱离面包板。
  
  小型化——方便实际使用时候安置设备。
  
  NodeMCU-32S的对应引脚——通过ESP32的wifi功能接入到homeassistant。

### 用处
—— 1. 音乐灯带模块,通过麦克风获取环境声音，通过处理后，反应到灯带上

—— 2. 智能音箱的无线拾音。通过布置在家庭的各处，实现任意位置唤醒/使用智能音箱

—— 3. 小型监听模块。借助ESP32的wifi功能，可以实现环境声音的捕捉以及打包发送到服务器端

—— 4. 灯带接口，连接了ESP32的17、21号引脚，通过自己编程，可以接其他设备，实现其他功能

### PCB图片
<img src="images/PCB.png">
  
