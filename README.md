# CCNA2020_WirelessLAN
無線區域網路

# 數據傳輸的媒介選擇

依照地理物理距離由大而小：

* Microwave, 微波（跨星球距離）

  數字微波傳輸設備、衛星等通常採用正交幅度調製。
  QAM調製方式同時利用信號的幅度和相位加載信息。
  這樣，可以在同樣的帶寬上傳遞更大的數據量。

* Wi-Fi（民眾使用的主流媒介）

   IEEE 802.11
   
   是當前『無線區域網』的標準，採用2GHz或5GHz頻段，數據傳輸速率為11 Mbps或54 Mbps。

* Zigbee, 紫蜂

   IEEE 802.15.4 為短距無線通訊其中的『 低功耗個域網協議 | 低速率無線個域網 』。
   據此協議的技術是一種短距離、低功耗的無線通信技術。
   ZigBee主要適用於自動控制和遠程控制領域，支持地理定位功能，是一種介於無線標記技術和藍牙技術之間的技術提案。
   
   Zig-Bee主要特點是工作頻段免執照； 1個節點工作6～24個月；協議簡單且免費，成本低廉。

     目前愛鳳11的 airdrop 均採用紫蜂取代藍芽，因為比較安全也省電。
     版主之前逛世貿網路展，發現滿多智慧家電都會帶著紫蜂標示的。

* BLE, 藍牙（可能被紫蜂取代）

     是一種『 短距離無線通訊的技術 』。

# 無線網路的應用：

汽車導航 、 OTT 電視、VoIP 電話、手機顯示。

# LLC, 鏈結層網路元件

由 IEEE 802.2 標準定義。

除了乙太網路外，光纖的 FDDI 和無線網路 WLAN 的 802.11 標準都會與 LLC 搭配使用。

# IEEE 802.11 標準的發展

1997 略

1999 802.11b 對於 ISM 頻道給予 2.4GHz 的頻段上，其最大吞吐量介於 6-7mbps，缺點是與藍芽、紫蜂在同一頻段，會互相影響。

2003 802.11g 的吞吐量達 31.4 - 54 mbps, 向下相容 802.11b 裝置的網路，然而 802.11b 網路拖慢了 802.11g 的網路。

2009 802.11n 的吞吐量達 600 mbps, 傳輸距離也增加。

2013 ~ 2016 802.11ac (WiFi5) 分別有 802.11ac WAVE1 與 802.12ac WAVE2，
是 802.11n 的延伸版，增加 RF 頻寬與 Spatial Stream 空間串流。

2019 802.11ax 定義了 WiFi6, 支援 1GHz ~ 6GHz 的所有頻段，也能向下相容 a/b/g/n/ac, 密集用戶環境下吞吐量提升四倍，因此速率提供，延遲下降。 。

