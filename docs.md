---
layout: default
title: Документация
---

## Документация
{:.no_toc}

* TOC
{:toc}
  
### Итоги общих собраний пользователей:

{% for result in site.data.meeting_results %}

* [{{ result.title}}](/assets/docs/meeting/results/{{ result.date }}.{{ result.format }})

{% endfor %}

### Протоколы собраний правления ТСН:

{% for protocol in site.data.protocols %}

* [{{ protocol.title}}](/assets/docs/board/protocols/{{ protocol.date }}.{{ protocol.format }})

{% endfor %}
