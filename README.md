# お名前.com デスクトップクラウド不正アクセス事案 公開情報OSINT調査

2026年10月に公表された、GMOインターネットの「お名前.com デスクトップクラウド」への不正アクセス・恐喝事案について、**公開情報のみ**を用いた受動的なOSINT（オープンソース・インテリジェンス）調査の結果を毎日記録するリポジトリです。

> **これは公開情報に基づく調査であり、公式の捜査を補完するものです。個人による違法行為は推奨しません。**

## 目的
- 公式発表・報道・公開記録から、事案の経緯を正確に整理すること
- 「確認済みの事実」「攻撃者の主張」「第三者の分析」「推測」を区別して記録すること
- 捜査機関・GMOによる検証に役立ちうる論点を、根拠と確度つきで整理すること

犯人の特定や断定を目的とするものではありません。技術的な相関は、個人の特定を意味しません。

## 調査方針とルール
- **合法・受動的な調査のみ**：公開されている公式発表、報道、公開登録記録（RDAP等）、証明書透明性ログ、既存の公開スキャン記録のみを参照します。
- **攻撃者サイト・リークサイトにはアクセスしません**（ミラー、アーカイブ上のコピーを含む）。GMOは、攻撃者サイトの閲覧者情報が攻撃者に取得されている可能性を警告しています。
- **スキャン・プローブ・侵入の試みは一切行いません。**
- **攻撃者への接触は一切行いません。**
- **盗まれたデータ（被害者情報・漏えいファイル）を取得・保存・再配布しません。**
- **個人名を挙げません**（公的立場にある人物の公的な発言を除く）。無関係な第三者を巻き込まないため、攻撃者側とされるドメイン名、メールアドレス、IPアドレス、同一サーバー上の無関係なサイトも掲載しません。インフラは「攻撃者側とされる3ドメイン」のように一般化して記載します。
- 確度ラベル：**CONFIRMED / HIGH / MODERATE / LOW / UNVERIFIED**

## 情報提供について
犯人や事案に関する情報をお持ちの方は、**GMOの公式窓口にのみ**提供してください。このリポジトリのIssue等には投稿しないでください。

- 公式発表：https://group.gmo/
- 懸賞金（サイバー犯罪懸賞金）公式窓口：https://cybercrimebounty.gmo/

## リポジトリ構成
```
README.md            このファイル
timeline.md          事案の時系列（随時更新）
sources.md           参照した情報源
reports/YYYY-MM-DD.md  日次レポート
```

---

## English summary
This repository records a daily, **legal, passive, public-information-only** OSINT review of the October 2026 intrusion and extortion incident affecting GMO Internet's Onamae.com Desktop Cloud service in Japan.

**Rules:** no access to attacker, mirror or leak sites; no scanning or probing; no contact with the attacker; no stolen data; no naming of private individuals. Attacker infrastructure is described generically and is not listed here, to avoid spreading it or implicating unrelated parties.

**Disclaimer:** This is research based on public information and is meant to complement the official investigation. Illegal actions by individuals are not encouraged.

**Tips** should go only to GMO's official channel: https://cybercrimebounty.gmo/ (official notices: https://group.gmo/). Please do not post tips in this repository.
