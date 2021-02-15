# LinkedIn Scammers by Open Social Network
Publicly available list of fraudulent entities on [LinkedIn](https://linkedin.com/).

This list is maintained by the Open Social Network Initative.

## Scammers

{% for scammer in site.data.scammers %}
#### {{scammer.name}}

E-Mail: <{{scammer.email}}>

Website: [{{scammer.website}}]({{scammer.website}})

{% endfor %}

## Support or Contact

You can contact us via [Github](https://github.com/) by opening an issue or making a pull request.