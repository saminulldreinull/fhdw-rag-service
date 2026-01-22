# FHDW RAG Service - Notenauskunft Bot

Ein Demonstrationsprojekt für **Software Engineering & DevOps** an der FHDW.

## 🎯 Zweck

Dieses Repository demonstriert:
- Automatisiertes Testing von LLM-Prompts
- CI/CD-Integration für KI-Systeme
- Erkennung von Prompt-Injection-Angriffen

## 🔒 Sicherheitstests

Bei jedem Push werden automatisch Sicherheitstests ausgeführt:
- **Naive Prompts** werden auf Anfälligkeit getestet
- **Robuste Prompts** mit Guardrails werden validiert
- Der Workflow blockiert unsichere Deployments

## 📁 Struktur

```
fhdw_rag_demo/
└── model_comparison/
    ├── promptfooconfig.yaml  # Hauptkonfiguration
    ├── prompt_naive.txt      # Unsicherer Prompt
    ├── prompt_robust.txt     # Abgesicherter Prompt
    └── tests.yaml            # Testfälle
```

## 🚀 Lokale Ausführung

```bash
cd fhdw_rag_demo/model_comparison
promptfoo eval
```

---
*FHDW Bielefeld | Software Engineering & DevOps*
