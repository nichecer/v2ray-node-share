# 免费 V2Ray 节点

这里整理 V2Ray 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-10-30 20:15:22
- 节点数量：17
- 最低 TCP 延迟：6 ms（中国大陆）
- 国家/地区：中国大陆、俄罗斯、加拿大、意大利、瑞典、美国、荷兰、香港
- 定时更新：**08:00、20:00**
- 节点协议：VMess、VLESS、Trojan、Shadowsocks。

## 订阅入口

| 文件 | 地址 | 用途 |
| --- | --- | --- |
| Base64 订阅 | [sub.txt](https://raw.githubusercontent.com/nichecer/v2ray-node-share/main/sub.txt) | 在兼容的 V2Ray 客户端中添加订阅 |
| 明文节点 | [nodes.txt](https://raw.githubusercontent.com/nichecer/v2ray-node-share/main/nodes.txt) | 按需复制单条节点并导入 |

### 订阅二维码

![V2Ray 订阅二维码](sub.svg)

## 节点延迟

延迟信息最多显示25个，订阅后查看全部节点

| 节点名称 | 国家/地区 | 协议 | TCP 延迟 |
| --- | --- | --- | ---: |
| 🇨🇳 中国_01 | 中国大陆 | VLESS | 6 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 32 ms |
| 🇭🇰 香港_02 | 香港 | VMESS | 36 ms |
| 🇸🇪 瑞典_01 | 瑞典 | VLESS | 216 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | VLESS | 250 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 271 ms |
| 🇨🇦 加拿大_01 | 加拿大 | VLESS | 285 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 312 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 315 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 319 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 319 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 328 ms |
| 🇮🇹 意大利_11 | 意大利 | SS | 335 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 340 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 342 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 362 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 370 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=&type=tcp#%F0%9F%87%A8%F0%9F%87%B3%20%E4%B8%AD%E5%9B%BD_01
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAyIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjoiMjMwMjYiLCJ0eXBlIjoibm9uZSIsImlkIjoiYjlkZTFiYzktYmFhNy00MWFjLTg2ZjctY2NkNTk2OTVjYjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmtpIiwiaG9zdCI6IjQ3LjI0NC4xMjAuMTk3IiwidGxzIjoiIn0=
vless://f8d52ece-fad4-478d-875d-df6eed3befa7@se-2.pythonsetupbib.online:61374?security=reality&type=xhttp&path=%2F&host=se-2.pythonsetupbib.online&packetEncoding=xudp&sni=se-2.pythonsetupbib.online&fp=chrome&pbk=QrNs0ew7snHqLfpVXS9RAhlRzgAzzGZK9fXmDcx9xHI&mode=packet-up&extra=%7B%22xPaddingBytes%22%3A%22100-500%22%2C%22xmux%22%3A%7B%22maxConnections%22%3A%223%22%7D%7D&encryption=none#%F0%9F%87%B8%F0%9F%87%AA%20%E7%91%9E%E5%85%B8_01
vless://9ea8b000-58ce-0005-b108-989dd4f248f1@146.185.197.95:443?security=none&type=ws&path=%2Flive%2Fws2&packetEncoding=xudp&encryption=mlkem768x25519plus.native.0rtt.8th1uEEPtl2BhPfgxINwmVO_Kq6V1htSghiTMdjWkRM#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
vless://6c713691-3ca2-4446-ad25-113d1bed6b03@78.17.178.125:443?security=reality&encryption=none&pbk=jcp4Lj_qYzxtkalm_XFjrmvqEMGRG7sb19yMwLe16WE&headerType=none&fp=chrome&type=tcp&flow=xtls-rprx-vision&sni=cdn.tbank.ru&sid=e0215064d8d1fd7c#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://e5cc16a6-ea42-46b2-82ae-ad2157e1641b@104.17.162.11:2082?security=none&type=ws&path=%2F&host=hhlfy.twiladaphne.ndjp.net&packetEncoding=xudp#%F0%9F%87%A8%F0%9F%87%A6%20%E5%8A%A0%E6%8B%BF%E5%A4%A7_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://b2847c3b-5278-4b06-9c66-bc919d2dfec7@186.246.9.29:443?security=reality&type=raw&packetEncoding=xudp&sni=wordpress.com&fp=firefox&sid=50ad5564&pbk=MPNMomAMn_lu9YMYjD2jAQWrI-rTM4hj9Jgg9d6qzTA#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My45MDoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_11
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My40NToxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My44MToxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND1AMjAyLjUwLjI1My43MjoxOTk5OQ==#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
```

## 反馈

欢迎在 Issues 反馈失效链接和导入问题，请说明客户端版本及错误提示，不要提交个人密码或私有订阅。

请遵守所在地法律法规及服务条款，谨慎通过公共代理传输敏感信息。

## 各平台客户端下载

### Windows

| 客户端 | 下载地址 |
| --- | --- |
| v2rayN | [GitHub 发布页](https://github.com/2dust/v2rayN/releases) |
| Hiddify | [GitHub 发布页](https://github.com/hiddify/hiddify-app/releases) |

### Android

| 客户端 | 下载地址 |
| --- | --- |
| v2rayNG | [GitHub 发布页](https://github.com/2dust/v2rayNG/releases) |
| Hiddify | [GitHub 发布页](https://github.com/hiddify/hiddify-app/releases) |

### iOS / iPadOS

| 客户端 | 下载地址 |
| --- | --- |
| Shadowrocket（小火箭） | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |

### macOS

| 客户端 | 下载地址 |
| --- | --- |
| v2rayN | [GitHub 发布页](https://github.com/2dust/v2rayN/releases) |
| Hiddify | [GitHub 发布页](https://github.com/hiddify/hiddify-app/releases) |

### Linux

| 客户端 | 下载地址 |
| --- | --- |
| v2rayN | [GitHub 发布页](https://github.com/2dust/v2rayN/releases) |
| Hiddify | [GitHub 发布页](https://github.com/hiddify/hiddify-app/releases) |

下载时选择对应系统和处理器架构的安装包。App Store 的可用地区和价格以商店页面为准。
