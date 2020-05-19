<h1>CISC374 Spring 2020 Educational Games</h1>

{% for project in site.data.s20games %}

<h2>{{ project.Name }}</h2>

<p>
<a href="{{ project.Link }}" target=_blank>
    <img src="screenshots/{{ project.Key }}_small.png">
</a>
</p>

<p>Coded by {{ project.Coders }}.<br>
{{ project.Pitch }}</p>

<p>
<table>
    <tr>
        <td><strong><a href="{{ project.Link }}">Play</a></strong></td>
        <td><a href="{{ project.EGDD }}">[EGDD]</a></td>
        <td><a href="{{ project.Youtube }}">[Youtube]</a></td>
    </tr>
</table>

</p>

{% endfor %}