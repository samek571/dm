# Web cvičení (GitHub Pages)

## Zprovoznění (~5 min, bez gitu)
1. Na GitHubu vytvořte **veřejný** repozitář `course` (jiný název → změňte `baseurl` v `_config.yml`).
2. **Add file → Upload files** → přetáhněte všechno z této složky → Commit.
3. **Settings → Pages** → *Deploy from a branch* → `main` / `(root)` → Save.
4. Za ~1 min běží na `https://<uživatel>.github.io/course/`.

## Co kde upravit
| Soubor | Co obsahuje |
|---|---|
| `_data/course.yml` | název, čas, místnost, email, odkazy na přednášku a Moodle |
| `_data/schedule.yml` | rozvrh – témata, štítky, soubory, odpadlá cvičení |
| `_data/grading.yml` | body a hranice zápočtu (graf se překreslí sám) |
| `_data/links.yml` | užitečné odkazy |
| `index.md` | volný text: pravidla úkolů, AI, konzultace |
| `materials/` | PDF – v YAML stačí napsat jen název souboru |

## Týdenní rutina
1. Nahrajte PDF do `materials/` (např. `cv3.pdf`).
2. V `_data/schedule.yml` k danému datu přidejte `files: [{ name: "zadání", url: "cv3.pdf" }]`.
3. Novinka: v `_posts/` **Add file → Create new file**, název `2026-10-12-neco.md`:

```markdown
---
title: "Písemka se posouvá"
---
Text novinky. Matematika: $$x^2 + y^2$$.
```

Nejbližší cvičení se na webu zvýrazní samo.
