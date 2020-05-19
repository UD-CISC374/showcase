# CISC374 Spring 2020 Educational Games

{% for project in site.data.s20games %}

## {{ project.Name }}

<a href="{{ project.Link }}" target=_blank>
    <img src="screenshots/{{ project.Key }}_small.png">
</a>

{{ project.Key }}

<p>Coded by {{ project.Coders }}.</p>

<p>{{ project.Pitch }}</p>

<p>
<strong><a href="{{ project.Link }}">Play</a></strong>, 
<a href="{{ project.EGDD }}">[EGDD]</a>, 
<a href="{{ project.Youtube }}">[Youtube]</a>
</p>

{% endfor %}