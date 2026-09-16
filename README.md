# seiwald-mitschrift

Das ist die README.md-Datei. MD steht für Markdown. Markdown ist eine heutzutage weit verbreitete Auszeichnungssprache(_MarkupLanguage_, [Wikipedia](https://de.wikipedia.org/wiki/Auszeichnungssprache))

Weiter bekannte Auszeichnungssprachen sind:

-Hypertext Markup Language (HTML)
-Extensible Markup Language(XML)
-Yet Another Markup Language (YAML, YML)

## Instalation von Node.js

Javasrcript läuft in normale Umständen in einer Browser-Sandbox (nur im Browser)
Seit ca. 2010 gibt es eine Laufzeitumgebung (_Runtime Environment_) für JS, damit man auch Serverseitig JS programmieren und ausführen kann: [Node.js](https://nodejs.org/en)

## Insatlation von pnpm

Der standardmäßige _Package Manager_ für Node.js ist `npm` (_node package manager_). Eine etwas modernere und inzwischen beliebtere Variante ist [`pnpm`](https://pnpm.io)

## Instalation von strapi

Installation mit dem Skript `pnpm create strapi` daraufhin führt das CLI durch die Installation.
Falls bei der Installation sogenannte `build scripts` nicht ausgeführt werden können, schlägt die CLI die Fehlerbehandlung selbstständig vor:

1. Wechsel in das Installationsverzeichnis (z.B. mit ` cd my-strapi-project`)
2. Neuerlicher versuch der Installation mit `pnpm install`. Dieser scheitert in der Regel - die Build-Skripte müssen mit `pnpm approve builds` manuell freigegebn werden.

## VibeCoding / AgenticEngineering mit VS-Code und GitHub Copilot

VibeCoding passiert in VS-Code in erster Linie über die neu eingeführte Agent View.
Dort können alle Anpassungen der "_Coding Harness_" vorgenommen werden. Wir können unseren _Harmess_ mit verschiedenen Methoden anpassen:

**MCP-Server**
MCP steht für _Model Context Protocoll_. Es ist ein Standard der von Antropic entwickelt wurde. Mit Hilfe von MCP können ChatBots/LLMs (_Lage Language Models_) auf zusätzliche Tools zugreifen, die sie zu Experten in einem bestimmten Themenbereich machen.
