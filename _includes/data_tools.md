| Skill | Level |
| ----- | ----- |
{% for tool in site.data.skills.data_tools -%}
| {{ tool.title }} | {{ tool.level }} |
{% endfor %}