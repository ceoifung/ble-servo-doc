---
title: Protocol
---
//[ble-servo](../../../index.html)/[com.xiaor.libservo](../index.html)/[Protocol](index.html)



# Protocol



[androidJvm]\
object [Protocol](index.html)



## Properties


| Name | Summary |
|---|---|
| [CTL_KEY1_STATUS](-c-t-l_-k-e-y1_-s-t-a-t-u-s.html) | [androidJvm]<br>val [CTL_KEY1_STATUS](-c-t-l_-k-e-y1_-s-t-a-t-u-s.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 2 |
| [CTL_KEY2_STATUS](-c-t-l_-k-e-y2_-s-t-a-t-u-s.html) | [androidJvm]<br>val [CTL_KEY2_STATUS](-c-t-l_-k-e-y2_-s-t-a-t-u-s.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 3 |
| [CTL_LIGHT](-c-t-l_-l-i-g-h-t.html) | [androidJvm]<br>val [CTL_LIGHT](-c-t-l_-l-i-g-h-t.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 3 |
| [CTL_POWER_STATUS](-c-t-l_-p-o-w-e-r_-s-t-a-t-u-s.html) | [androidJvm]<br>val [CTL_POWER_STATUS](-c-t-l_-p-o-w-e-r_-s-t-a-t-u-s.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 4 |
| [CTL_RECV](-c-t-l_-r-e-c-v.html) | [androidJvm]<br>val [CTL_RECV](-c-t-l_-r-e-c-v.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 1 |
| [CTL_SERVO](-c-t-l_-s-e-r-v-o.html) | [androidJvm]<br>val [CTL_SERVO](-c-t-l_-s-e-r-v-o.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 0 |
| [CTL_STOP](-c-t-l_-s-t-o-p.html) | [androidJvm]<br>val [CTL_STOP](-c-t-l_-s-t-o-p.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 0 |
| [header](header.html) | [androidJvm]<br>val [header](header.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [tail](tail.html) | [androidJvm]<br>val [tail](tail.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [TYPE_LIGHT](-t-y-p-e_-l-i-g-h-t.html) | [androidJvm]<br>val [TYPE_LIGHT](-t-y-p-e_-l-i-g-h-t.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 2 |
| [TYPE_RECV](-t-y-p-e_-r-e-c-v.html) | [androidJvm]<br>val [TYPE_RECV](-t-y-p-e_-r-e-c-v.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [TYPE_SERVO](-t-y-p-e_-s-e-r-v-o.html) | [androidJvm]<br>val [TYPE_SERVO](-t-y-p-e_-s-e-r-v-o.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) = 1 |


## Functions


| Name | Summary |
|---|---|
| [calculateCRC](calculate-c-r-c.html) | [androidJvm]<br>fun [calculateCRC](calculate-c-r-c.html)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), len: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)<br>crc校验 |
| [createMessage](create-message.html) | [androidJvm]<br>fun [createMessage](create-message.html)(vararg data: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)<br>创建消息 |

