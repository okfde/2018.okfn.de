---
layout: page
chapter: 5.1
title: Organisationsprofil
permalink: /organisation/profil/
visual:
    img: /assets/images/einleitung/logo.png
    alt: Logo der OKF

---


## Anzahl in Köpfen (Jahresmittel)

<table width="500">
  <tr>
    <th>Jahr</th>
    <th>Mitarbeiter*innen</th>
    <th>davon hauptamtlich</th>
  </tr>
  <tr>
    <td>2011</td>
    <td>0</td>
    <td>0</td>
  </tr>
  <tr>
    <td>2012</td>
    <td>5</td>
    <td>5</td>
  </tr>
  <tr>
    <td>2013</td>
    <td>8</td>
    <td>8</td>
  </tr>
  <tr>
    <td>2014</td>
    <td>10</td>
    <td>10</td>
  </tr>
  <tr>
    <td>2015</td>
    <td>22</td>
    <td>22</td>
  </tr>
  <tr>
    <td>2016</td>
    <td>24</td>
    <td>24</td>
  </tr>
  <tr>
    <td>2017</td>
    <td>39</td>
    <td>39</td>
  </tr>
  <tr>
    <td>2018</td>
    <td>36</td>
    <td>36</td>
  </tr>
</table>

<br>


## Governance der Organisation


### Leitungs- und ggf. Geschäftsführungsorgan
gemäß der Vereinssatzung in der Beschlussfassung vom 23.08.2012


§ 9 Der Vorstand

§ 9.1 Der Vorstand setzt sich aus dem Vorsitzenden und dem stellvertretenden Vorsitzenden, dem Kassenwart zusammen sowie bis zu sechs weiteren Beisitzer*innen. Die Amtszeit beträgt zwei Jahre. Die Wiederwahl ist zulässig. Die jeweils amtierenden Vorstandsmitglieder bleiben nach Ablauf ihrer Amtszeit im Amt, bis Nachfolger gewählt sind. Der Vorstand arbeitet ehrenamtlich.
<br><br>
§ 9.2 Der Vorstand wird von der Mitgliederversammlung gewählt.

<div class="team">
  {% for person in site.data.board %}
  <div>
    <p class="team-entry">
      <strong class="team-entry__name">{{ person.name }}</strong>
      {% if person.img  %}
      {% assign img_path =  person.img %}
      {% else  %}
      {% assign img_path = person.name | downcase | split: ' ' | join: '' %}
      {% endif %}</p>
    <p>
      <img class="team-entry__img"
           src="/assets/images/team/{{ img_path }}.jpg"
           alt="Bild von {{ person.name }}">
      <em>{{ person.position }}</em><br>
      {{ person.text }}</p>
  </div>
  {% endfor %}
</div>


<br>

### Aufsichtsorgan

§7 Mitgliederversammlung

§ 7.1 Der Mitgliederversammlung gehören alle ordentlichen Vereinsmitglieder mit je einer Stimme an.

§ 7.2 In jedem Geschäftsjahres findet eine ordentliche Mitgliederversammlung statt. Sie wird vom Vorstand schriftlich oder in elektronischer Form als E-Mail unter Angabe der Tagesordnung einberufen. Wahlen bzw. Abwahlen von Vorstandsmitgliedern und Änderungen dieser Satzung bedürfen der ausdrücklichen Nennung in der Tagesordnung, mit der eingeladen wird. Die Einladungsfrist beträgt zwei Wochen. Die Frist beginnt mit dem auf die Absendung des Einladungsschreibens folgenden Tag. Das Einladungsschreiben gilt dem Mitglied als zugegangen, wenn es an die letzte vom Mitglied des Vereins schriftlich bekannt gegebene Adresse / E-Mail Adresse gerichtet ist.

§ 8.1 Der Mitgliederversammlung als beschlussfassendem Vereinsorgan obliegen alle Aufgaben, es sei denn, diese sind ausdrücklich laut Satzung einem anderen Vereinsorgan übertragen worden.

<br>

### Mitglieder des Vereins

* Adrian Pohl
* Andreas Pawelke, bis 02.06.2018 Beisitzer, dann Vorstandsvorsitzender
* Andrej Sandorf
* Anja Jentzsch
* Anna Alberts
* Arne Semsrott
* Bela Seeger
* Christian Heise, Vorstandsvorsitzender bis 02.06.2018
* Claudia Schwegmann, Beisitzerin bis 21.11.2018
* Daniel Dietrich, Beisitzer
* Daniel Mietchen
* Edgar Zanella Alvarenga
* Eileen Wagner
* Fiona Krakenbürger
* Friedrich Lindenberg, stellv. Vorstandsvorsitzender bis 02.06.2018
* Hauke Gierow
* Helene Hahn
* Jana Wichmann
* Johanna zum Felde
* Jonathan Gray
* Julia Kloiber
* Knut Perseke
* Kristina Klein, bis 30.06.2017 Geschäftsführerin, seit 11.11.2017 Kassenwartin
* Leonard Wolf
* Lucy Chambers, Beisitzerin, stellv. Vorstandsvorsitzende seit 02.06.2018
* Mara Mendes
* Maria Reimer
* Mark Brough
* Markus Neuschäfer
* Maximilian Voigt
* Michael Hörz
* Michael Peters
* Moritz Neujeffski
* Paula Grünwald
* Rufus Pollock
* Sören Auer, Beisitzer bis 02.06.2018
* Stefan Wehrmeyer
* Stefan Kaufmann
* Timo Lundelius
* Walter Palmetshofer


