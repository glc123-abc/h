proxies:
  - {name: 🇸🇬 新加坡2 NF|华南移动|V2, server: rxzgzq.moox.icu, port: 34019, type: vmess, uuid: 3ed7ef7a-5f66-47c8-9da1-a11852ccb7a4, alterId: 1, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-path: /, ws-headers: {Host: rxzgzq.moox.icu}}
  - {name: 微信公众号：天泽玩机, server: rxzgzq.moox.icu, port: 34006, type: vmess, uuid: 3ed7ef7a-5f66-47c8-9da1-a11852ccb7a4, alterId: 1, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-path: /, ws-headers: {Host: rxzgzq.moox.icu}}
  - {name: 🇸🇬 直连 | 新加坡 DO 01, server: 165.22.103.3, port: 80, type: vmess, uuid: 5f33138a-9704-4637-a51a-b6b6e877e6b6, alterId: 1, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-path: /, ws-headers: {Host: 165.22.103.3}}
  - {name: 🇸🇬 新加坡1 NF|华南移动|V3, server: rxzgzq.moox.icu, port: 34015, type: vmess, uuid: 3ed7ef7a-5f66-47c8-9da1-a11852ccb7a4, alterId: 1, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-path: /, ws-headers: {Host: rxzgzq.moox.icu}}
  - {name: 🇸🇬 新加坡3 NF|广州移动|V3, server: 183.236.97.87, port: 40006, type: vmess, uuid: 3ed7ef7a-5f66-47c8-9da1-a11852ccb7a4, alterId: 1, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-path: /, ws-headers: {Host: 183.236.97.87}}
  - {name: 🇸🇬 新加坡4 NF|广州移动|V2, server: icajm.moox.icu, port: 40007, type: vmess, uuid: 3ed7ef7a-5f66-47c8-9da1-a11852ccb7a4, alterId: 1, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-path: /, ws-headers: {Host: icajm.moox.icu}}
  - {name: 🇯🇵 直连 | 日本 AZURE 1, server: 20.46.166.193, port: 80, type: vmess, uuid: 5f33138a-9704-4637-a51a-b6b6e877e6b6, alterId: 1, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-path: /, ws-headers: {Host: 20.46.166.193}}
  - {name: 🇸🇬 新加坡01丨解锁丨隧道优化, server: sd.djsym.com, port: 50027, type: vmess, uuid: e768371f-8525-3483-940e-8695260390a2, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-path: /qq, ws-headers: {Host: sd.djsym.com}}
proxy-groups:
  - name: 🚀 节点选择
    type: select
    proxies:
      - ♻️ 自动选择
      - DIRECT
      - 🇸🇬 新加坡2 NF|华南移动|V2
      - 微信公众号：天泽玩机
      - 🇸🇬 直连 | 新加坡 DO 01
      - 🇸🇬 新加坡1 NF|华南移动|V3
      - 🇸🇬 新加坡3 NF|广州移动|V3
      - 🇸🇬 新加坡4 NF|广州移动|V2
      - 🇯🇵 直连 | 日本 AZURE 1
      - 🇸🇬 新加坡01丨解锁丨隧道优化
  - name: ♻️ 自动选择
    type: url-test
    url: http://www.gstatic.com/generate_204
    interval: 300
    proxies:
      - 🇸🇬 新加坡2 NF|华南移动|V2
      - 微信公众号：天泽玩机
      - 🇸🇬 直连 | 新加坡 DO 01
      - 🇸🇬 新加坡1 NF|华南移动|V3
      - 🇸🇬 新加坡3 NF|广州移动|V3
      - 🇸🇬 新加坡4 NF|广州移动|V2
      - 🇯🇵 直连 | 日本 AZURE 1
      - 🇸🇬 新加坡01丨解锁丨隧道优化
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🎯 全球直连
      - 🇸🇬 新加坡2 NF|华南移动|V2
      - 微信公众号：天泽玩机
      - 🇸🇬 直连 | 新加坡 DO 01
      - 🇸🇬 新加坡1 NF|华南移动|V3
      - 🇸🇬 新加坡3 NF|广州移动|V3
      - 🇸🇬 新加坡4 NF|广州移动|V2
      - 🇯🇵 直连 | 日本 AZURE 1
      - 🇸🇬 新加坡01丨解锁丨隧道优化
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 🇸🇬 新加坡2 NF|华南移动|V2
      - 微信公众号：天泽玩机
      - 🇸🇬 直连 | 新加坡 DO 01
      - 🇸🇬 新加坡1 NF|华南移动|V3
      - 🇸🇬 新加坡3 NF|广州移动|V3
      - 🇸🇬 新加坡4 NF|广州移动|V2
      - 🇯🇵 直连 | 日本 AZURE 1
      - 🇸🇬 新加坡01丨解锁丨隧道优化
  - name: Ⓜ️ 微软服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 🇸🇬 新加坡2 NF|华南移动|V2
      - 微信公众号：天泽玩机
      - 🇸🇬 直连 | 新加坡 DO 01
      - 🇸🇬 新加坡1 NF|华南移动|V3
      - 🇸🇬 新加坡3 NF|广州移动|V3
      - 🇸🇬 新加坡4 NF|广州移动|V2
      - 🇯🇵 直连 | 日本 AZURE 1
      - 🇸🇬 新加坡01丨解锁丨隧道优化
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 🇸🇬 新加坡2 NF|华南移动|V2
      - 微信公众号：天泽玩机
      - 🇸🇬 直连 | 新加坡 DO 01
      - 🇸🇬 新加坡1 NF|华南移动|V3
      - 🇸🇬 新加坡3 NF|广州移动|V3
      - 🇸🇬 新加坡4 NF|广州移动|V2
      - 🇯🇵 直连 | 日本 AZURE 1
      - 🇸🇬 新加坡01丨解锁丨隧道优化
  - name: 📢 谷歌FCM
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - ♻️ 自动选择
      - 🇸🇬 新加坡2 NF|华南移动|V2
      - 微信公众号：天泽玩机
      - 🇸🇬 直连 | 新加坡 DO 01
      - 🇸🇬 新加坡1 NF|华南移动|V3
      - 🇸🇬 新加坡3 NF|广州移动|V3
      - 🇸🇬 新加坡4 NF|广州移动|V2
      - 🇯🇵 直连 | 日本 AZURE 1
      - 🇸🇬 新加坡01丨解锁丨隧道优化
  - name: 🎯 全球直连
    type: select
    proxies:
      - DIRECT
      - 🚀 节点选择
      - ♻️ 自动选择
  - name: 🛑 全球拦截
    type: select
    proxies:
      - REJECT
      - DIRECT
  - name: 🍃 应用净化
    type: select
    proxies:
      - REJECT
      - DIRECT
  - name: 🐟 漏网之鱼
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - ♻️ 自动选择
      - 🇸🇬 新加坡2 NF|华南移动|V2
      - 微信公众号：天泽玩机
      - 🇸🇬 直连 | 新加坡 DO 01
      - 🇸🇬 新加坡1 NF|华南移动|V3
      - 🇸🇬 新加坡3 NF|广州移动|V3
      - 🇸🇬 新加坡4 NF|广州移动|V2
      - 🇯🇵 直连 | 日本 AZURE 1
      - 🇸🇬 新加坡01丨解锁丨隧道优化
rules:
 - GEOIP,CN,🎯 全球直连
 - MATCH,🐟 漏网之鱼
