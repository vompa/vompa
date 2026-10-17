# Hallo 👋

Ich entwickle **.NET-Backends**, die sicher mit **KI-Agenten** zusammenarbeiten: C#, Datenbanken, Industrie-Anbindung (OPC UA) und das **Model Context Protocol (MCP)**.

**Website:** [vompa.dev](https://vompa.dev) · **Live-Demos:** [demo.vompa.dev](https://demo.vompa.dev) (OData) · [opc.vompa.dev](https://opc.vompa.dev) (OPC UA) · [LinkedIn](https://www.linkedin.com/in/stephan-emil-jordan-a57084426)

## Ausgewählte Projekte

| Projekt | Worum es geht | Schwerpunkte |
|---|---|---|
| [OPCAgentSample](https://github.com/vompa/OPCAgentSample) | KI-Leitstand für eine simulierte Fertigungshalle: OPC-UA-Daten, Kennzahlen und Claude als Assistent, der Fragen mit Zahlen beantwortet | OPC-UA-Simulator und Collector (HistoryRead, Subscriptions), OEE und Reports, Redis mit verdichteten Zeitbereichen, MCP-Server mit 17 Tools, Vue-3-PWA, Live-Demo auf Azure, 616 Tests |
| [SqlMcpServer](https://github.com/vompa/SqlMcpServer) | MCP-Server, der einem KI-Agenten kontrollierten Lesezugriff auf eine SQL-Datenbank gibt | SQL-Guard, schreibgeschützte Verbindung, API-Key, Rate Limit, Audit-Log, 89 Tests |
| [ODataAgentSample](https://github.com/vompa/ODataAgentSample) | Ein OData-v4-Service, umgebaut für KI-Agenten: gleiche Daten, neue Tools | API-Key und OAuth2/JWT, Rollen (reader/writer), Limits, Klartext-Fehler für Agenten, Datenqualitäts-Funde, Live-Demo auf Azure, 217 Tests |
| [OPCSample](https://github.com/vompa/OPCSample) | OPC-UA-Client mit Rx.NET und persistenter Queue, gehärtet und für Agenten geöffnet | Retry mit Backoff, Idempotenz, Tests ohne OPC-Server, MCP-Zugang, CodeTour |
| [ODataSample](https://github.com/vompa/ODataSample) | Das Original zu ODataAgentSample: OData-v4-Server und Client-Beispiele in .NET 8 | Ausgangspunkt des Umbaus, Pakete ohne bekannte Schwachstellen, 32 Integrationstests |

## Wie ich arbeite

- **Sicher von Anfang an:** Authentifizierung ist Pflicht, Rechte sind minimal (Least Privilege), Eingaben werden geprüft. Mehrere Schutzschichten statt einer einzelnen.
- **Für Agenten gestaltet:** Wenige, gut beschriebene Tools mit festen Limits und Fehlertexten, aus denen ein Modell lernen kann.
- **Nachweisbar:** Tests, CI mit Warnungen als Fehler und eine nachvollziehbare Commit-Historie.
- **Ehrlich dokumentiert:** Jedes README nennt Grenzen und offene Punkte.

## Technologien

C# · .NET 8/10 · ASP.NET Core · EF Core · SQLite · Redis · OData · OPC UA · Rx.NET · MCP · Claude API · OAuth2/JWT · Vue 3 · xUnit · GitHub Actions · Azure Container Apps
