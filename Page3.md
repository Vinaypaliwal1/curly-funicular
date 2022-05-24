List of passangers is given below:

{% for item in site.data.titanic %}
- {{ item.Name }}, {{ item.Age }}
{% endfor %}