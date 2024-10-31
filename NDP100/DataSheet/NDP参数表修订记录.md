# NDP参数表修订记录

[toc]



## NDP100 v3

| Version    | Status | Description                                                  | Date Modified | Modifier/Contributor   |
| ---------- | ------ | ------------------------------------------------------------ | ------------- | ---------------------- |
| 2024-10-14 | Add    | 新增参数表，提交给市场部                                     | 2024-10-15    | Lee                    |
| 2024-10-15 | Add    | 新增NDP100产品重量数据：<br />净重：90千克<br />毛重：90 + 36 + 5 = 131千克[^2] | 2024-10-15    | 剑锋、何凯、狄霞、王力 |
| 2024-10-22 | Edited | 1. 调整“Interactive Pen Display-Surface"玻璃铅笔硬度为6H（原7是莫氏硬度）<br />2. 调整Interactive Pen Display的built-in speaker 为“4Ω 3W” （原 4Ω 3W * 2） | 2024-10-22    | 王力、陈珂             |



[^2]: 1): 刚才称的数据是85千克，再加上展台小配件 按照90千克来算<br>2): 木箱(不带底座版） 31.35KG，带底座要算个36kg<br>3):V3版后面的货木箱又加高了6公分，再加5公斤来算吧<br><img src="./img/image-20241015142701060.png" alt="image-20241015142701060" style="zoom:67%;" /><img src="./img/image-20241015142737625.png" alt="image-20241015142737625" style="zoom:87%;" /><br>



## NDP100 v2 / NMP211



| Version                                                  | Status  | Description                                                  | Date Modified | Modifier/Contributor |
| -------------------------------------------------------- | ------- | ------------------------------------------------------------ | ------------- | -------------------- |
| 202405                                                   | Edited  | 1. 调整广播、流媒体参数表,移除掉原来诸多协议，对分辨率和码率做最新的更新调整（1080p@30fps recommended,  up to 4K@30fps）<br />2. 原格式支持参数（audio format, video format)合并到广播参数描述中<br />3. Communication Interface的USB接口描述调整[^1]<br />4. 拆分Power Control，并调整Power Control的描述<br />5. 调整 Phoenix 4-Pin的描述<br />6. 调整功放接口描述<br /> | 2024-05-24    | Lee                  |
| 202405-v2                                                | Edited  | 1. 调整 IR-IN，IR-OUT参数描述<br />2. Single pole double throw（SPDT） switch (External port) * 1；调整为“ External port (RELAY) * 1”<br />3. “Audio matrix module”名称调整为”Audio",因为矩阵还包含了DHMI OUT A | 2024-05-24    |                      |
| [NDP100 v2-2024-08-21.xlsx](./NDP100 v2-2024-08-21.xlsx) | Deleted | 1. 移除掉Lock接口锁的说明，NDP100的Lock口已经被OPS占用。参数表改用”Built-in OPS Control (LOCK Interface)“代替<br />2. 最近NDP100固件已经调整为 3* 2矩阵<br />3. 移除主从描述，因接口被占用，无法实现标准主从教室。 | 2024-08-21    | 陈冰雯、陈觅觅       |

*Status：New，Edited，Added，Deleted



[^1]: 隐藏掉In, Out描述，只体现HOST，Devices<br><img src="../../NMP/UserManual/img/Touch-Following.png"  style="zoom: 39%;" />



## NDP500

| Version   | Status | Description                                                  | Date Modified | Modifier/Contributor |
| --------- | ------ | ------------------------------------------------------------ | ------------- | -------------------- |
| 202405    | Edited | 1. Surface玻璃参数为AG+AF<br />2. 移除电容触控的”Compatible operating systems“对于”Android和Mac"的支持情况（后续继续跟进）<br />3. 移除Audio out的mixed描述，有疑问再说<br />4. 移除 USB接口对于 In, Out的描述，统一改成Host, Device以减少困惑 <br />5. 移除 Communication interface下的“Phoenix 4 Pin *1;”接口<br />6. 调整“Power amplifier”描述<br />7. 调整Antenna参数描述<br />8. 拆分Power Control，并调整Power Control的描述<br />9. 调整广播、流媒体参数表,移除掉原来诸多协议，对分辨率和码率做最新的更新调整<br /> | 2024-05-24    | Lee                  |
| 202405-v2 | Edited | 1. 调整HDMI Matrix为 HDMI Port名称<br />2. 移除“Handwriting Specification”下的“Signal Interface”选项。<br />3. Single pole double throw（SPDT） switch (External port) * 1；调整为“ External port (RELAY) * 1” | 2024-05-24    |                      |





## References

1. smb://192.168.10.168/IQ-国际事业部/4.跨部门共享区/1.售前支持Pre-sales/2. 营销工具（彩页&参数表&图片&视频等）Marketing materials/9.Q-NEX产品线/01 Brochure&Datasheet&Manuals/
1. [smb://192.168.10.168/IQ-国际事业部/4.跨部门共享区/1.售前支持Pre-sales/2. 营销工具（彩页&参数表&图片&视频等）Marketing materials/4.图片Product pictures/00 产品图片-2024 products/QNEX/01 产品图 Products](smb://192.168.10.168/IQ-国际事业部/4.跨部门共享区/1.售前支持Pre-sales/2. 营销工具（彩页&参数表&图片&视频等）Marketing materials/4.图片Product pictures/00 产品图片-2024 products/QNEX/01 产品图 Products)
