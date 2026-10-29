# mcps

JSON Schemas públicos das configurações lidas pelos MCPs, servidos pelo GitHub Pages. É a URL que vai no `$schema`
dos arquivos de cada projeto, para o editor validar e completar.

| Schema | URL | Arquivo validado | Cópias |
|---|---|---|---|
| [elm/pa.schema.json](elm/pa.schema.json) | `https://dxaraujo.github.io/mcps/elm/pa.schema.json` | `.kiro/config/sdd/pa_<nome>.json` | `mcp-elm/mcp_elm/`, `kiro/powers/sdd/skills/sdd-setup/assets/` |
| [elk/elk.schema.json](elk/elk.schema.json) | `https://dxaraujo.github.io/mcps/elk/elk.schema.json` | `.kiro/config/elk/elk-<ambiente>.json` | `mcp-elk/mcp_elk/` |

Os MCPs e o power validam pela cópia local, nunca pela URL. Ao mudar um schema, mude aqui e copie para cada cópia:
com este repositório clonado ao lado (`../mcps`), os testes de cada um conferem que as cópias são iguais.
