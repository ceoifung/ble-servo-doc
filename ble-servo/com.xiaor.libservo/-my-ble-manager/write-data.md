---
title: writeData
---
//[ble-servo](../../../index.html)/[com.xiaor.libservo](../index.html)/[MyBleManager](index.html)/[writeData](write-data.html)



# writeData



[androidJvm]\
fun [writeData](write-data.html)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))



发送数据



#### Parameters


androidJvm

| | |
|---|---|
| data | bytes数组 |





[androidJvm]\
fun [writeData](write-data.html)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))



发送数据



#### Parameters


androidJvm

| |
|---|
| data |





[androidJvm]\
fun [~~writeData~~](write-data.html)(context: Context, data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))

---

### Deprecated



do not need context



#### Replace with

```kotlin
writeData(data)
```
---


写数据到蓝牙中去



#### Parameters


androidJvm

| |
|---|
| context |
| data | byte[] 数组 |





[androidJvm]\
fun [~~writeData~~](write-data.html)(context: Context, data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

---

### Deprecated



do not need context



#### Replace with

```kotlin
writeData(data.toByteArray())
```
---



