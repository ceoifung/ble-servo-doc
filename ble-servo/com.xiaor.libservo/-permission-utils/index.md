---
title: PermissionUtils
---
//[ble-servo](../../../index.html)/[com.xiaor.libservo](../index.html)/[PermissionUtils](index.html)



# PermissionUtils



[androidJvm]\
object [PermissionUtils](index.html)

权限申请工具类



## Types


| Name | Summary |
|---|---|
| [PermissionCheckCallBack](-permission-check-call-back/index.html) | [androidJvm]<br>interface [PermissionCheckCallBack](-permission-check-call-back/index.html) |
| [PermissionRequestSuccessCallBack](-permission-request-success-call-back/index.html) | [androidJvm]<br>interface [PermissionRequestSuccessCallBack](-permission-request-success-call-back/index.html) |


## Functions


| Name | Summary |
|---|---|
| [checkAndRequestMorePermissions](check-and-request-more-permissions.html) | [androidJvm]<br>fun [checkAndRequestMorePermissions](check-and-request-more-permissions.html)(context: Context?, permissions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>检测并请求多个权限<br>[androidJvm]<br>fun [checkAndRequestMorePermissions](check-and-request-more-permissions.html)(context: Context?, permissions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), callBack: [PermissionUtils.PermissionRequestSuccessCallBack](-permission-request-success-call-back/index.html))<br>检测并申请多个权限 |
| [checkAndRequestPermission](check-and-request-permission.html) | [androidJvm]<br>fun [checkAndRequestPermission](check-and-request-permission.html)(context: Context?, permission: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>检测权限并请求权限：如果没有权限，则请求权限<br>[androidJvm]<br>fun [checkAndRequestPermission](check-and-request-permission.html)(context: Context?, permission: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), callBack: [PermissionUtils.PermissionRequestSuccessCallBack](-permission-request-success-call-back/index.html))<br>检测并申请权限 |
| [checkMorePermissions](check-more-permissions.html) | [androidJvm]<br>fun [checkMorePermissions](check-more-permissions.html)(context: Context?, permissions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;<br>fun [checkMorePermissions](check-more-permissions.html)(context: Context?, permissions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, callBack: [PermissionUtils.PermissionCheckCallBack](-permission-check-call-back/index.html))<br>检测多个权限 |
| [checkPermission](check-permission.html) | [androidJvm]<br>fun [checkPermission](check-permission.html)(context: Context?, permission: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [checkPermission](check-permission.html)(context: Context?, permission: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), callBack: [PermissionUtils.PermissionCheckCallBack](-permission-check-call-back/index.html))<br>检测权限 |
| [onRequestMorePermissionsResult](on-request-more-permissions-result.html) | [androidJvm]<br>fun [onRequestMorePermissionsResult](on-request-more-permissions-result.html)(context: Context?, permissions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, callback: [PermissionUtils.PermissionCheckCallBack](-permission-check-call-back/index.html))<br>用户申请多个权限返回 |
| [onRequestPermissionResult](on-request-permission-result.html) | [androidJvm]<br>fun [onRequestPermissionResult](on-request-permission-result.html)(context: Context?, permission: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, grantResults: [IntArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html), callback: [PermissionUtils.PermissionCheckCallBack](-permission-check-call-back/index.html))<br>用户申请权限返回 |
| [requestMorePermissions](request-more-permissions.html) | [androidJvm]<br>fun [requestMorePermissions](request-more-permissions.html)(context: Context?, permissions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>fun [requestMorePermissions](request-more-permissions.html)(context: Context?, permissionList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>请求多个权限 |
| [requestPermission](request-permission.html) | [androidJvm]<br>fun [requestPermission](request-permission.html)(context: Context?, permission: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), requestCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>请求权限 |
| [toAppSetting](to-app-setting.html) | [androidJvm]<br>fun [toAppSetting](to-app-setting.html)(context: Context)<br>跳转到权限设置界面 |

