# Hallo 👋

Ich entwickle **.NET-Backends**, die sicher mit **KI-Agenten** zusammenarbeiten: C#, Datenbanken, Industrie-Anbindung (OPC UA) und das **Model Context Protocol (MCP)**.

## Ausgewählte Projekte

| Projekt | Worum es geht | Schwerpunkte |
|---|---|---|
| [SqlMcpServer](https://github.com/vompa/SqlMcpServer) | MCP-Server, der einem KI-Agenten kontrollierten Lesezugriff auf eine SQL-Datenbank gibt | SQL-Guard, schreibgeschützte Verbindung, API-Key, Rate Limit, Audit-Log, 51 Tests |
| [ODataAgentSample](https://github.com/vompa/ODataAgentSample) | Ein OData-v4-Service, umgebaut für KI-Agenten: gleiche Daten, neue Tools | Rollen (reader/writer), Limits, Klartext-Fehler für Agenten, Datenqualitäts-Funde, 42 Tests |
| [OPCSample](https://github.com/vompa/OPCSample) | OPC-UA-Client mit Rx.NET und persistenter Queue, gehärtet und für Agenten geöffnet | Retry mit Backoff, Idempotenz, Tests ohne OPC-Server, MCP-Zugang, CodeTour |
| [ODataSample](https://github.com/vompa/ODataSample) | Das Original zu ODataAgentSample: OData-v4-Server und Client-Beispiele in .NET 8 | Ausgangspunkt des Umbaus, Pakete ohne bekannte Schwachstellen |

## Wie ich arbeite

- **Sicher von Anfang an:** Authentifizierung ist Pflicht, Rechte sind minimal (Least Privilege), Eingaben werden geprüft. Mehrere Schutzschichten statt einer einzelnen.
- **Für Agenten gestaltet:** Wenige, gut beschriebene Tools mit festen Limits und Fehlertexten, aus denen ein Modell lernen kann.
- **Nachweisbar:** Tests, CI mit Warnungen als Fehler und eine nachvollziehbare Commit-Historie.
- **Ehrlich dokumentiert:** Jedes README nennt Grenzen und offene Punkte.

## Technologien

C# · .NET 8/10 · ASP.NET Core · EF Core · SQLite · OData · OPC UA · Rx.NET · MCP · xUnit · GitHub Actions
