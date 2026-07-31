# CCF5 幾何の作品集 — MQRI ART へ移転しました（2026-07-31）

**このリポジトリは誘導専用になりました。作品の実体は MQRI ART にあります。**

🌐 **https://art.mqri.or.jp/**

## なぜ残してあるか

`https://keisuke19831213-source.github.io/ccf5-gallery/` は **REGEN DAY 2026-07-13 で配布したQRコード（`QR_ギャラリー.png`）の飛び先**です。印刷物に載っているURLなので、**このリポジトリを消したり Pages を止めたりしてはいけません**。

GitHub Pages は 301 を返せない（`.nojekyll` があるので jekyll-redirect-from も使えない）ため、各ページを **meta refresh + `<link rel="canonical">` + 目に見えるリンク** の3枚重ねにしています。canonical があるので検索エンジンには新URLが正として伝わり、同じ作品が2箇所から見える状態は解消されます。

## 移転先の対応

| 旧URL | 新URL |
|---|---|
| `/ccf5-gallery/` | https://art.mqri.or.jp/ |
| `/ccf5-gallery/kiosk.html` | https://art.mqri.or.jp/exhibit/ |
| `/ccf5-gallery/art01/` | https://art.mqri.or.jp/works/cymatic-resonance/ |
| `/ccf5-gallery/art02/` | https://art.mqri.or.jp/works/morphogenesis/ |
| `/ccf5-gallery/art03/` | https://art.mqri.or.jp/works/infinite-geometry/ |
| `/ccf5-gallery/art04/` | https://art.mqri.or.jp/works/hopf-loom/ |
| `/ccf5-gallery/art05/` | https://art.mqri.or.jp/works/quantum-mandala/ |
| `/ccf5-gallery/art06/` | https://art.mqri.or.jp/works/genesis-of-form/ |

作品の実体（移転前の各 `art0N/index.html`）は、このリポジトリの **git履歴**と、移設先の [mqri-art](https://github.com/keisuke19831213-source/mqri-art) の両方に残っています。

## 展示モードについて

`kiosk.html` は https://art.mqri.or.jp/exhibit/ に移り、上映順（無から満ちるへの弧）と操作系（`→` `←` `Space` `F` `L` `C`）はそのまま引き継いでいます。運用は移設先の `EXHIBITION.md` を参照してください。
