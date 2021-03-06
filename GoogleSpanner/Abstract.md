***
[<<< Inhaltsverzeichnis](Inhaltsverzeichnis.md)
***


## 1. Abstract

Cloud Spanner ist Googles skalierbare, multi-versionale, global verteilter und synchron-replizierte Datenbank. Als ein Produkt wurde Google Cloud Spanner direkt für den Einsatz in der Cloud entwickelt. Cloud Spanner vereint die Vorteile einer relationalen Datenbankstruktur mit nicht relationaler Skalierung.<sup>1,</sup><sup>2</sup>

Google Cloud Spanner ist die skalierbare, global verteilte und synchron replizierte Datenbank von Google mit mehreren Versionen. Es ist das erste System, das Daten im globalen Maßstab verteilt und extern konsistente verteilte Transaktionen unterstützt.
Google sichert für Cloud Spanner in ihrem SLA (Service-Level-Agreement) eine Verfügbarkeit von 99,999 % zu ohne planmäßige Ausfallzeiten.<sup>3</sup>  

In dieser Arbeit wird beschrieben, wie Spanner strukturiert ist, der Funktionsumfang, die verschiedenen Entwurfsentscheidungen zugrunde liegenden Gründe und eine Spanners neuartige Time-API, die Zeitunterschiede ausgleicht. Diese API und ihre Implementation sind wichtig um die Konsistenz der Datenbank zu wahren. Eine Reihe von Features unterstützt das: Non-Blocking-Reads, Lock-Free Read-Only-Transaktionen und Atomic-Schema-Änderungen.<sup>4</sup>    


Quellen:

  <sup>1</sup>Google: Cloud Spanner. Der erste horizontal skalierbare relationale Datenbankdienst mit Strong Consistency
  
  <sup>2</sup>James C. Corbett (2012)
  
  <sup>3</sup>James C. Corbett (2012)
  
  <sup>4</sup> Google: Cloud Spanner. Der erste horizontal skalierbare relationale Datenbankdienst mit Strong Consistency

***


