## 1. Ziel
Die App wird getestet auf Funktionalität, Benutzerfreundlichkeit, Datenspeicherung und Darstellung. Die Tests erfolgen auf Smartphones (Android 8 und neuer) im Hoch- und Querformat.

## 2. Testumgebung
- Geräte: Android Smartphones (verschiedene Modelle)
- Android-Versionen: Android 8+
- Formate: Hochformat & Querformat
- Netzwerk: Offline & Online
- Displaygrössen: Kleine, mittlere und grosse Displays

---

## 1. Produkt hinzufügen
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 1.1 | Produkt mit Name, Menge, Ort hinzufügen | Produkt erscheint in Liste |
| 1.2 | Produkt ohne Name hinzufügen | Fehlermeldung erscheint |
| 1.3 | Produkt mit extrem langer Bezeichnung | Produkt wird vollständig gespeichert |

---

## 2. Einkaufsliste anzeigen
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 2.1 | App starten | Einkaufsliste wird geladen |
| 2.2 | App drehen (Hoch/Quer) | Liste passt sich korrekt an |
| 2.3 | App schliessen und neu starten | Liste bleibt erhalten |

---

## 3. Artikel abhaken
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 3.1 | Produkt abhaken | Produkt wird als „erledigt“ markiert (z. B. grau) |
| 3.2 | Produkt wieder ent-abhaken | Produkt wird normal angezeigt |

---

## 4. Abgehakte entfernen
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 4.1 | „Erledigte entfernen“ klicken | Nur abgehakte Produkte werden gelöscht |
| 4.2 | Sicherheitsabfrage abbrechen | Kein Produkt wird entfernt |
| 4.3 | Sicherheitsabfrage bestätigen | Abgehakte Produkte verschwinden |

---

## 5. Daten lokal speichern
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 5.1 | App schliessen und wieder öffnen | Daten sind noch da |
| 5.2 | Gerät neu starten | Daten sind noch da |

---

## 6. Hoch- und Querformat
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 6.1 | Liste in Hochformat anzeigen | Anzeige korrekt, keine Überlappung |
| 6.2 | Liste in Querformat anzeigen | Anzeige korrekt, keine Überlappung |
| 6.3 | Während Eingabe drehen | Keine Eingabe geht verloren |

---

## 7. Produkte bearbeiten
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 7.1 | Produkt bearbeiten (Menge ändern) | Änderung wird gespeichert |
| 7.2 | Bearbeiten abbrechen | Keine Änderung wird übernommen |

---

## 8. Produkte löschen
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 8.1 | Produkt löschen | Produkt verschwindet aus Liste |
| 8.2 | Sicherheitsabfrage abbrechen | Produkt bleibt erhalten |
| 8.3 | Sicherheitsabfrage bestätigen | Produkt wird gelöscht |

---

## 9. Liste leeren
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 9.1 | „Liste leeren“ klicken | Alle Produkte verschwinden |
| 9.2 | Sicherheitsabfrage abbrechen | Liste bleibt erhalten |
| 9.3 | Sicherheitsabfrage bestätigen | Liste wird geleert |

---

## 10. Unterstützung älterer Geräte
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 10.1 | App auf Android 8 starten | App läuft ohne Absturz |
| 10.2 | Produkte hinzufügen, abhaken, löschen auf Android 8 | Alles funktioniert fehlerfrei |

---

## 11. Offline-Funktionalität
| Testfall | Beschreibung | Erwartetes Ergebnis |
|---|---|---|
| 11.1 | App ohne Internet starten | App funktioniert normal |
| 11.2 | Produkt hinzufügen & App schliessen (offline) | Produkt bleibt erhalten |
