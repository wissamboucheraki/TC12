## Logisim quick notes

Logisim is a simple digital logic simulator used for drawing and testing circuits such as adders, multiplexers, and state machines. It runs as a Java application (a `*.jar` file), so you can launch it with:

```bash
java -jar logisim-evolution.jar
```

Basic workflow:
- Place gates or components from the toolbar (AND, OR, NOT, flip-flops, RAM, etc.).
- Wire components by dragging between pins; green highlights show a valid connection.
- Toggle input pins to simulate and watch outputs update live.
- Use the **Analyzer** tool to build and export truth tables or simplify expressions.

If you need a download, grab the latest Logisim-Evolution release (the actively maintained fork) from its GitHub releases page (https://github.com/logisim-evolution/logisim-evolution/releases). Run the jar with Java 11+.
