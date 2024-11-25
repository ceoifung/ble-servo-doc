---
title: PermissionCheckCallBack
---
//[ble-servo](../../../../index.html)/[com.xiaor.libservo](../../index.html)/[PermissionUtils](../index.html)/[PermissionCheckCallBack](index.html)



# PermissionCheckCallBack



[androidJvm]\
interface [PermissionCheckCallBack](index.html)



## Functions


| Name | Summary |
|---|---|
| [onHasPermission](on-has-permission.html) | [androidJvm]<br>abstract fun [onHasPermission](on-has-permission.html)()<br>用户已授予权限 |
| [onUserHasAlreadyTurnedDown](on-user-has-already-turned-down.html) | [androidJvm]<br>abstract fun [onUserHasAlreadyTurnedDown](on-user-has-already-turned-down.html)(vararg permission: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)<br>用户已拒绝过权限 |
| [onUserHasAlreadyTurnedDownAndDontAsk](on-user-has-already-turned-down-and-dont-ask.html) | [androidJvm]<br>abstract fun [onUserHasAlreadyTurnedDownAndDontAsk](on-user-has-already-turned-down-and-dont-ask.html)(vararg permission: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)<br>用户已拒绝过并且已勾选不再询问选项、用户第一次申请权限; |

