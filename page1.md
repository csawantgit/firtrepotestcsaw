This is page 1 test.

_The titanic.csv file contains data for 887 of the real Titanic passengers. Each row represents one person. The columns describe different attributes about the person including whether they survived (S), their age (A), their passenger-class (C), their sex (G) and the fare they paid (X)._

{% for item in site.data.titanic %}
- {{ item.survived }}, {{ item.Pclass }},  {{ item.Name }}, {{ item.Sex }}, {{ item.Age }}, {{ item.Siblings/Spouses+Aboard }}, {{ item.Parents/Children+Aboard }}, {{ item.Fare }}
{% endfor %}

{% include footer.txt %}