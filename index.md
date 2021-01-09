# Hallo!

Danke, dass du dich dafür entschieden hast, unser wunderschönes Radolfzell zu kennen zu lernen.  
Einige Hinweise vorab:
- Die Stadtführung dauert zwischen 1,5 und 2,5 Stunden.
- Du musst über keine Zäune klettern. Falls doch, bist du auf dem falschen Weg.
- Du kannst diese Stadtführung so oft du willst mit beliebig vielen Leuten machen.
- Bitte halte Abstand und trage eine Maske dort, wo es gefordert wird.
- Diese Seite ist schlicht, damit du dich nicht von der Schönheit unserer Stadt ablenken lässt.
Viel Spaß, Robert Nickel

{% for post in site.posts %}
    <h1>{{ post.title }}</h1>
    {% for answer in post.answers %}
    <h2>{{ answer }}</h2>
    {% endfor %}
{% endfor %}