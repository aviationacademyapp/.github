<picture>
  <source media="(prefers-color-scheme: dark)" srcset="svg/logo-horizontal-dark.svg">
  <img src="svg/logo-horizontal.svg" alt="Aviation Academy" width="420">
</picture>

# Marka kimliği

Bütün yazılar SVG içinde path'e çevrildi, açmak için font kurmaya gerek yok. Vektör kaynak `svg/` klasöründe, PNG kopyaları (logolar 2000 px genişlik, ikonlar 1024 px) `png/` klasöründe.

## Renkler

| | Ad | HEX | Kullanım |
| --- | --- | --- | --- |
| ![](https://placehold.co/16x16/051C3A/051C3A.png) | Lacivert | `#051C3A` | "Aviation", uçak, koyu zemin |
| ![](https://placehold.co/16x16/0A7AFF/0A7AFF.png) | Mavi | `#0A7AFF` | "Academy", vurgu, mavi ikon zemini |
| ![](https://placehold.co/16x16/FFFFFF/FFFFFF.png) | Beyaz | `#FFFFFF` | Koyu zeminde uçak ve "Aviation" |
| ![](https://placehold.co/16x16/E2E4E8/E2E4E8.png) | Ayırıcı gri | `#E2E4E8` | Split logodaki dikey çizgi |

```css
:root {
  --aa-navy: #051C3A;
  --aa-blue: #0A7AFF;
  --aa-white: #FFFFFF;
  --aa-divider: #E2E4E8;
}
```

## Yazı tipi

**Montserrat** ([Google Fonts](https://fonts.google.com/specimen/Montserrat), OFL lisanslı).
- **Logo yazısı:** Ağırlık 660 (SemiBold ile Bold arası), harf aralığı `-0.02em`. "AviationAcademy" bitişik yazılır: "Aviation" lacivert, "Academy" mavi.
- **Arayüz metinleri:** Montserrat 600 ya da 700.

## Dosyalar

| Dosya | Ne zaman |
| --- | --- |
| `logo-horizontal` | Ana logo, açık zemin |
| `logo-horizontal-dark` | Ana logo, koyu zemin |
| `logo-stacked` / `logo-stacked-dark` | Dar ve kare alanlar (açılış ekranı, kapak) |
| `logo-horizontal-plane-right` | Uçağın yazının sağında durduğu alternatif |
| `logo-split` | Uçak, ayırıcı ve iki satır yazı (antet, sunum) |
| `icon-app-navy` / `icon-app-blue` | Köşeleri yuvarlatılmış uygulama ikonu |
| `icon-app-navy-square` / `icon-app-blue-square` | Köşesiz ikon: App Store, Play Store, avatar (köşeyi platform yuvarlatır) |
| `icon-circle` | Yuvarlak rozet, sosyal medya profili |
| `mark` / `mark-white` | Yazısız uçak işareti |

## Kurallar

- Uçak her zaman sağ yukarıya bakar. Döndürme, aynalama, esnetme yapılmaz.
- Koyu zeminde `-dark` ve `-white` dosyaları kullanılır. Lacivert logo koyu zemine konmaz.
- Renkler yalnızca yukarıdaki paletten seçilir. Gradyan, gölge ya da kontur eklenmez.
- Logonun etrafında en az uçağın yüksekliği kadar boşluk bırakılır.
