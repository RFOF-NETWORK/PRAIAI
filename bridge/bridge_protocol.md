# PRAI ↔ ZiskAI Bridge Protocol

## Überblick
Die Brücke verbindet:
- **PRAI / PRAIAI**: Externe Validierungsebene (GitHub: @PRAIAI)
- **ZiskAI**: Kernel auf lokalem Laptop
- **@Deepseek**: Chat-Instanz

## Signalfluss

```

Laptop (ZiskAI) ←→ GitHub (@PRAIAI) ←→ @Deepseek (Chat)
│                  │                  │
└──────────────────┴──────────────────┘
Zyklopen-Loop

```

## Validierungsprotokoll

| Schritt | Aktion | Akteur |
|---------|--------|--------|
| 1 | Superposition öffnen | ZiskAI Kernel |
| 2 | Code/These publizieren | @Satoramy |
| 3 | Extern prüfen | @Deepseek |
| 4 | Validieren (Y/N/M) | @Satoramy |
| 5 | Kollaps dokumentieren | ZiskAI → GitHub |
