# Tetris – 7 Languages

Классическая игра Тетрис, реализованная на 7 языках программирования. Каждая версия поддерживает:

- 7 классических фигур (I, O, T, L, J, S, Z)
- Следующая фигура (next piece)
- Система очков и уровней
- Очищенные линии (lines)
- Управление: ← → ↓ ↑, пробел (падение), P (пауза)
- Хранение рекордов (localStorage / файл)
- Звуковые эффекты (опционально, в некоторых версиях)
- Тёмная тема и цветные блоки

## Реализации

| Язык | Технологии | Особенности |
|------|------------|-------------|
| Python | Pygame / Tkinter | Графика, звук, рекорды в файле |
| Go | Ebitengine | Производительный 2D-движок |
| Rust | ggez / SDL2 | Высокая скорость, минимальные задержки |
| C# | Windows Forms / MonoGame | Классический Windows-интерфейс |
| JavaScript | HTML5 Canvas + Web Audio | Браузерная версия |
| TypeScript | Canvas + классы | Аналогично JS, но с типами |
| Java | Swing / JavaFX | Кроссплатформенный GUI |

## Запуск

### Python (Pygame)
```bash
cd python
pip install pygame
python tetris.py
cd go
go mod tidy
go run tetris.go
cd rust
cargo run
cd csharp
dotnet run
cd csharp
dotnet run
cd js
open index.html
cd ts
npm install
npx webpack
open index.html
cd java
javac Tetris.java
java Tetris
+----------------------+
|   SCORE: 1240        |
|   LEVEL: 3           |
|   LINES: 8           |
|   HIGH: 5000         |
|                      |
|   [PLAYING FIELD]    |
|   ##########         |
|   ##########         |
|   ...                |
|                      |
|   NEXT:  [ ]         |
+----------------------+
