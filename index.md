{% if user %}
  Hello {{ user.name }}!
{% endif %}



{% assign my_array = "zebra, octopus, giraffe, Sally Snake" | split: ", " %}

{{ my_array | sort | join: ", " }}
