# 群管理

<!-- ### 🚫获取群资料信息

暂不对外开放

### 🚫获取机器人加入群列表

暂不对外开放 -->

<!-- ## 群成员

### 获取群内成员列表

\[内邀开放\]

::: tip 说明
获取群成员 openid 列表
:::

- **请求**

<table>
	<tr>
	  <th colspan="2">基本</th>
	</tr>
  <tr>
    <td>HTTP URL</td>
    <td>/v2/groups/{group_openid}/members</td>
	</tr>
  <tr>
    <td>HTTP Method</td>
    <td>POST</td>
	</tr>
</table>

- **路径参数**

| **属性** | **类型** | **必填** | **说明** |
| --- | --- | --- | --- |
| group_openid | string | 是 | 群聊的 openid |

- **请求参数**

| **属性** | **类型** | **必填** | **说明** |
| --- | --- | --- | --- |
| limit | int | 否 | 每页限制数量 1-500 |
| start_index | int | 否 | 首页输入 0，后续填入返回参数的 next_index |

- **返回参数**

| **属性** | **类型** | **说明** |
| --- | --- | --- |
| members | object[] | openid 列表{member_openid:'',join_timestamp: 0} |
| next_index | int | 下一页的拉取标记位 |

- **错误码**

 -->

<!-- ### 事件

#### 🚫用户加入群聊

暂不对外开放

#### 🚫用户退出群聊

暂不对外开放

## 三方平台

### 🚫获取小程序链接

暂不对外开放 -->
