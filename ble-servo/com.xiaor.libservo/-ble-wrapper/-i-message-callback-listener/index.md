---
title: IMessageCallbackListener
---
//[ble-servo](../../../../index.html)/[com.xiaor.libservo](../../index.html)/[BleWrapper](../index.html)/[IMessageCallbackListener](index.html)



# IMessageCallbackListener



[androidJvm]\
interface [IMessageCallbackListener](index.html)



## Functions


| Name | Summary |
|---|---|
| [onBoardStatusCallback](on-board-status-callback.html) | [androidJvm]<br>abstract fun [onBoardStatusCallback](on-board-status-callback.html)(boardMsg: [BoardMsg](../../-board-msg/index.html))<br>板子状态消息回调 |
| [onKeyStatusCallback](on-key-status-callback.html) | [androidJvm]<br>abstract fun [onKeyStatusCallback](on-key-status-callback.html)(keyMsg: [KeyMsg](../../-key-msg/index.html))<br>按键的的回调 |
| [onPowerStatusCallback](on-power-status-callback.html) | [androidJvm]<br>abstract fun [onPowerStatusCallback](on-power-status-callback.html)(powerStatus: [PowerStatus](../../-power-status/index.html))<br>开关机按键的回调 |
| [onRawDataCallback](on-raw-data-callback.html) | [androidJvm]<br>abstract fun [onRawDataCallback](on-raw-data-callback.html)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>原始数据 |

