# 免费 V2Ray 节点

这里整理 V2Ray 客户端可导入的节点 URI 和订阅，提供固定入口、导入说明和更新信息。

## 本次更新

- 最近成功整理：2026-11-03 08:15:22
- 节点数量：19
- 最低 TCP 延迟：35 ms（美国）
- 国家/地区：IR、印度、德国、意大利、美国、荷兰
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
| 🇺🇸 美国_03 | 美国 | VLESS | 35 ms |
| 🇺🇸 美国_04 | 美国 | VLESS | 37 ms |
| 🇩🇪 德国_01 | 德国 | VLESS | 208 ms |
| 🇮🇳 印度_03 | 印度 | VLESS | 233 ms |
| 🇮🇹 意大利_09 | 意大利 | SS | 256 ms |
| 🇮🇹 意大利_05 | 意大利 | SS | 266 ms |
| 🇮🇹 意大利_01 | 意大利 | SS | 277 ms |
| 🇮🇹 意大利_03 | 意大利 | SS | 277 ms |
| 🇮🇹 意大利_06 | 意大利 | SS | 278 ms |
| 🇮🇹 意大利_10 | 意大利 | SS | 284 ms |
| 🇮🇹 意大利_08 | 意大利 | SS | 295 ms |
| 🇮🇷 伊朗_01 | IR | VLESS | 301 ms |
| 🇮🇹 意大利_07 | 意大利 | SS | 303 ms |
| 🇮🇹 意大利_04 | 意大利 | SS | 307 ms |
| 🇮🇹 意大利_02 | 意大利 | SS | 316 ms |
| 🇺🇸 美国_01 | 美国 | VLESS | 352 ms |
| 🇳🇱 荷兰_01 | 荷兰 | VLESS | 357 ms |
| 🇺🇸 美国_02 | 美国 | VLESS | 391 ms |
| 🇮🇳 印度_02 | 印度 | VLESS | 1256 ms |

[查看完整延迟数据](latency.json)

## 免费节点列表

节点列表最多显示25个，订阅后查看全部节点

```text
vless://0afc6426-606c-48e7-bd70-3c424a416842@us22.sofast.live:58011?encryption=none&security=&type=tcp#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_03
vless://399b6b23-cc40-4831-a494-61948e2df133@jp.sofast.live:52683?encryption=none&security=none&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_04
vless://36fb6650-8a50-42b5-9f66-06538806f32c@de15.h1cloud.net:25362?encryption=none&security=reality&sni=www.chip.de&fp=chrome&pbk=hFee7zTreqlv_wccK_8zxN5v23hj9u-DshByvGf-KAA&sid=23732d14a527990d&type=tcp&headerType=none&insecure=1#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD_01
vless://5e679ccd-1586-4d5f-b87b-48251046cad8@5.253.28.240:2443?encryption=none&security=reality&sni=deepl.com&fp=qq&pbk=h85e28MxBgNyT9d9cNeOLVtWfHq6cT_1_oxZOTajtTg&sid=92c32de179e5d908&type=grpc&authority=&serviceName=rex-eb0bf76b710ce763&mode=gun#%F0%9F%87%AE%F0%9F%87%B3%20%E5%8D%B0%E5%BA%A6_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.45:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_09
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.90:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_05
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.99:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.54:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_03
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.81:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_06
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.18:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_10
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.36:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_08
vless://f47057d5-120d-4b42-b6d6-30469aef6813@tunell2027.crackerbinam.org:48312?encryption=none&security=reality&sni=www.cloudflare.com&fp=chrome&pbk=d9eM_jy8ztZrOf3DMq1m55VQSo7bnKcG1dRnO9ktJ2Y&sid=902c315efc&type=tcp&headerType=http#%F0%9F%87%AE%F0%9F%87%B7%20%E4%BC%8A%E6%9C%97_01
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.72:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_07
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.63:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_04
ss://YWVzLTI1Ni1nY206WlJwZ2FCZUd4dEVOSVhndmhwa1pCS3o5R25XUlMyZFljeDlPK2EyaXdOND0=@202.50.253.27:19999#%F0%9F%87%AE%F0%9F%87%B9%20%E6%84%8F%E5%A4%A7%E5%88%A9_02
vless://056405e8-de9f-4d0d-8145-956f13cc34da@79.182.39.57:443?encryption=none&security=reality&sni=a0688bt.us4.h1clayd.click&fp=firefox&pbk=5-9YzvyXcZ4J5Z4OaVTUbxUU2InvnwT17m0XY-Jse1E&sid=257420d9d430152a&type=tcp&headerType=none#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_01
vless://b2847c3b-5278-4b06-9c66-bc919d2dfec7@186.246.9.29:443?encryption=none&security=reality&sni=wordpress.com&fp=firefox&pbk=MPNMomAMn_lu9YMYjD2jAQWrI-rTM4hj9Jgg9d6qzTA&sid=50ad5564&type=tcp&headerType=none&insecure=1#%F0%9F%87%B3%F0%9F%87%B1%20%E8%8D%B7%E5%85%B0_01
vless://7ad63b26-bf70-4872-8fab-ebaf73a1e19d@201.51.4.89:443?&security=reality&flow=xtls-rprx-vision&pbk=LEziyH-E4k9hehGRJkVi1FadVObB_NZJy8U7oUCVWXU&sid=b9120cd53ffd7bba&fp=chrome&sni=cache-89.topp-con.xyz&type=tcp&headerType=none&host=cache-89.topp-con.xyz&path=%2F#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD_02
vless://5e679ccd-1586-4d5f-b87b-48251046cad8@hydra.yokkastars.com:2443?encryption=none&security=reality&sni=deepl.com&fp=qq&pbk=h85e28MxBgNyT9d9cNeOLVtWfHq6cT_1_oxZOTajtTg&sid=92c32de179e5d908&type=grpc&authority=&serviceName=rex-eb0bf76b710ce763&mode=gun#%F0%9F%87%AE%F0%9F%87%B3%20%E5%8D%B0%E5%BA%A6_02
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
