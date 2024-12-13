### Einführung

- Cloud-Kosten können bei unsachgemäßer Nutzung schnell steigen und die Kosten-Nutzen-Balance beeinträchtigen.
- Ziel: Ein Verständnis für die Struktur von Cloud-Kosten entwickeln und Strategien zur Optimierung anwenden.
- Häufige Herausforderungen:
  - Überprovisionierung von Ressourcen
  - Mangelnde Transparenz bei der Nutzung
  - Ineffiziente Skalierung

---

## Optimierungsstrategien

- **Reserved Instances**: 
  - Langfristige Reservierungen für häufig genutzte Workloads.
  - Bietet erhebliche Rabatte im Vergleich zu On-Demand-Ressourcen.
  - Geeignet für vorhersehbare, langfristige Workloads.

- **Spot Instances**:
  - Nutzung von nicht ausgelasteter Cloud-Kapazität zu stark reduzierten Preisen.
  - Ideal für flexible und unterbrechbare Workloads wie Batch-Prozesse.
  - Risiko: Ressourcen können jederzeit zurückgezogen werden.

- **Automatisierte Skalierung**:
  - Dynamische Anpassung von Ressourcen basierend auf der Auslastung.
  - Verhindert Überprovisionierung und spart Kosten in Zeiten geringer Nutzung.

  
---

## Praxis: Budget-Alarm erstellen

### Aufgabe

1. Richte einen Budget-Alarm in AWS ein.
 
2. Überwache die Nutzung mit dem Cost Explorer.