# Public Enemies by Open Social Network
Publicly available list of entities considered as public enemies.

This list is maintained by the Open Social Network Initative.

## Public enemies

{% for public_enemy in site.data.public_enemies %}
  
#### {{public_enemy.name}}

{% if public_enemy.email %}
E-Mail: <{{public_enemy.email}}>
{% endif %}

{% if public_enemy.website %}
Website: [{{public_enemy.website}}]({{public_enemy.website}})
{% endif %}

{% endfor %}

## Support or Contact

You can contact us via [Github](https://github.com/) by opening an issue or making a pull request.
