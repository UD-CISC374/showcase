# CISC374 Spring 2020 Educational Games

{% for project in site.data.s20games %}

## {{ project.Name }}

<img src="screenshots/{{ project.Filename }}_small.png">

<p>Coded by {{ project.Coders }}.</p>
    
<strong><a href="{{ project.Link }}">Play</a></strong>

<p>{{ project.Pitch }}</p>

<a href="{{ project.EGDD }}">[EGDD]</a>

<a href="{{ project.Youtube }}">[Youtube]</a>

{% endfor %}