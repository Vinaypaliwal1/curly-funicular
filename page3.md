List of passangers in ship is given below with their age:

{% for item in site.data.titanic %}
- {{ item.Name }}, {{ item.Age }}
{% endfor %}