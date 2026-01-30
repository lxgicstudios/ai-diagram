# ai-diagram

[![npm version](https://img.shields.io/npm/v/ai-diagram.svg)](https://www.npmjs.com/package/ai-diagram)
[![npm downloads](https://img.shields.io/npm/dm/ai-diagram.svg)](https://www.npmjs.com/package/ai-diagram)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-diagram)](https://github.com/lxgic-studios/ai-diagram/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate Mermaid diagrams from your codebase. Supports flowcharts, class diagrams, sequence diagrams, and more.

## Install

```bash
npm install -g ai-diagram
```

## Usage

```bash
npx ai-diagram ./src/
# → Generates flowchart in diagram.mmd

npx ai-diagram ./src/ --type class -o architecture.mmd
# → Class diagram

npx ai-diagram ./src/ --type sequence
# → Sequence diagram of function calls
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Diagram Types

- `flowchart` - Code flow and dependencies (default)
- `class` - Class relationships and inheritance
- `sequence` - Function call sequences
- `er` - Entity relationship diagram
- `state` - State machine diagram

## License

MIT
