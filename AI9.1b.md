# Agenda Item 9.1 b 傾向と対策
23cm帯で、ガリレオ(欧州)やみちびきのような、無線航行衛星業務(RNSS)の信号の受信をアマチュア無線の電波から保護するのに追加措置は必要か?

## AI 9.1 b 原文
> **9.1** on the activities of the Radiocommunication Sector since WRC-19:
> - (略)
> – Review of the amateur service and the amateur-satellite service allocations in the frequency band 1 240-1 300 MHz to determine if additional measures are required to ensure protection of the radionavigation-satellite (space-to-Earth) service operating in the same band in accordance with Resolution 774 (WRC-19);

## AI 9.1 b 総務省

> 課題 9.1 b) 1 240-1 300 MHz帯におけるアマチュア業務及びアマチュア衛星業務の分配の見直し
>
> <課題の概要>
>
> 本議題は、1 240-1 300 MHz 帯に二次分配されているアマチュア業務(及びアマチュア衛星業務)について、分配を削除せずに、無線航行衛星業務(RNSS)(宇宙から地球)の局(受信機)を保護するための技術的及び運用上の検討を行うことである。欧州により提案された議題である。

## AI 9.1 b 我が国の考え方
> 日本は、ITU-Rにおける1 240-1 300 MHz帯に二次分配されているアマチュア業務及びアマチュア衛星業務から無線航行衛星業務(RNSS)(宇宙から地球)の局(受信機)を保護するための技術的及び運用上の検討を支持する。

## IARU暫定見解

> During many years of operational experience, the secondary amateur and amateur satellite services have successfully co-existed with all the primary services in the range 1 240-1 300 MHz with very few issues.
> In cases where certain applications (in particular wide bandwidth, high duty cycle applications) could increase the potential for interference, careful spectrum management and national licensing conditions have minimised any risk.
> Radio amateurs have successfully co-existed and innovated in this frequency range for many years and IARU believes that the regulatory status of the amateur and amateur satellite services in this range is already clear.
> Therefore any additional regulatory, operational or technical measures incorporated into the Radio Regulations are unnecessary.
> Any recommendations resulting from studies under Resolution 774 can be applied on a national basis and should be based on realistic assumptions, proportionate in scope and carefully justified so as not to unnecessarily inhibit development of the amateur services.

### 分析
検討のもっと具体的なことは、Resolution 774 (WRC-19)を参照。

去年の時点では、IARUは、干渉の報告は数少なく(国レベルで認知されているのはドイツの1件、イタリアの1件)、その例も誇張されていて、従来通りの共用に問題はなく、追加的な措置は「不要」ないし「時期尚早」であるという見解を取っていた。現在でも、そのような広範な干渉の恐れは誇張されていて、追加的な措置は慎重に調査、議論されるべきという見解は変わらない。ただし、2021〜2022年の間に、WP 4Cにて、アマチュアがガリレオ信号受信に与える干渉について、これまでより詳細な検討がなされた結果、IARUはアマチュア業務に追加制約が課される方向で議論が進むのはやむを得ないと考えるに至った。

(IARU暫定見解の英文解釈面で、難しいことはないように思われる。)

IARU G4SJHの2022年6月のスライド(Amateur / RNSS Coexistence in the 23cm band)のp.13最後に、
> At WRC, some countries may try to mandate the guidance in the Radio Regs by incorporation by reference or through an updated WRC Resolution.

とあるが、これは、WP5AのCPM textドラフトの最後の最後にある、
> ITU-R is developing a Recommendation ITU-R M.[AS.GUIDANCE] providing guidelines in order to avoid such cases of harmful interference to the RNSS receivers in the future. This Recommendation could include, inter alia, encouragement of the use of specific sub-bands with sufficient frequency offsets from the spectrum main lobes of RNSS signals to enhance the protection of RNSS receivers in the bands under consideration.
>
> These guidelines are intended to assist administrations and the amateur and amateur-satellite services to ensure the protection of the RNSS (space-to-earth) in the frequency band 1 240-1 300 MHz.

では拘束力が足らないというような発言が、どこかの国から出てきたということを、滲ませているように思う。(こういう会議では、議事録にも報告書にも出ない事項は漏らさない、特に発言者が特定できるような発言内容は漏らさない決まり)

