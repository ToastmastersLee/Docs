# NMP 参数表维护记录

[toc]



## NMP

| Version                                                  | Status  | Description                                                  | Date Modified | Modifier/Contributor |
| -------------------------------------------------------- | ------- | ------------------------------------------------------------ | ------------- | -------------------- |
| 202405                                                   | Edited  | 1. 调整广播、流媒体参数表,移除掉原来诸多协议，对分辨率和码率做最新的更新调整（1080p@30fps recommended,  up to 4K@30fps）<br />2. 原格式支持参数（audio format, video format)合并到广播参数描述中<br />3. Communication Interface的USB接口描述调整[^1]<br />4. 拆分Power Control，并调整Power Control的描述<br />5. 调整 Phoenix 4-Pin的描述<br />6. 调整功放接口描述<br /> | 2024-05-24    | Lee                  |
| 202405-v2                                                | Edited  | 1. 调整 IR-IN，IR-OUT参数描述<br />2. Single pole double throw（SPDT） switch (External port) * 1；调整为“ External port (RELAY) * 1”<br />3. “Audio matrix module”名称调整为”Audio",因为矩阵还包含了DHMI OUT A | 2024-05-24    |                      |
| [NDP100 v2-2024-08-21.xlsx](./NDP100 v2-2024-08-21.xlsx) | Deleted | 1. 移除掉Lock接口锁的说明，NDP100的Lock口已经被OPS占用。参数表改用”Built-in OPS Control (LOCK Interface)“代替<br />2. 最近NDP100固件已经调整为 3* 2矩阵<br />3. 移除主从描述，因接口被占用，无法实现标准主从教室。 | 2024-08-21    | 陈冰雯、陈觅觅       |

*Status：New，Edited，Added，Deleted



[^1]: 隐藏掉In, Out描述，只体现HOST，Devices<br><img src="../../NMP/UserManual/img/Touch-Following.png"  style="zoom: 39%;" />

