## GitHub Projects

<table>
{% for repository in site.github.public_repositories %}
 {% if repository.name != site.github.project_title %}
  <tr>
   <td>[{{ repository.name }}]({{ repository.html_url }})</td>
  </tr>
  <tr>
   <td>{{ repository.description }}</td>
  </tr>
 {% endif %}
{% endfor %}
</table>

## Other Projects

<table>
 <tr>
   <td>Mafia</td>
   <td>Poker Helper</td>
  </tr>
  <tr>
   <td><img src="/projects/mafia.png" height="15%"></td>
   <td><img src="/projects/pokerhelper.png" height="15%"></td>
  </tr>
  <tr>
   <td>Online Android game</td>
   <td>Poker guide for novice (My first project on Android). Available on <a href="https://play.google.com/store/apps/details?id=ru.daringmandarin.pokerhelper">Google Play</a>(only in russian)</td>
  </tr>
</table>
