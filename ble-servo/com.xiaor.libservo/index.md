---
title: com.xiaor.libservo
---
//[ble-servo](../../index.html)/[com.xiaor.libservo](index.html)



# Package-level declarations



## Types


| Name | Summary |
|---|---|
| [BleStatus](-ble-status/index.html) | [androidJvm]<br>enum [BleStatus](-ble-status/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[BleStatus](-ble-status/index.html)&gt; |
| [BleWrapper](-ble-wrapper/index.html) | [androidJvm]<br>object [BleWrapper](-ble-wrapper/index.html) |
| [BoardMsg](-board-msg/index.html) | [androidJvm]<br>data class [BoardMsg](-board-msg/index.html)(var horizontalAngle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), var verticalAngle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), var batteryVoltage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), var isHorizontalInCtl: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), var isVerticalInCtl: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>板子的回传数据 |
| [KeyMsg](-key-msg/index.html) | [androidJvm]<br>data class [KeyMsg](-key-msg/index.html)(var id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), var status: [KeyStatus](-key-status/index.html))<br>按键消息 |
| [KeyStatus](-key-status/index.html) | [androidJvm]<br>enum [KeyStatus](-key-status/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[KeyStatus](-key-status/index.html)&gt; <br>控制板按键状态事件 |
| [LightColor](-light-color/index.html) | [androidJvm]<br>enum [LightColor](-light-color/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[LightColor](-light-color/index.html)&gt; <br>灯光颜色通道值 |
| [MotorDef](-motor-def/index.html) | [androidJvm]<br>enum [MotorDef](-motor-def/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[MotorDef](-motor-def/index.html)&gt; <br>电机的定义 |
| [MyBleManager](-my-ble-manager/index.html) | [androidJvm]<br>class [MyBleManager](-my-ble-manager/index.html) |
| [PermissionUtils](-permission-utils/index.html) | [androidJvm]<br>object [PermissionUtils](-permission-utils/index.html)<br>权限申请工具类 |
| [PowerStatus](-power-status/index.html) | [androidJvm]<br>enum [PowerStatus](-power-status/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[PowerStatus](-power-status/index.html)&gt; <br>控制板电源状态事件 |
| [Protocol](-protocol/index.html) | [androidJvm]<br>object [Protocol](-protocol/index.html) |
| [XRConstant](-x-r-constant/index.html) | [androidJvm]<br>object [XRConstant](-x-r-constant/index.html) |

