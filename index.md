## GitHub Projects

<table>
{% for repository in site.github.public_repositories %}
 {% if repository.name != site.github.project_title %}
  <tr>
   <td><a href="{{ repository.html_url }}">{{ repository.name }}</a></td>
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
   <td align="center"><b>Mafia</b></td>
   <td align="center"><b>Poker Helper</b></td>
  </tr>
  <tr>
   <td align="center"><img src="/projects/mafia.png" width="35%"></td>
   <td align="center"><img src="/projects/pokerhelper.png" width="35%"></td>
  </tr>
  <tr>
   <td>Online game for Android™</td>
   <td>Poker guide for novice (My first project on Android). Available on <a href="https://play.google.com/store/apps/details?id=ru.daringmandarin.pokerhelper">Google Play</a> (only in russian)</td>
  </tr>
  <tr>
   <td><b>Java, PHP, MySQL, Google Play Game Services, Google Sign-In, Andoid Studio</b></td>
   <td><b>Java, AdMob</b></td>
  </tr>
</table>
