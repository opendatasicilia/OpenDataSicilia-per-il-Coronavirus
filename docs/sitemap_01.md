---
disqus: ""
hide:
  - navigation
  - toc
---
<body>
<script>
    var callback = function(){
        alert('A callback was triggered');
    }
    var config = {
        startOnLoad:true,
        flowchart:{
            useMaxWidth:true,
            htmlLabels:true,
            curve:'cardinal',
        },
        securityLevel:'loose',
    };

    mermaid.initialize(config);
  </script>
</body>

# Mappa del sito

``` mermaid
flowchart TD
A(fa:fa-home Home page&nbsp;) 
A -...- B(fa:fa-file-image-o Elaborazioni&nbsp;);
A -...- C(fa:fa-map Mappe&nbsp;);
A -...- D(fa:fa-database Dati vaccinali&nbsp;);
A -...- E(InformaCOVID&nbsp;);
A -...- F(fa:fa-users About&nbsp;);
B -...- L(onData&nbsp;);
B -...- M(OpenDataSicilia&nbsp;);
B -...- N(fa:fa-github Repo Github&nbsp;);
C -...- G(fa:fa-map Sicilia - Adesioni Campagna Vaccinale&nbsp;);
C -...- H(fa:fa-tachometer Dashboard di Guenter Richter&nbsp;);
C -...- I(fa:fa-map InformaCOVID - Mappa dei comuni che hanno aderito&nbsp;);
D -...- O(fa:fa-tachometer Dashboard&nbsp;)
D -...- P(fa:fa-file-text Report vaccini&nbsp;)

click A "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/" _self
click B "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/elaborazioni/ondata/" _self
click C "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/mappe/farm_vaccini_anticovid/" _self
click D "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/vaccini/sit_vaccini/" _self
click E "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/info_covid/informa_covid/" _self
click F "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/ods/" _self
click G "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/mappe/farm_vaccini_anticovid/" _self
click H "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/mappe/mappa_vaccini_gjrichter/" _self
click I "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/mappe/mappa_comuni_informacovid/" _self
click L "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/elaborazioni/ondata/" _self
click M "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/elaborazioni/ods/" _self
click O "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/vaccini/sit_vaccini/" _self
click P "https://opendatasicilia.github.io/OpenDataSicilia-per-il-Coronavirus/vaccini/report/" _self
style A fill:#ff9900,stroke:#333,stroke-width:2px
style B fill:#ff99009e,stroke:#333,stroke-width:1px
style C fill:#ff99009e,stroke:#333,stroke-width:1px
style D fill:#ff99009e,stroke:#333,stroke-width:1px
style E fill:#ff99009e,stroke:#333,stroke-width:1px
style F fill:#ff99009e,stroke:#333,stroke-width:1px
style G fill:#ff99006b,stroke:#333,stroke-width:1px
style H fill:#ff99006b,stroke:#333,stroke-width:1px
style I fill:#ff99006b,stroke:#333,stroke-width:1px
style L fill:#ff99006b,stroke:#333,stroke-width:1px
style M fill:#ff99006b,stroke:#333,stroke-width:1px
style N fill:#ff99006b,stroke:#333,stroke-width:1px
style O fill:#ff99006b,stroke:#333,stroke-width:1px
style P fill:#ff99006b,stroke:#333,stroke-width:1px
```