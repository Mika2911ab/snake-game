# 🐍 Snake (PyQt5)

Ein simples **Snake**-Spiel mit **PyQt5** – inklusive Pause, Highscores und kleinen Spieleinstellungen.
> ℹ️ **Hinweis:** Das ist eines meiner **ersten Python-Projekte** – der Code ist bewusst einfach gehalten.

## 🎮 Features
- Klassisches Snake-Gameplay (32×32 Spielfeld, Pixel-basiert)
- **Pause**-Funktion & **Restart**-Dialog mit **Top-3 Highscores**
- **Einstellungen vor dem Start**:
    - **Borders**: an/aus (Tod am Rand oder Wrap-Around)
    - **Speed**: 10 Stufen
    - **Fruit Spawn Rate**: 10 Stufen
- HUD mit aktuellem **Score**

## 🕹️ Steuerung
- **Pfeiltasten**: Richtung ändern (keine 180°-Wende in den Körper)
- **Leertaste**: (nicht benötigt)
- **Pause-Button**: pausiert/fortsetzt das Spiel
- Im Game-Over-Dialog: **Restart** startet eine neue Runde