### Interessenskonflikte

Der Vorstand und einige hauptamtliche Teammitglieder sind auch Vereinsmitglieder und damit stimmberechtigt in der Mitgliederversammlung als Aufsichtsorgan der OKF Deutschland e.V. Der Vorstand ist ehrenamtlich tätig und erhält keine Bezüge, weder Gehälter, Aufwandsentschädigungen noch Sachbezüge. Kein Vorstandsmitglied arbeitet vertraglich in einem OKF-Projekt mit und bezieht daraus Gehalt.
Für das Geschäftsjahr 2018 gab es keine finanziellen, persönlichen oder rechtlichen Abhängigkeitsverhältnisse zwischen den Mitgliedern der OKF Deutschland e.V. und anderen an der Finanzierung der OKF DE beteiligten Organisationen. Es bestanden auch keine Verwandtschaftsverhältnisse innerhalb der Organisation.

<br>

### Internes Kontrollsystem

Das interne Kontrollsystem besteht aus einem projektgesteuerten 4-Augen-Prinzip im operativen Geschäft, einer Prüfung durch eine projektübergreifende Stelle, der Supervision durch die Kassenwartin sowie einer internen Kassenprüfung. Darüber hinaus wird die Buchhaltung von einer externen Steuerkanzlei ausgeführt, welche vereinsschädigende oder gemeinnützigkeitsschädliche Handlungen direkt an die Geschäftsführung melden würde. Damit eine wirksame Kontrolle durch die Mitgliederversammlung stattfinden kann, werden jährlich zwei Kassenprüfer bestimmt. 2018 wurde die Kassenprüfung durch die Mitglieder Mark Brough und Timo Lundelius durchgeführt. Mit der Satzungsänderung vom 11.11.2017 hat die OKF DE festgelegt, dass Kassenprüfer nicht aus Vorstand und Belegschaft kommen dürfen, um mögliche Interessenskonflikte zu vermeiden.


<br><br>
## Eigentümerstruktur, Mitgliedschaften und verbundene Organisationen

**Eigentümerstruktur der Organisation**<br>
An unserem Verein halten weder private noch juristische Personen Anteile. Dies ist auch nicht möglich.


**Mitgliedschaften anderer Organisationen**<br>
Es besteht eine Mitgliedschaft beim Bundesverband Deutscher Stiftungen e.V.


**Verbundene Organisationen**<br>
Wir sind mit keinen Organisationen juristisch verbunden und halten auch keine Anteile an anderen Organisationen.

<br><br>
## Umwelt- und Sozialprofil

**Zum Umweltschutz tragen wir durch folgende Punkte bei:**
* Wir kaufen viele Büromöbel sowie einen Teil unserer IT-Ausstattung gebraucht.
* Wir verwenden vornehmlich Recyclingpapier, Bürobedarf bestellen wir bei einem ökofairen Anbieter.
* Reisen finden in aller Regel mit öffentlichen Verkehrsmitteln statt (2. Klasse).
* Inlandsflüge buchen wir nur in Ausnahmesituationen; Auslandsreisen sind Ausnahmen.
* Wir haben keine Dienstwagen.
* Wir stehen hinter den Forderungen der Bits&Bäume-Konferenz zur Nachhaltigkeit.

<br>

**Zum Sozialprofil gehören die folgenden Punkte:**
* flexible Arbeitszeiten
* freie Einteilung von Heimarbeitstagen
* Tiere am Arbeitsplatz sind erlaubt.
* Weiterbildungsmaßnahmen innerhalb der Arbeitszeit werden unterstützt und teilweise finanziert.
* Das gesamte Team wird mindestens monatlich über die wichtigsten Entwicklungen von Vorstand, Geschäftsführung und Team intern informiert, um stets einen Gesamtüberblick zu haben.
* Alle Mitarbeiter*innen, die der Geschäftsführung nicht direkt unterstehen, haben mehrmals im Jahr Gruppenmeetings mit der Geschäftsführerung.
* Die Geschäftsführerin hat eine »Open-Door-Policy« für alle Mitarbeiter*innen.
