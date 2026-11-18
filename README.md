# Incorporação imobiliária: Lei 4.591/64 e o roteiro jurídico

Skill para agentes de IA assessorarem compradores ou incorporadores em incorporação imobiliária: Lei 4.591/64 comentada artigo por artigo, proteção do comprador, contratos, distrato, patrimônio de afetação, alienação fiduciária e condomínio edilício.

## O que cobre

- **Lei 4.591/64 comentada** — memorial de incorporação, registro, carência, quadro-resumo, distrato (art. 67-A) e patrimônio de afetação (arts. 31-A a 31-F).
- **Alienação fiduciária de imóvel** — arts. 26 e 27 da Lei 9.514/1997, com a redação vigente pós-Lei 14.711/2023 e o Tema 1.288 do STJ.
- **Condomínio edilício** — convenção, regimento interno, assembleia, síndico, despesas e rateio, multipropriedade.
- **Contratos** — 16 modelos extraídos de Rizzardo, 8ª ed., 2021, com item do livro e página de origem, e inventário dos demais modelos com o conteúdo mínimo exigido pela lei.
- **Camada de atualidade** — Leis 13.786/2018, 14.382/2022 e 14.711/2023, com divergências jurisprudenciais marcadas sem escolha de lado.

## Como usar

Copie esta pasta para o diretório de skills do seu agente (por exemplo, `~/.claude/skills/` no Claude Code) e peça para assessorar um caso de incorporação. A skill é carregada quando o assunto é incorporação imobiliária.

Cada regra legal traz o artigo; cada recomendação de método começa com as palavras "como método". Confira o artigo no texto oficial vigente antes de citar em petição ou contrato.

## Estrutura

```
SKILL.md                  # entrada: quando usar, regras e roteiro
references/
  lei-4591-comentada.md           # Lei 4.591/64 artigo por artigo
  quadro-resumo-35a-distrado-67a.md
  afetacao-fiduciaria-habite-se.md
  condominio-edilicio.md
  modelos-rizzardo.md             # 16 modelos (Rizzardo, 8ª ed., 2021)
  modelos-de-contrato.md          # inventário dos demais modelos
  camada-atualidade.md            # vigência e divergências
skill.yaml
```

## Fontes

Lei 4.591/1964, Lei 9.514/1997, Lei 13.786/2018, Lei 14.382/2022, Lei 14.711/2023, Código Civil e jurisprudência do STJ (Tema 1.288). Textos conferidos no Planalto em 2026-11-10. Os modelos de contrato do inventário aguardam os textos originais; nada foi inventado.

## Licença

MIT. Veja `LICENSE`.
