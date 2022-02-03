---
lang: hu
---
Adatvizualizáció demonstráció
================

Ez a dokumentum az adatvizualizáció néhány gondolatát kívánja
szemléltetni egy konkrét példán. Nem bevezetést szeretne adni, hanem
sokkal inkább motivációt, hogy az adatvizualizáció

  - miért fontos,
  - hogyan lehet elemi építőkövekből akár egészen bonyolult
    vizualizációkat is összerakni,
  - végezetül, hogy mindez milyen hatékonyan megvalósítható az `R` (és
    megfelelő csomagok: `data.table` és `lattice`) használatával.

A konkrét esettanulmányunk a [Nemzeti
Rákregiszter](http://www.onkol.hu/hu/nemzeti_rakregiszter) (NRR)
adatainak vizualizálása lesz. Az NRR hazánk egyik legnagyobb hagyományú
betegségregisztere, melye a rákos esetek számát gyűjti átfogóan, több
mint egy évtizedre visszamenően Magyarországon. Ami a mostani
szempontunkból még fontosabb, az adatok nyilvánosan elérhetőek, sőt, le
is bonthatóak ráktípus (diagnózis), diagnózis éve, beteg életkora, neme
és lakhelye (megye szinten) szerint. Ezért a többdimenziós
adatvizualizálásra is kitűnő példa, ráadásul könnyen megfogalmazhatóak
olyan kérdések, melyek – tényleg – fontosak a gyakorlatban, és melyeknél
az adatvizualizáció nagyon fontos segítséget jelent.
