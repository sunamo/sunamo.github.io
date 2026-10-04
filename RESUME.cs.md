---
schema_version: 11
type: other
category_override: none
file_count: 3
file_extensions: md:2, noext:2, html:1
file_extensions_updated: 2026-10-04
avg_lines_per_file: 19
total_lines: 10
metrics_lm: 2026-10-01 16:40:53
move_to_legacy_percent: 60
description_updated: 2026-10-01
links_updated: 2026-10-01
github_source_url: not found
origin_status: found
origin_checked: 2026-10-01
article_source_url: not run
article_status: pending
article_checked: not run
last_build_ok: not run
last_build_date: not run
last_tests_run_date: not run
covered_lines: 0
---

## Description

Repo pro GitHub Pages uživatele sunamo. Jediný obsah je index.html, který pomocí meta refresh přesměruje na http://sunamo.cz. Hlavním účelem je tak rezervovat doménu sunamo.github.io a přesměrovat návštěvníky.

## Původ zdrojáků

Staženo z GitHubu: **ne** — vlastní GitHub Pages repo s pár řádky HTML redirectu.

- Ověřeno: index.html přečten celý (meta refresh na sunamo.cz); remote je vlastní git@github.com:sunamo/sunamo.github.io.git, nejde o fork; autor sunamo / radek.jancik@sunamo.cz.

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **60 %** — repo jen rezervuje doménu GitHub Pages a přesměrovává na sunamo.cz.
- Jediný obsah je index.html s meta refresh na http://sunamo.cz.
- Funkční účel (přesměrování) existuje, proto nižší hodnota než u prázdných repo; je to výjimka z pravidla o GitHubu, o smazání rozhoduje uživatel.

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: žádné
