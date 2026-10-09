# isms-governance-lab
An ISMS governance learning project for a fictional remote company, covering risk assessment, gap analysis, access control policies, and action planning.

Version: 0.1 · Stand: 2026-10-09 · Status: Entwurf in Bearbeitung

## Ziel

Dieses Lernprojekt überträgt Grundlagen aus ISO/IEC 27001, ISO/IEC 27002 und dem Risikomanagement auf ein überschaubares Unternehmensszenario. Es zeigt, wie Risiken, interne Soll-Vorgaben, Richtlinien, Maßnahmen und geplante Nachweise miteinander verbunden werden.

Das fiktive Beispielunternehmen Nordlicht Support hat 30 Beschäftigte, arbeitet vollständig remote und nutzt Microsoft 365, ein SaaS-Ticketsystem und Firmenlaptops.

## Dokumente

| Datei                         | Zweck                                                               |
| `01-scope.md`                 | Unternehmensannahmen, Geltungsbereich, Informationswerte und Rollen |
| `02-risk-register.md`         | Bewertungsmethode und drei begründete Risiken                       |
| `03-gap-analysis.md`          | Vergleich der angenommenen Ausgangslage mit internen Soll-Vorgaben  |
| `04-access-control-policy.md` | Entwurf einer Zugriffsrichtlinie                                    |
| `05-action-plan.md`           | Verantwortliche, Prioritäten, Fristen und Abschlusskriterien        |
| `06-mock-audit.md`            | Prüffragen, erwartete Nachweise und Lernaufgaben                    |
| `07-references.md`            | Öffentliche Quellen, Versionen und Grenzen der Aussagen             |

## Ein Beispiel durch alle Dokumente

R-01: Ein ehemaliger Mitarbeiter könnte weiterhin auf Kundentickets zugreifen, weil ein verlässlicher Offboarding-Prozess fehlt.

Dieses Risiko wird über die Dokumente hinweg verfolgt:

- R-01 – Risikoregister: Begründung der angenommenen Eintrittswahrscheinlichkeit und Auswirkung.
- G-01 – Gap-Analyse: Beschreibung der Lücke gegenüber der internen Soll-Vorgabe.
- P-04 – Zugriffsrichtlinie: Regel zum rechtzeitigen Entzug von Zugriffsrechten.
- M-01 – Maßnahmenplan: Umsetzung, Verantwortliche und Abschlusskriterien.
- E-01 – Prüfungsnachweise: Beschreibung der Nachweise, die für eine spätere Prüfung erforderlich wären.

Für einen schnellen Einstieg: Zuerst R-01 in `02-risk-register.md`, anschließend G-01, P-04 und M-01 lesen.

## Einordnung und Grenzen

Die Dokumente bilden eine Lernfallstudie mit erfundenen Unternehmensannahmen. Es wurden keine realen Konten, Systeme oder Beschäftigten geprüft. Alle technischen Maßnahmen sind Vorschläge; ein technischer Rollout oder ein Audit wurde nicht durchgeführt.

Die Normbezüge beruhen auf öffentlichen ISO-Übersichtsseiten und Lerninhalten. Die Fallstudie stellt keine vollständige Normprüfung, keine vollständige Anwendbarkeitserklärung (Statement of Applicability, SoA) und keinen Nachweis einer ISO-Zertifizierung dar.

Eine Bewertung nach NIS2, DORA oder BSI-Grundschutz ist nicht Bestandteil von Version 0.1.

## Nächste Schritte

- [ ] Das Szenario und alle drei Risikobegründungen auf Plausibilität und Konsistenz prüfen.
- [ ] Eine Annahme ändern und die Auswirkungen in allen betroffenen Dokumenten nachführen.
- [ ] Die Fragen in `06-mock-audit.md` mit eigenen Worten beantworten.
- [ ] Änderungen mit aussagekräftigen Git-Commits dokumentieren.

Die inhaltliche Prüfung und Weiterentwicklung der Fallstudie stehen noch aus. Der Bearbeitungsstand wird entsprechend dem tatsächlichen Fortschritt aktualisiert.
