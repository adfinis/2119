===========================       =====================
Network Working Group             Scott Bradner
Request for Comments: 2119        Harvard University
Übersetzung                       Februar 2015
Kategorie:                        bewährte Methoden
Übersetzt von:                    Jean-Louis Fuchs
                                  ganwell@fangorn.ch
===========================       =====================

Mit Schlüsselwörtern Anforderungen in RFCs anzeigen
===================================================

Status dieses Memorandum
------------------------

Dieses Dokument definiert bewähre Methoden für die Internetgemeinschaft und
fordert zu Diskussionen und Vorschlägen zur Verbesserung auf.

Zusammenfassung
---------------

Im Standardisierungsverfahren werden in vielen Dokumenten Schlüsselwörter
verwendet um Anforderungen der Spezifikation aufzuzeigen. Diese Wörter werden
auf gross geschrieben. Dieses Dokument definiert wie diese Wörter in IETF
Dokumenten interpretiert werden sollen. Autoren die diesen Richtlinien folgen,
sollten den folgenden Satz am Anfang ihres Dokuments einfügen:

      Die Schlüsselwörter "MUSS", "DARF NICHT", "VERBOTEN", "ERFORDERLICH",
      "SOLL", "NÖTIG", "NICHT NÖTIG", "SOLL NICHT", "EMPFOHLEN", "DARF" und
      "OPTIONAL" werden nach RFC 2119 interpretiert.

Beachte dass die Aussagekraft dieser Wörter durch die Anforderungen des Dokument
in welchem sie verwendet werden relativiert werden können.

Definition
----------

1. MUSS        Oder die Schlüsselwörter "ERFORDERLICH" oder "NÖTIG", bedeuten
   dass die Definition eine absolute Anforderung der Spezifikation sind.

2. DARF NICHT  Oder das Wort "VERBOTEN" Bedeutet dass die Definitionen ein
   absolutes Verbot der Spezifikation sind.

3. SOLL        Oder das Adjektiv "EMPFOHLEN" bedeuteten dass es in speziellen
   Situationen Gründe geben kann, diese Spezifikation zu ignorieren. Natürlich
   müssen die Auswirkungen voll und ganz Verstanden werden und sorgfältig
   abgewägt werden, bevor von der Spezifikation abgewichen wird.

4. SOLL NICHT  Oder "NICHT EMPFOHLEN" bedeutet dass es gute Gründe in speziellen
   Situationen geben kann, dass dieses Verhalten akzeptabel ja sogar nützlich
   sein kann. Natürlich müssen die Auswirkungen voll und ganz Verstanden werden
   und sorgfältig abgewägt werden, bevor von der Spezifikation abgewichen wird.

5. DARF        Oder "NICHT NÖTIG" oder das Adjektiv "OPTIONAL" bedeuten dass
   dieses Verhalten wirklich optional ist. Ein Anbieter kann entscheiden dieses
   Verhalten einzuschliessen, weil es das Produkt verbessert oder für einen
   speziellen Mark erforderlich ist. Ein anderer Anbieter kann dieses Verhalten
   weglassen. Eine Implementation dieses Verhalten weglässt MUSS bereit sein,
   mit einer anderen Implementation die dieses Verhalten einschliesst zu zu
   interagieren. In der selben Art MUSS eine Implementation die dieses Verhalten
   einschliesst mit einer Implementation die diese Verhalten weglässt
   interagieren können. Natürlich ausschliesslich der Eigenschaft die dieses
   Verhalten anbietet.

Anmerkung fürs Deutsche: Die Schlüsselwörter DÜRFEN dekliniert und konjugiert
werden. Die Grossschreibung ist ausreichend um die Schlüsselwörter zu erkennen.
"NICHT" kann mit "KEIN" ersetzt werden, wie im Deutschen üblich ist.

Abgrenzung
----------

1. Leitlinie für die Verwendung dieser Richtlinie

   Die Gebote die in diesem Memo definiert sind, sollen sparsam und mit Sorgfalt
   eingesetzt werden. Im speziellen ist es NÖTIG sie nur zu benutzen wo es für
   die Interaktion wichtig ist oder um nachteiliges Verhalten auszuschliessen.
   Sie DÜRFEN KEINE Implementationsdetails vorschreiben, welche unabhängig von
   der Interaktion sind.

2. Sicherheitsbedenken

   Diese Begriffe werden oft verwendet und sicherheitsrelevantes Verhalten zu
   definieren. Ein MUSS oder SOLL wegzulassen kann oder etwas zu tun das als
   DARF NICHT oder SOLL NICHT definiert ist, kann subtile Auswirkungen haben.
   Autoren sollten sich Zeit nehmen um über Sicherheitsauswirkungen
   nachzudenken, da die Anwender des Dokuments unter Umständen nicht über die
   selbe Erfahrung und Hintergrundwissen verfügen.

Danksagung
----------

Die Definitionen basieren auf  existierender RFCs. Zusätzlich sind
Anmerkungen einer Reihe von Leuten eingeflossen, unter anderem Robert Ullmann,
Thomas Narten, Neal McBurnett and Robert Elz.

9. Adress des Autors::

      Scott Bradner
      Harvard University
      1350 Mass. Ave.
      Cambridge, MA 02138

      phone - +1 617 495 3864

      email - sob@harvard.edu
