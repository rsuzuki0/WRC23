# Agenda Item 1.2 傾向と対策
アマチュア無線では3.3GHzと10GHzが影響を受ける。3.3GHzはJAでは影響がないので、10GHzに絞る。

## AI 1.2 原文
> 1.2 to consider identification of the frequency bands 3 300-3 400 MHz, 3 600-3 800 MHz, 6 425- 7 025 MHz, 7 025-7 125 MHz and 10.0-10.5 GHz for International Mobile Telecommunications (IMT), including possible additional allocations to the mobile service on a primary basis, in accordance with Resolution 245 (WRC-19);

## AI 1.2 総務省
> 議題 1.2 3 300-3 400 MHz、3 600-3 800 MHz、6 425-7 025 MHz、7 025-7 125 MHz 及び 10.0-10.5 GHz 帯の IMT への特定の検討
> <議題の概要>
> 本議題は、3 300-3 400 MHz(第一地域の脚注改訂及び第二地域)、3 600-3 800 MHz(第二地域)、6 425-7 025 MHz(第一地域)、7 025-7 125 MHz(全地域)及び 10.0-10.5 GHz 帯 (第二地域)の IMT への特定を検討するものである。

## AI 1.2 我が国の考え方 (抜粋)
> 10.0-10.5 GHz 帯(第二地域) 日本は、ITU-R における対象帯域での既存業務との共用・両立性検討の実施を支持する。

## IARU暫定見解 (分割、強調はこのメモで付加。文はそのまま)
> The IARU opposes
> * the identification of the band 10.0-10.5 GHz for IMT in Region 2 as well as
> * the introduction of a mobile service allocation in the region, which would be a necessary precursor to its identification for IMT.
>
> **Spectrum sharing with a mass market deployment of mobile systems** can be challenging and experiences have shown that **the legal implications of national IMT licensing processes and service provider requirements tend to result in removal of national amateur service assignments** which can severely affect the development of amateur radio.
>
> Considering j) of Resolution 245 (WRC-19) notes that **harmonized worldwide arrangements for IMT are “highly desirable;”** it logically follows that an undesirable regional identification for IMT must be weighed against the continuing requirements of incumbent services. While studies are only invited with regard to the protection of primary services, **considering k) and l) and recognizing c) of the resolution make no distinction between primary and secondary allocations with regard to the need to protect existing services.** The use and evolving needs of the **amateur and amateur-satellite services must not be overlooked** as an undesirable regional arrangement for IMT is being considered. The IARU requests that **the special status of 10.45- 10.5 GHz as a worldwide amateur-satellite allocation with no mobile allocation** be respected.

### 分析
IARUは、議題の抜粋部分そのものに反対。

最後の段落は、まずは[WRC-19のReolution 245](https://www.itu.int/dms_pub/itu-r/oth/0c/0a/R0C0A00000D0002PDFE.pdf)を参照しないと理解できない。

> considering
> j) that harmonized worldwide frequency bands and harmonized frequency arrangements for IMT are highly desirable in order to achieve global roaming and the benefits of economies of scale;

IMT割当は世界共通で調和がとれることが非常に望ましい、と書いてある。この議題で10GHzはR2に限っているので、IARU見解ではそんな検討をしても、たいして望ましくない結果しか出ない。その大して望ましくないIMTに周波数を特定するならば、現役の業務継続の必要性をちゃんと考慮してもらわないと困る、と。また、書いてはいないが、R2で穴を開けられたら、次は世界的に広めてこられるのは明らかではないか。

仮にこの議題が通って、検討がはじまると、保護の必要性があるのは、一次割当ユーザーのみであるが、Resolution 235によれば、

> considering
>
> k) that identification of frequency bands as in considering e) for IMT may change the sharing situation regarding applications of all services to which the frequency band is already allocated, and may require additional regulatory actions;
>
> l) the need to protect existing services and to allow for their continued development when considering frequency bands for possible additional allocations to any service,
>
> recognizing
>
> c) that any identification of frequency bands for IMT should take into account the use of the frequency bands by other services and the evolving needs of these services,

に関しては二次ユーザーも同列に扱われる。そこで、たいして望ましくない地域限定IMTに周波数を特定する検討をするならば、アマチュア業務とアマチュア衛星業務の必要性と、これからの発展の必要性を、ちゃんと考慮されるべきで、特に、10.45--10.5 GHzの世界的なアマチュア衛星業務の周波数は、移動通信と共用することのない、現在の割当を、尊重するよう要請する。

## その他の関連背景
* アマチュア衛星の多くは周回衛星であるので、地上割当が地域限定であっても、多大な影響を受ける。
* 10GHzは、アマチュア無線のマイクロ波バンドでも利用率が高い。電波伝播研究用のビーコンなども稼働している。
* JAでは10.0--10.25が地上用, 10.45--10.50が衛星やEMEと分かれているが、R2では10.0--10.50が割当られている。10.2--10.3GHzは、ガンダイオードを用いた送信機による通信に使われている。バンド中部は、全二重通信などに使われる。

## コメント例
議題1.2の10GHz帯のIMTへの特定の検討を支持しないよう要請する。WRC-19の決議235にあるように、IMTはあくまで世界共通で調和した割当を望んでいるが、本議題の第二地域限定ではそれは達成されない。また、いずれかの時点で、他地域も同様の検討対象となれば、日本で現存一次割当の放送事業者の通信(固定、移動)と、レーダー業務へ多大な影響を及ぼすことは自明である。当初は一次だったアマチュア業務も、後の譲歩で二次に降りたが、決議235のconsidering k), l)およびrecognizing c)では二次業務も含めて干渉など悪影響から保護されるべき対象に含まれる。アマチュア業務と、アマチュア衛星業務は、10GHz帯で世界的に運用されており、また今後の発展も期待される。特に、アマチュア衛星の大半は周回衛星であり、仮に議題1.2のとおり第二地域限定で特定されたとしても、衛星運用上世界的な悪影響を受ける。また、アマチュア業務の地上通信では、他の業務と比べて非常に弱い電波を受信する長距離通信や、伝搬研究などが盛んであり、これらの業務は世界的に10.0〜10.3GHzが用いられる。これらを綜合すると、議題は第二地域限定(日本は対象地域外)だが、賛成するには問題が多い。
