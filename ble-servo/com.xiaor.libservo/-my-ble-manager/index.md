---
title: MyBleManager
---
//[ble-servo](../../../index.html)/[com.xiaor.libservo](../index.html)/[MyBleManager](index.html)



# MyBleManager



[androidJvm]\
class [MyBleManager](index.html)



## Constructors


| | |
|---|---|
| [MyBleManager](-my-ble-manager.html) | [androidJvm]<br>constructor() |


## Types


| Name | Summary |
|---|---|
| [BleReceiver](-ble-receiver/index.html) | [androidJvm]<br>class [BleReceiver](-ble-receiver/index.html) : BroadcastReceiver |
| [BleStatusListener](-ble-status-listener/index.html) | [androidJvm]<br>interface [BleStatusListener](-ble-status-listener/index.html) |
| [Companion](-companion/index.html) | [androidJvm]<br>object [Companion](-companion/index.html) |
| [InstanceManger](-instance-manger/index.html) | [androidJvm]<br>class [InstanceManger](-instance-manger/index.html) |


## Properties


| Name | Summary |
|---|---|
| [nearRssi](near-rssi.html) | [androidJvm]<br>var [nearRssi](near-rssi.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Functions


| Name | Summary |
|---|---|
| [cancelScan](cancel-scan.html) | [androidJvm]<br>fun [cancelScan](cancel-scan.html)() |
| [connectBle](connect-ble.html) | [androidJvm]<br>fun [connectBle](connect-ble.html)() |
| [destroy](destroy.html) | [androidJvm]<br>fun [destroy](destroy.html)() |
| [disableBle](disable-ble.html) | [androidJvm]<br>fun [disableBle](disable-ble.html)(context: Context) |
| [disconnect](disconnect.html) | [androidJvm]<br>fun [disconnect](disconnect.html)() |
| [enableBle](enable-ble.html) | [androidJvm]<br>fun [enableBle](enable-ble.html)(context: Context) |
| [getRssi](get-rssi.html) | [androidJvm]<br>fun [getRssi](get-rssi.html)() |
| [init](init.html) | [androidJvm]<br>fun [init](init.html)(application: Application)<br>全局注册 |
| [isBleEnable](is-ble-enable.html) | [androidJvm]<br>fun [isBleEnable](is-ble-enable.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onRequestPermissionsResult](on-request-permissions-result.html) | [androidJvm]<br>fun [onRequestPermissionsResult](on-request-permissions-result.html)(context: Context, requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), listener: [MyBleManager.BleStatusListener](-ble-status-listener/index.html)?)<br>连接蓝牙回调 |
| [requestPermissions](request-permissions.html) | [androidJvm]<br>fun [requestPermissions](request-permissions.html)(context: Context)<br>请求近场连接蓝牙权限 |
| [scanAndConnectBle](scan-and-connect-ble.html) | [androidJvm]<br>fun [scanAndConnectBle](scan-and-connect-ble.html)(context: Context) |
| [setMtu](set-mtu.html) | [androidJvm]<br>fun [setMtu](set-mtu.html)(mtu: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [startNotify](start-notify.html) | [androidJvm]<br>fun [startNotify](start-notify.html)() |
| [unregisterBleReceiver](unregister-ble-receiver.html) | [androidJvm]<br>fun [unregisterBleReceiver](unregister-ble-receiver.html)(context: Context) |
| [writeData](write-data.html) | [androidJvm]<br>fun [writeData](write-data.html)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>fun [writeData](write-data.html)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>发送数据<br>[androidJvm]<br>fun [~~writeData~~](write-data.html)(context: Context, data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>写数据到蓝牙中去<br>[androidJvm]<br>fun [~~writeData~~](write-data.html)(context: Context, data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

