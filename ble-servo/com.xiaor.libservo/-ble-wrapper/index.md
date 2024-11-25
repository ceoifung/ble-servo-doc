---
title: BleWrapper
---
//[ble-servo](../../../index.html)/[com.xiaor.libservo](../index.html)/[BleWrapper](index.html)



# BleWrapper



[androidJvm]\
object [BleWrapper](index.html)



## Types


| Name | Summary |
|---|---|
| [IMessageCallbackListener](-i-message-callback-listener/index.html) | [androidJvm]<br>interface [IMessageCallbackListener](-i-message-callback-listener/index.html) |


## Functions


| Name | Summary |
|---|---|
| [getCurrentHorizontalAngle](get-current-horizontal-angle.html) | [androidJvm]<br>fun [getCurrentHorizontalAngle](get-current-horizontal-angle.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>获取当前的角度，这个是上面设置的，底部的不一定是这个角度，用registerMessageCallback实时监听底部数据回传 |
| [getCurrentVerticalAngle](get-current-vertical-angle.html) | [androidJvm]<br>fun [getCurrentVerticalAngle](get-current-vertical-angle.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>获取当前的角度，这个是上面设置的，底部的不一定是这个角度，用registerMessageCallback实时监听底部数据回传 |
| [registerMessageCallback](register-message-callback.html) | [androidJvm]<br>fun [registerMessageCallback](register-message-callback.html)(callback: [BleWrapper.IMessageCallbackListener](-i-message-callback-listener/index.html))<br>注册蓝牙消息监听器 |
| [requestDataDecode](request-data-decode.html) | [androidJvm]<br>fun [requestDataDecode](request-data-decode.html)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>解析回传数据，在蓝牙接收事件中调用 |
| [setHorizontalMoveAngle](set-horizontal-move-angle.html) | [androidJvm]<br>fun [setHorizontalMoveAngle](set-horizontal-move-angle.html)(angle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>设置水平云台舵机角度 |
| [setHorizontalMoveStep](set-horizontal-move-step.html) | [androidJvm]<br>fun [setHorizontalMoveStep](set-horizontal-move-step.html)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>设置水平云台舵机步幅 |
| [setLight](set-light.html) | [androidJvm]<br>fun [setLight](set-light.html)(color: [LightColor](../-light-color/index.html))<br>设置全部彩灯灯光 |
| [setMotorMoveAngle](set-motor-move-angle.html) | [androidJvm]<br>fun [setMotorMoveAngle](set-motor-move-angle.html)(horizontalAngle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), verticalAngle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>设置水平和云台电机的角度 |
| [setMotorMoveStep](set-motor-move-step.html) | [androidJvm]<br>fun [setMotorMoveStep](set-motor-move-step.html)(horizontalStep: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), verticalStep: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>以步幅的形式设置水平和云台电机的角度 |
| [setSingleLight](set-single-light.html) | [androidJvm]<br>fun [setSingleLight](set-single-light.html)(position: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), color: [LightColor](../-light-color/index.html))<br>设置单个彩灯的亮灭 |
| [setVerticalMoveAngle](set-vertical-move-angle.html) | [androidJvm]<br>fun [setVerticalMoveAngle](set-vertical-move-angle.html)(angle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>设置垂直云台舵机角度 |
| [setVerticalMoveStep](set-vertical-move-step.html) | [androidJvm]<br>fun [setVerticalMoveStep](set-vertical-move-step.html)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>设置垂直云台舵机步幅 |
| [stopMove](stop-move.html) | [androidJvm]<br>fun [stopMove](stop-move.html)()<br>停止所有的电机转动<br>[androidJvm]<br>fun [stopMove](stop-move.html)(motor: [MotorDef](../-motor-def/index.html))<br>停止水平或垂直的电机转动 |

