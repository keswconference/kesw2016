---
title: Organization committee
layout: page
---

### Main organizers

**General Chair:** Petr Křemen, [FEE CTU in Prague](https://www.fel.cvut.cz/en/), Czech Republic

**Program Chair:** Axel-C. Ngonga Ngomo, [University of Leipzig](http://aksw.org/AxelNgonga.html), Germany

**Open Science and Education Chair:** *Will be announced.*

**Publicity Chair:**  
[Maxim Kolchin](http://kolchinmax.ru), [ITMO University](http://en.ifmo.ru), Russia  
Martin Ledvinka, [FEE CTU in Prague](https://www.fel.cvut.cz/en/), Czech Republic

### Program committee


<table id="pc">
{% for member in site.data.pc %}
    <tr>
        <td class="name" width="30%">
            {%if member.page %}
                <a href="{{ member.page }}">{{ member.name }}</a>
            {% else %}
                {{ member.name }}
            {% endif%}
        </td>
        <td class="affiliation" width="70%">{{ member.affiliation }}</td>
    </tr>
{% endfor %}
</table>

<!--h3. Additional reviewers-->
