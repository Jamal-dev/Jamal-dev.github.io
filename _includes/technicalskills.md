#### Programming Skills

| Skill | Level |
| ---- | ---- |
{%assign skills=site.data.skills.programming | sort : "title" -%}
{%for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}


#### Numerics Skills

| Skill | Level |
| ---- | ---- |
{%assign skills=site.data.skills.numerics | sort : "title" -%}
{%for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}


#### Aerospace Skills

| Skill | Level |
| ---- | ---- |
{%assign skills=site.data.skills.aerospace | sort : "title" -%}
{%for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor -%}
{%assign skills=site.data.skills.robotics | sort : "title" -%}
{%for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}

#### CAD Skills

| Skill | Level |
| ---- | ---- |
{%assign skills=site.data.skills.cad | sort : "title" -%}
{%for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}
