# Web cvicenia (GitHub Pages)

Stranka bezi na `https://samek571.github.io/dm/`. Po kazdom commite sa za cca 1–2 minuty prebuduje sama (stav vidno v zalozke **Actions**).

## Co kde upravit
| Subor | Co obsahuje |
|---|---|
| `_data/course.yml` | nazov, cas, miestnost, email, odkazy na prednasku a sovu |
| `_data/schedule.yml` | rozvrh – temy, stitky, subory, zrusene cvicenia |
| `_data/grading.yml` | body a hranica zapoctu (graf sa prekresli sam) |
| `_data/links.yml` | uzitocne odkazy |
| `index.md` | volny text: pravidla uloh, AI, konzultacie |
| `_posts/` | novinky (jeden subor = jedna novinka) |
| `materials/` | PDF – v YAML staci napisat len nazov suboru |

## Tyzdenna rutina
1. Nahrajte PDF do `materials/` (napr. `cv3.pdf`, bez medzier a diakritiky).
2. Odkaz sa prida **sam**: PDF v `materials/cvN/` (N = poradie cvicenia, odpadnute sa nepocitaju) sa zobrazi pri N-tom cviceni, `cvN.pdf` ako "zadanie", ostatne pod nazvom suboru. Rucne (napr. externy odkaz) mozete v `_data/schedule.yml` k danemu datumu pridat:
   ```yaml
     files:
       - { name: "zadanie", url: "cv3.pdf" }
   ```
   Odsadzujte iba medzerami, nikdy tabulatorom.
3. Novinka: v `_posts/` **Add file → Create new file**, nazov `RRRR-MM-DD-nieco.md` s **dnesnym** datumom (novinky s buducim datumom sa nezobrazia):
   ```markdown
   ---
   title: "Pisomka sa presuva"
   ---
   Text novinky. Matematika: $$x^2 + y^2$$.
   ```

Najblizsie cvicenie sa na webe zvyrazni samo.
