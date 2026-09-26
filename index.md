---
layout: default
---

{% assign c = site.data.course %}

{% include news.html %}

{% include schedule.html %}

{% include grading.html %}

<section class="block rules" markdown="1">

### Domácí úkoly

Zadání i odevzdávání probíhá v [{{ c.submissions.name }}]({{ c.submissions.url }}). Úkol lze odevzdat vždy do začátku dalšího cvičení. Když ho odevzdáte dost brzy a nebude za plný počet, můžete ho opravit a odevzdat znovu.

Úkoly můžete konzultovat s ostatními, ale řešení sepisuje každý sám. Kromě výsledku musí být vidět i postup; částečné řešení je lepší než žádné.

### Opravné písemky

Máte právo na opravu dvou písemek. Napíšeme je na posledních dvou cvičeních (viz [rozvrh](#rozvrh)).

### Umělá inteligence

- AI můžete používat k **vysvětlení pojmů** nebo jako **nápovědu**, když se zaseknete.
- **Ne** k vygenerování celého řešení – opravovat ho je ztráta času pro vás i pro mě.
- Pamatujte, že AI se plete, a to často sebevědomě.

</section>

<section id="konzultace" class="block" markdown="1">

## Konzultace

Pokud něčemu nerozumíte, nestíháte úkol nebo máte nápad, co zlepšit, napište mi na <code>{{ c.email }}</code> **dřív, než bude pozdě** – něco vymyslíme.

</section>

{% include links.html %}
