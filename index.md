---
my_variable: footer.html
---

{% if page.my_variable %}
  {% exclude {{ page.my_variable }} %}
{% endif %}

![area chart of vax data from DHSS](img/de_vax_data_issues.png)