## その他の関連背景
* CW, SSB, FMなどの狭帯域変調波と、ATVなどの広帯域変調波では、RNSS受信への干渉の度合いが違う。また、RNSS信号(非常に広帯域)の中心周波数とアマチュア波の周波数の差も影響する。このように、WP 4Cではやや詳細に検討さてきたし、必要な措置に関しても、同様に詳細に検討されるものと予想されるが、今回のパブコメで立ち入ってしまうと、先走りすぎる感が強い。
* WP 4Cでは、干渉からの保護に必要な措置の程度や内容などについては、RNSS信号の中心周波数との関係(近いほど干渉が強い)、アマチュアの電波形式の帯域(広いほど干渉が強い)、などの面を考慮した出力規制案が複数検討されているが、今回のパブコメでは、技術や運用面での制約内容を例示したり、その程度などを具体的に議論することは、まだできない。先走ったコメントを出さぬよう注意されたい。
* 現在議論されている規制案のひとつは、全バンドでEIRP 1Wという規制案であるが、これはアンテナゲインの差はあるものの、現在のJAの現状と大差ない。他の案では、一部の限られた條件で出力20〜100W許すものの、それ以外では出力を厳しく制限する。
* これまでの経緯から、適切な追加的措置は、国や地域によって大きく違ってくると推論するのは妥当である。例えば、日本では従来から移動局は出力1Wに制限されていた上に、レピーターの出力が減力され、また一次業務である放送事業用FPUとの調整でレピーター局の停波などの調整が行なわれた。これらの措置によって、周波数共用は問題なくできている。今回決議774が出てきた欧州では、もっと大出力の運用がされている。
* 1.2GHzはギガヘルツ域のアマチュアバンドでは最も運用しやすく、運用局数も多いとは言え、送信頻度や送信時間のデューティー比、運用局の密度などは十分に低く、トータルの干渉を一定に抑えるという観点から、これらの要素を妥当に織り込んだ検討をすれば、アマチュア業務ができなくなるようほどの制約にはならないのではないかと想像される。

## 参照文書
* WP 4Cであった議論は、ITU-R 4C/333報告文書を。
* [IARU continues engagement in the WRC-23 preparations](https://www.iaru-r1.org/2021/iaru-continues-engagement-in-the-wrc-23-preparations/)
* IARU による1200MHz関連のニュースと見解
  * [23cm band and Sat-Nav Coexistence: Studies maturing in ITU‑R WP4C](https://www.iaru.org/2022/23cm-band-and-sat-nav-coexistence-studies-maturing-in-itu-r-wp4c/)
    * https://www.iaru.org/wp-content/uploads/2022/05/IARU-Report-from-WP4C_May-2022.docx
    * https://storage.iaru-r1.org/index.php/s/BtpxWjL7La7syr7
  * [23cm Band and RNSS – Compromises need to be found](https://www.iaru.org/2022/23cm-band-and-rnss-compromises-need-to-be-found/)
* 日本で、アマチュア業務が測位衛星信号に与える影響を評価した [情報通信審議会 情報通信技術分科会 衛星通信システム委員会報告 資料 119-1-2](https://www.soumu.go.jp/main_content/000427597.pdf)

2022年6月のITU-R WP 5A会合では、CPM(Conference Preparatory Meeting、WRC-23本会議に向けた準備会合)テキストのドラフト作業や、RNSS保護に関する勧告のドラフトも進んできて、今後のうごきの方向性もだいぶ明確になってきた。
* https://www.iaru.org/wp-content/uploads/2022/06/Report-from-WP5A_June-2022-FINAL.pdf
* [Amateur / RNSS Coexistence in the 23cm band](https://www.iaru.org/wp-content/uploads/2022/06/23cm-Band-and-RNSS-June2022.pdf)

* [597. Report on the twenty-seventh meeting of Working Party 5A (Geneva, 23 May - 3 June 2022)](https://www.itu.int/md/R19-WP5A-C-0597/en)
これのAnnex 6にWRC-23 AI 9.1bのCPM textドラフトが収載。

## 基本的な対策軸
本件議題は、支持する、しないという次元の話ではとっくになくなっており、ITUの機関でもあり、アマチュア無線界を代表するIARUが常に最大限に検討や議論に関与し、シミュレーションや計算に使われる前提條件やパラメーターが実際のアマチュアの実情に即しているか、などを確認するよう、また必要以上の制約が課されぬように最大限の配慮を求めていく、というのが現段階では最も現実的で建設的な軸ではないかと考える。加えて、新たな制約はRadio Regulations(RR、無線通信規則)のレベルで規制するのではなく、勧告などで国毎の事情を勘案して実施する余地を残すように求める。

## コメント例
議題9.1 bの、WRC-19決議774に従ったRNSS受信局の保護措置を検討するにおいて、その基礎となるアマチュア業務の運用実態のデータが現実に即したものであることが決定的に重要である。そのため、関連する検討、議論において、ITU-Rのワーキングパーティー5Aや4Cはじめ、すべてにおいて、ITUの機関であり、アマチュア無線界の利益を代表するInternational Amateur Radio Union(IARU)の積極的な関与を保証し、干渉の程度の計算などが最大限に正確であることを確認させることを要請する。また、これまでの干渉の報告例は数少なく、アマチュア業務は一次業務と共存してきた。日本をはじめ、いくつかの国では既に減力、限定的な一時停波などの措置によって一次ユーザーの保護が実現した。追加措置が必要となる場合でも、その国や地域の実情に応じた対応によって、過剰制約とならないことが、措置の正当化や業務の共存の面で重要である。そのため、本件調査がいずれ結論づけるであろう追加措置は、Radio Regulations(無線通信規則)による一律な規制ではなく、勧告によって対処し、各国で具体化して実施するのが妥当と考える。

## 履歴
2022年6月22日のIARU Newsに出てきた報告書類を分析し、このページにも若干の追記をしたが、方向性はこれまでの議論と変わっておらず、結論はこれまでと変化なし。