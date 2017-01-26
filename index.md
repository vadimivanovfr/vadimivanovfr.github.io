## GitHub Projects

{% for repository in site.github.public_repositories %}
 {% if repository.name != site.github.project_title %}
  [{{ repository.name }}]({{ repository.html_url }})|
  --------------------------------------------------|
  {{ repository.description }}|
  ----------------------------|
 {% endif %}
{% endfor %}

## Other Projects

Mafia | Poker Helper |
------|--------------|
Online Android game | Poker guide for novice (My first project on Android). |
                    | Available on [Google Play](https://play.google.com/store/apps/details?id=ru.daringmandarin.pokerhelper) (only in russian)
--------------------|------------------------------------------------------|
