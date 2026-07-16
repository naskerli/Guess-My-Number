# Şəkil qovluğu / Image slots

Bu qovluqdakı şəkillər `index.html`-də avtomatik yüklənir. Səhifədə həmçinin
istənilən çərçivəyə **klikləyib** və ya şəkli **sürükləyib** yeni şəkil əlavə etmək olar
(brauzerdə localStorage-da saxlanılır).

## Timeline (Hero) — sıra `v1 → v4` fayl adları ilə müəyyən olunur
| Fayl | Model | Şəklin məzmunu |
|---|---|---|
| `v1-classic.png` | V1 — Şəffaf Çox-Səviyyəli Lotok | şəffaf çox-tərəfli tray, iri qırmızı POZ QAZAN başlıq |
| `v2-cascade.png` | V2 — Şəffaf Kilidli Qutu | şəffaf 2×3 qutu, açarlı kilid, azərlotereya |
| `v3-hybrid.png`  | V3 — Sarı-Akril Hibrid | sarı çərçivə + akril panel, yuvarlaq başlıq |
| `v4-modular.png` | V4 — Klassik Sarı Korpus | tam sarı korpus, döşəmə tipli, yan tutacaq |

## Yekun Təkliflər (Section 2)
| Fayl | Model | Şəklin məzmunu |
|---|---|---|
| `3d-dispenser.png`        | 3D Dispenser        | sarı pilləli kaskad rəf (10x, PRESTIJ, XAMSA...) |
| `stackable-dispenser.png` | Stackable Dispenser | mavi/sarı üst-üstə yığılan modul drum bloklar |

## Qeydlər
- **Timeline sırası** fayl adlarındakı `v1..v4` nömrələri ilə gedir. Başqa sıra istəsəniz,
  `index.html`-də `<article class="tl-card">` bloklarını yerini dəyişin (mətnlər də orada).
- `Azerlotereya-Dispenser.html` — bütün şəkillər içinə **base64 kimi yerləşdirilmiş** tək fayldır;
  brauzerdə birbaşa açılır, `assets/` qovluğuna ehtiyac yoxdur.
- Analiz bölməsindəki rəqəmlər **nümunə/proqnoz**dur — real data ilə əvəzləyin.
