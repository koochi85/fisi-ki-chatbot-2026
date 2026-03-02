# Analyse-Phase: Open-Source-Alternativen

Hier der Vergleich der ausgewählten Tools (Stand 02.03.2026):

## Vergleich meiner ausgewählten Open-Source-Tools + Botpress (Stand 02.03.2026)

| Tool                | GitHub-Link                          | Stars   | Lizenz      | Letzter Commit              | Fokus & Stärken                                      | LLM/OpenAI-Integration          | Aktivität & Empfehlung für dein Projekt                  |
|---------------------|--------------------------------------|---------|-------------|-----------------------------|------------------------------------------------------|---------------------------------|----------------------------------------------------------|
| **kotaemon**       | Cinnamon/kotaemon                   | 25.2k  | Apache-2.0 | 27. Feb 2026 (vor 3 Tagen) | Saubere RAG-UI für Dokumenten-Chat (QA, Citations)  | Native (OpenAI, Ollama, Azure, lokale LLMs) | ★★★★★ Sehr aktiv – stark für RAG/Dokumenten-Chat       |
| **Rasa**           | RasaHQ/rasa                         | 21.1k  | Apache-2.0 | 18. Dez 2025 (vor ~2,5 Monaten) | Klassisches Conversational AI (NLU + Dialoge)       | Begrenzt / Custom              | ★★ Wartungsmodus – **nicht empfohlen** für 2026         |
| **MaxKB**          | 1Panel-dev/MaxKB                    | 20.2k  | GPLv3      | 02. Mär 2026 (heute!)      | Enterprise-Agent-Plattform (RAG + Workflows)        | Stark (LangChain, OpenAI etc.) | ★★★★★ Extrem aktiv – stark für Agenten & Knowledge-Base |
| **Botpress**       | botpress/botpress                   | 14.6k  | MIT        | 27. Feb 2026 (vor 3 Tagen) | Visueller Chatbot-Builder + LLM-Agents (OpenAI-powered) | Native (GPT/LLM Agents, direkte Key-Integration) | ★★★★★ Sehr aktiv – **sehr stark empfohlen** für einfache Integration & visuelle Flows |

**Kurze Entscheidungshilfe (mein Projekt: KI-Chatbot mit API-Integration, DSGVO/AI Act, Systemintegration, Proof-of-Concept):**

- **Botpress** → Beste Allround-Wahl: Visueller Editor, native OpenAI-Integration, Docker-fähig, sehr aktiv 2026. Passt perfekt zu meinem Originalplan.
- **kotaemon** → Top, wenn starken Fokus auf **RAG/Chat mit Dokumenten/PDFs** gelegt (Citations, Multi-Modal). Auch visuell & aktuell.
- **MaxKB** → Top, wenn **komplexere Agent-Workflows** oder Enterprise-Features (z. B. Knowledge-Base-Management, LangChain).
- **Rasa** → Raus: Zu veraltet, schwache LLM-Unterstützung.

**Mein Favorit:**  
**Botpress** bleibt die Nr. 1 – es ist genau auf meinen Use-Case zugeschnitten 

