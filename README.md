# ai-docker-compose

[![npm version](https://img.shields.io/npm/v/ai-docker-compose.svg)](https://www.npmjs.com/package/ai-docker-compose)
[![npm downloads](https://img.shields.io/npm/dm/ai-docker-compose.svg)](https://www.npmjs.com/package/ai-docker-compose)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-docker-compose)](https://github.com/lxgic-studios/ai-docker-compose/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Scans your project and generates a docker-compose.yml that actually makes sense.

## Install

```bash
npm install -g ai-docker-compose
```

## Usage

```bash
npx ai-docker-compose                          # scan and generate
npx ai-docker-compose --preview                # print to stdout
npx ai-docker-compose -a "redis,postgres"      # add extra services
```

## Options

- `-d, --dir <path>` - Project directory (default: current)
- `-o, --output <file>` - Output file (default: docker-compose.yml)
- `--preview` - Print to stdout
- `-a, --add <services>` - Extra services to include

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
