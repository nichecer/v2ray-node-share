# 免费 V2Ray 节点

这里整理 V2Ray 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-04 20:15:19
- 节点数量：20
- 最低 TCP 延迟：31 ms（美国）
- 国家/地区：IR、俄罗斯、德国、意大利、日本、美国、香港
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
| 🇺🇸 美国_04 | 美国 | VLESS | 31 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 35 ms |
| 🇭🇰 香港_01 | 香港 | VMESS | 36 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 247 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 271 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 276 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 280 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 281 ms |
| 🇯🇵 日本_01 | 日本 | SS | 282 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 284 ms |
| 🇷🇺 俄罗斯_01 | 俄罗斯 | VLESS | 291 ms |
| 🇮🇷 伊朗_01 | IR | VLESS | 305 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 313 ms |
| 🇩🇪 德国_02 | 德国 | VLESS | 317 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 321 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 323 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 330 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 331 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 349 ms |
| 🇺🇸 美国_03 | 美国 | VLESS | 466 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=none&fp=chrome&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_04
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=none&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAxIiwiYWRkIjoiNDcuMjQ0LjEyMC4xOTciLCJwb3J0IjozNjcwMywiYWlkIjowLCJzY3kiOiJhdXRvIiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsInRscyI6IiIsImlkIjoiNDViODM1MTktOWM0Zi00MDUyLWExMWItMDJlMDE3YjYzNmQ0Iiwic2tpcC1jZXJ0LXZlcmlmeSI6dHJ1ZSwicGF0aCI6Ii9hcmtpIn0=
vless://ac36b6f8-d03d-46cb-808f-e655183fb76d@185.44.64.166:59397?encryption=mlkem768x25519plus.native.0rtt.sphudmOm4wKYnBGDTU6kl6-KH7fdQ1VzXp58hEAn3zU&flow=xtls-rprx-vision&security=reality&sni=la.blogs.nvidia.com&fp=chrome&pbk=7w6m1Z7wZk1KX7bBlCi50t_8T-HdC8aMizOcIyqcaS4&sid=1430&type=tcp&headerType=none#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206QmVhVWY5YzBBRVdINDBQdQ==@154.36.158.197:8388#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
vless://b2847c3b-5278-4b06-9c66-bc919d2dfec7@186.246.9.29:443?encryption=none&security=reality&sni=wordpress.com&fp=firefox&pbk=MPNMomAMn_lu9YMYjD2jAQWrI-rTM4hj9Jgg9d6qzTA&sid=50ad5564&type=tcp&headerType=none#%F0%9F%87%B7%F0%9F%87%BA%20%E4%BF%84%E7%BD%97%E6%96%AF_01
vless://e3e0e1c3-599e-4ae1-8ad4-d9e90effacc4@198.16.113.219:8443?&security=reality&flow=xtls-rprx-vision&pbk=8NkTRxC5Q7bptx-8ADobkuhPK-ZN0kEEbzv6tCFGMzE&sid=69984b9e02545831&fp=chrome&sni=www.apple.com&type=tcp&headerType=none&host=www.apple.com&path=%2F#%F0%9F%87%AE%F0%9F%87%B7%20%E4%BC%8A%E6%9C%97_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@13.143.165.126:443?&security=reality&flow=xtls-rprx-vision&pbk=EHlZh1OuiO6gQLTSV2-BVeV0Niv23vvIxQaPvcWCJUw&sid=db382e1979d80ecb&fp=ios&sni=update-26.topp-con.xyz&type=tcp&headerType=none&host=update-26.topp-con.xyz&path=%2F#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_02
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
vless://056405e8-de9f-4d0d-8145-956f13cc34da@79.182.39.57:443?encryption=none&security=reality&sni=a0688bt.us4.h1clayd.click&fp=firefox&pbk=5-9YzvyXcZ4J5Z4OaVTUbxUU2InvnwT17m0XY-Jse1E&sid=257420d9d430152a&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@201.51.4.89:443?encryption=none&flow=xtls-rprx-vision&security=reality&sni=cache-89.topp-con.xyz&fp=chrome&pbk=LEziyH-E4k9hehGRJkVi1FadVObB_NZJy8U7oUCVWXU&sid=b9120cd53ffd7bba&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
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
