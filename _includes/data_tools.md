| Skill | Level |
| ---- | ---- |
{% assign skills = site.data.skills.data_tools | sort: "title" -%}
{% for skill in skills -%}
| {{ skill.title }} | {{ skill.level }} |
{% endfor %}