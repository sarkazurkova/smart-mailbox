<h2>Chytrá schránka na dopisy/balíčky</h2>

<p>Cílem projektu by byla schránka, která při přijetí doručené pošty pošle email s fotkou. Shránka by měla mít dva vstupy, jeden na obálky - nezamyká se; druhý na balíčky - po vložení většího objektu se dvířka zamknou, zároveň by se těmito dvířky schránka vybírala.</p>
<p>Pro kontrolu, že do schránky bylo opravdu něco vloženo použiju: </p>
<ul>
  <li><b>IR senzor</b> nebo <b>laser + fotodiodu</b> - jestli schránkou něco projde, přeruší to signál</li>
  <li><b>spínač na malé i velké dvířka</b> - po otevření se ověří, jestli byl přerušen i IR senzor (laser)</li>
  <li>pokud přidám váhu, budu ověřovat i tenhle senzor</li>
</ul>

<p>Po kontrole, že opravdu ve schránce něco je, se odešle email s oznámením a (pokud možno i) s fotkou z kamery, která (pokud to půjde) bude umístěna ve schránce. Také, jestli to byly vetší dvířka, kterými byla pošta doručena, zamknou se. Ty se poté odemknou <b>PIN kódem</b> a nebo <b>klíčkem</b> (pokud selže elektronika, atd...)</p>
<p>Nejspíš přidám signalizaci ledkou ze zadní strany</p>
<p>Zamýšlím, že při vložení balíčku většími dvířky, se vygeneruje dočasný PIN kód, který ztratí platnost po prvním otevření. Pokud je schránka prázdná půjde ji otevřít bez pinu (# nebo *).</p>
<p>Také nejspíš oddělím dopisy od balíčků, aby je někdo nepovolaný nemohl vybrat, pokud dvířka nebudou zamčená. Ještě ale nevím jak. </p>
<h2>Technologie které použiji</h2>
<p>Nejdřív se asi poradím, než začnu něco vymýšlet...</p>
