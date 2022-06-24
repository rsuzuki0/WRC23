# Agenda Item 1.12 傾向と対策


## AI 1.12 原文
> 1.12 to conduct, and complete in time for WRC-23, studies for a possible new secondary allocation to the Earth exploration-satellite (active) service for spaceborne radar sounders within the range of frequencies around 45 MHz, taking into account the protection of incumbent services, including in adjacent bands, in accordance with Resolution 656 (Rev.WRC-19);

## AI 1.12 総務省
> 議題 1.12 45 MHz 帯衛星搭載レーダーサウンダーのための地球探査衛星業務(能動)への新規二次分配のための検討の実施
> <議題の概要>
> 45 MHz周辺の周波数の範囲においてスペースボーンレーダーサウンダー用途に地球探査衛星業務(EESS)(能動)への新規二次分配の可能性について、隣接帯域を含む既存業務の保護を考慮しつつ、検討するもの。

## AI 1.12 我が国の考え方
> 日本は、45 MHz付近の周波数領域における、衛星搭載レーダーサウンダーのための地球探査衛星業務(能動)への新規二次分配について、ITU-R の検討において、該当周波数 帯または隣接周波数帯の既存業務が保護され、それら業務に追加の制限を課さないことが明らかになった場合は、当該分配の検討を支持する。

## IARU暫定見解
> The IARU believes that the studies for a possible new secondary allocation to the Earth exploration-satellite (active) service for spaceborne radar sounders within the range of frequencies around 45 MHz should include the need to protect the incumbent amateur service in the adjacent 50-54 MHz band. The IARU will contribute to the studies to ensure adequate protection of the sensitive receivers used by stations in the amateur service in the 50-54 MHz band, especially the frequencies 50-50.5 MHz where the majority of amateur communication via the ionosphere is conducted, often with very low signal levels.

### 分析
IARUは、反対しないものの、慎重な検討を要請。

Rec. ITU-R RS.2042-1には、
> The spaceborne sounding radar will operate at a centre frequency of 45 MHz covering a 10 MHz bandwidth.

とある(3章冒頭)。表1にも、帯域10MHz、出力20dBW、クロス八木の円偏波とある。変調は85μsパルスで1200Hz、線形FMチャープである。受信機のIF帯域は12MHzとあるから、10MHzの「送信帯域」からはみ出す信号電力も十分に活用したいということではないか。つまり、このレーダーサウンダーの広帯域信号は、スペクトルの広がりが大きく、50MHz帯でもモロに被りを受けることになりそうだ。


また、3.4節には、運用地域に関し、
> The sounding radar is to be operated exclusively in un-inhabited or sparsely populated areas of the ice sheets of Greenland and Antarctica and the deserts of northern Africa and the Arabian Peninsula and will operate for a period not to exceed 10 minutes in duration per 92.7 minute orbit.

とあり、運用地域はグリーンランド、北アフリカ、アラビア半島、南極大陸に限定され、間欠運用になるとされる。

限られた情報から、アマチュア業務への影響を推測するのは難しい。

## 参照文書
* [Resolution 656 (Rev.WRC-19)](https://www.itu.int/dms_pub/itu-r/oth/0C/0A/R0C0A00000F00137PDFE.pdf)
* Recommendation ITU-R RS.2042-1 (12/2018) [Typical technical and operating characteristics for spaceborne radar sounder systems using the 40-50 MHz band](https://www.itu.int/dms_pubrec/itu-r/rec/rs/R-REC-RS.2042-1-201812-I!!PDF-E.pdf)

## コメント例