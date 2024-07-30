| Skill       | Level       |
| ----------- | ----------- |
{% for tool in site.data.skills.programming_tools %}
| {{ tool.title }} | {{ tool.level }} |
{% endfor %}