---
title: BoardMsg
---
//[ble-servo](../../../index.html)/[com.xiaor.libservo](../index.html)/[BoardMsg](index.html)



# BoardMsg



[androidJvm]\
data class [BoardMsg](index.html)(var horizontalAngle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), var verticalAngle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), var batteryVoltage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), var isHorizontalInCtl: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), var isVerticalInCtl: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

板子的回传数据

```kotlin
horizontalAngle: 水平云台电机角度
verticalAngle: 垂直云台电机角度
batteryVoltage: 电池电压
isHorizontalInCtl: 水平云台电机受控状态和非受控状态，true为受控，false为非受控
isVerticalInCtl: 垂直云台电机受控状态和非受控状态，true为受控，false为非受控
```



## Constructors


| | |
|---|---|
| [BoardMsg](-board-msg.html) | [androidJvm]<br>constructor(horizontalAngle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), verticalAngle: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), batteryVoltage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), isHorizontalInCtl: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), isVerticalInCtl: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [batteryVoltage](battery-voltage.html) | [androidJvm]<br>var [batteryVoltage](battery-voltage.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [horizontalAngle](horizontal-angle.html) | [androidJvm]<br>var [horizontalAngle](horizontal-angle.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isHorizontalInCtl](is-horizontal-in-ctl.html) | [androidJvm]<br>var [isHorizontalInCtl](is-horizontal-in-ctl.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVerticalInCtl](is-vertical-in-ctl.html) | [androidJvm]<br>var [isVerticalInCtl](is-vertical-in-ctl.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [verticalAngle](vertical-angle.html) | [androidJvm]<br>var [verticalAngle](vertical-angle.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

