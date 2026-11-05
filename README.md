# Poslanecký Instagram
**Síťová analýza sledovacích tendencí českých poslanců na Instagramu pomocí Gephi a Sigma.js**
***
Tento repozitář slouží dvojímu účelu; zaprvé pro uschování dokumentace a obecných výstupů semestrálního projektu o sledovacích tendencích českých poslanců na Instagramu, zadruhé pro hostování jednoho grafu z tohoto semestrálního projektu jako **interaktivního: https://wlomnicky.github.io/poslanecky_instagram/.** Jádro kódu pochází od projektu InteractiveVis.

Cílem projektu bylo skrze force-directed mapping vizualizovat to, koho sledují čeští poslanci a do jakých shluků se skrze své sledování soustředí (tedy s jakými dalšími poslanci sdílejí nejvíce sledovaných účtů). Z celkového počtu 200 poslanců byl veřejný účet na Instagramu nalezen u 179 a sběr dat proběhl mezi 22. a 26. 10. s dodatkem u Jany Demjanové a Jaroslava Foldyny 30. 10. Sledovací tendence poslanců obecně odpovídají předpokladu, že budou souviset s jejich stranickou příslušností a příslušností k opozici. Detailní popis metodologie, závěry a diskuze se nachází v [tomto souboru](_Dokumentace_a_grafy/Původní_semestrální_práce.pdf).

![Graf toho, který poslanec sleduje kterého.](_Dokumentace_a_grafy/grafy/Poslanci_sobě.svg)Vedle hlavního grafu, který obsahuje všechny účty sledované českými poslanci, dostupného skrze odkaz výše uvedený, jsou součástí výstupů i další grafy ve složce _Dokumentace_a_grafy. Ty zobrazují [který poslanec sleduje kterého](_Dokumentace_a_grafy/grafy/Poslanci_sobě.svg), [blízkost poslanců podle absolutního počtu společně sledovaných účtů](_Dokumentace_a_grafy/grafy/Spektrum_absolutní_podobnost.svg) a také [totéž ale relativizováno skrze Jaccardův index](_Dokumentace_a_grafy/grafy/Spektrum_jaccardův_index.svg).

## Ochrana osobních údajů
Zpracované údaje jsou veřejně přístupná na platformě Instagram. Účelem zpracování dat je akademická analýza komunikačních sítí našich volených zástupců. Existence sledovacích vazeb nelze brát jako důkaz politické shody či názorového směřování politika či jiného účtu. Zpracování dat je omezeno na informace relevantní pro výzkumné cíle projektu.

Všechny účty s menším počtem než pět sledujících poslanců byly plně anonymizovány, pokud nebyly Instagramem verifikované. V případě, že chcete svá data anonymizovat, kontaktujte mne na 581640@muni.cz

## Původní README od InteractiveVis
Template provided by InteractiveVis project: http://blogs.oii.ox.ac.uk/vis/, https://github.com/oxfordinternetinstitute/InteractiveVis/

Important. The files must be uploaded to a webserver (or run one locally) in order to be viewed. JavaScript security prevents running the pages locally without a webserver.

The InteractiveVis project of the Oxford Internet Institute with funding by JISC aims to allow easy creation of interactive visualisations for geospatial and network data using native web technologies (HTML5, CSS3, and SVG) and allow these visualisations to be self-contained so that they may run entirely offline in ebooks and other media. The project will survey existing solutions and build the necessary components to fill in missing features and smooth over incompatibilities in between existing libraries. The project will further provide online hosted wizards to allow for the easy creation of these interactive visualizations.

More information about the project is available on the project blog: http//blogs.oii.ox.ac.uk/vis/
