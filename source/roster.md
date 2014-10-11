---
layout: default
generator: pagination
pagination:
    provider: page.players
use: [players]
---

{% for player in page.pagination.items %}
        An item
    {{ player.name }}
{% endfor %}