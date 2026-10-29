# Query big data with Trino · Sunum

VBO Data Engineering Bootcamp bonus dersinin sunumu: federated query mantığı ve Trino.

**Sunumu aç:** https://cemalcici.github.io/trino-bonus-slides/

**Demo reposu:** [cemalcici/trino-federated-demo](https://github.com/cemalcici/trino-federated-demo). Sunumdaki sayılar bu demodaki ölçümlerden alındı.

## Kullanım

| Tuş | İşlev |
|---|---|
| → / Space | Sonraki adım veya slayt |
| ← / Backspace | Geri |
| P | Presenter mode (ayrı seyirci sekmesi açar) |

13. slayttaki "Beklenen sonuçlar" düğmesi, demonun beklenen çıktılarını gösteren yedek slaytlara götürür.

## Yerelde çalıştırma

```bash
npm run dev      # npx hyperframes present ./composition → http://localhost:3004
```

Ya da herhangi bir statik sunucuyla: `python3 -m http.server` ve http://localhost:8000.

## Yapı

- `composition/index.html`: deck (14 slayt + 3 yedek slayt).
- `composition/assets/`: yerel fontlar (Barlow Condensed, Public Sans, JetBrains Mono; OFL) ve görseller.
- `index.html`, `player.js`, `slideshow.js`: [HyperFrames](https://github.com/heygen-com/hyperframes) 0.8.178 slideshow çalışma zamanı; GitHub Pages bu dosyalarla sunar.

Veri: Olist, *Brazilian E-Commerce Public Dataset by Olist*, Kaggle, CC BY-NC-SA 4.0. Senaryodaki şirketler kurgusaldır.
