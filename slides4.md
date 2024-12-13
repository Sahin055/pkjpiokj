
# Modul 4: Cloud-Sicherheit und Compliance

### Themen

- Best Practices für Sicherheit
- Identity & Access Management (IAM)
- Datenschutz und Compliance

 

---

# Security Risks
## Risiken der Deployment Models
### Alle Deployment Modelle
- Personal: Unbeabsichtigte bzw. schadhafte Handlungen. Bei managed Services gehören die Admins nicht zum CSC
- Naturkatastrophen
- Angriffe jeglicher Art (Ddos, Malware etc.)
- Non-Compliance zu Gesetzen, Vorschriften etc.
### Public Cloud
- Vendor Lock-In: Abhängigkeit von CSP wird aufgebaut z.B. aufgrund nicht standardisierter Datenformate. Keine/schwere Überführung zu anderen CSPs wann immer CSC möchte
- Vendor Lock-Out: Ebenfalls aufgrund Abhängikeit zu CSP. Tritt ein wenn CSP nicht mehr Verfügbar (z.B. Insolvenz etc.)
- Multi-Tenant Umgebung: Escalation of priviliges/Host escalation (Benutzer kann unberechtigt auf andere Kundenumgebgen zugreifen),
Rechtl. Einbezug von Datenträgern als Beweismaterial etc.
### Hybrid Cloud
- Kombination der Risiken der eingesetzten Deployment Modelle

--- 

# Security Risks
## Risiken der Service Models
Die Service Modelle erben die jeweiligen Risiken des jeweiligen Deployment Model

### IaaS
- Personal: Unbeabsichtigte bzw. schadhafte Handlungen. Bei managed Services gehören die Admins nicht zum CSC
- Angriffe jeglicher Art (Ddos, Malware etc.)
- Fehlendes KnowHow bei CSC durch Verantwortung Betrieb & Security des gesamten Stacks
### PaaS
- Interoperabilitäts Probleme: Da OS durch CSP bereitgestellt/gewartet ist kann es sein das Software von CSC mit Änderungen nicht
kompatibel ist
- Backdoors: PaaS häufig als Entwicklungsumgebung genutzt um Entwicklung dann in produktiv System zu überführen. Kann dazu führen das
Testfälle, Testzugänge mit in Produktion überführt werden und zu Backdoors werden
- Resource Sharing: Teilen der Ressourcen zw. Unterschiedlichen Kunden des CSPs
### SaaS
- Nicht standardisierte Datenformate dadurch Vendor-LockIn
- Resource Sharing: siehe PaaS
- Web App Security: Schwachstellen führen zu weitreichenden Risiken da Zugirff über Browser/API für jedermann erreichbar (Broad Network
Access)

--- 
