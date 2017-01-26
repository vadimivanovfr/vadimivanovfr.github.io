## GitHub Projects

{% for repository in site.github.public_repositories %}
 {% if repository.name != site.github.project_title %}
  [{{ repository.name }}]({{ repository.html_url }})|
  --------------------------------------------------|
  {{ repository.description }}|
  ----------------------------|
 {% endif %}
{% endfor %}
