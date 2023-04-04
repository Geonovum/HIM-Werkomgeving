# Software en UML profiel 

<p><keep>Voor de toepassing van het metamodel is een UML-profiel met stereotypen gemaakt voor toepassing in modelleersoftware.</keep></p>

<aside class="issue" title="Documentstructuur bepalend voor waar dit landt, zie ook eerstgenoemde issue H6"></aside>

<aside class="issue" title="Duidelijke verwijzingen opnemen naar profiel en handleiding"></aside>

## Modelleersoftware

<p><keep>Er zijn verschillende sofware tools voor het modelleren van UML modellen. Een veel gebruikte tool is Sparx Enterprise Architect (EA), dit is geen open source maar is wijd verspreid en biedt daardoor een functionaliteit voor interoperabiliteit tussen modelleeromgevingen van verschillende partijen. Er zijn ook weer software tools die op basis van EA afgeleide producten kunnen genereren.</keep></p>

<aside class="note" title="Aanbeveling">
    Aanbeveling: Gebruik van Sparx Enterprise Architect software voor het modelleren vergroot de interoperabiliteit tussen modelleeromgevingen.
</aside>

<p><keep>Voor toepassing van MIM in EA is er een UML-profiel ontwikkeld</keep>: <remove>‘Informatiemodel’ UML-profiel, MIM-alt2: UML profiel voor implementatie binnen EA. Stereotypen conform MIM alternatief 2. Ontwikkeld binnen project Metamodel MIM.</remove>

## Implementatiesoftware

<p><keep>Voor het toepassen van de in UML opgestelde informatiemodellen naar specificaties voor berichtenverkeer is er een vertaling van het informatiemodel naar de structuur van het berichtenverkeer nodig.</keep> <remove>In overeenstemming met het globaal ontwerp Gegevenstromen Laaninfrastructuur zijn linked data en XML gestructureerd berichtenverkeer als implementatie gekozen. Linked data heeft daarbij de voorkeur. Bijzonder vermelding is voor geo-data. Linked data standaarden kunnen daar in worden gebruikt maar zijn echter niet in alle gevallen haalbaar of praktisch. De standaarden van het OGC, INSPIRE en NEN3610 voor geo-data zijn de huidige bewezen en stabiele standaarden die met name tussen overheden goed werken(Globaal ontwerp Gegevensstromen Laaninfrastructuur).</remove></p>

<p><keep>Een tool die gebruikt kan worden voor het genereren van GML (XML) of RDF schema (linked data) van uit het UML van het informatiemodel is <b>Imvertor</b>. Aan de hand van in standaarden beschreven vertaalregels worden de schema’s in het correcte format gegenereerd. Imvertor kan daarnaast verschillende documentatie producten genereren.</keep></p>

<aside class="issue" title="Imvertor uitgebreider behandelen"></aside>