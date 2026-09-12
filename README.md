# Proposta NovaLex — Precedentes Vinculantes, Relevância e IA

Apresentação do projeto de formação executiva à coordenação acadêmica.

**No ar:** https://tdahfocado.github.io/novalex-precedentes-proposta/

## Sobre

Doze telas navegáveis com as setas do teclado, barra de espaço ou pelos marcadores.
A transição entre telas percorre o corredor de admissibilidade — a metáfora que estrutura
o próprio curso. O agente **LEX** comenta cada tela.

Formação de 40 horas-aula em nove encontros, sobre o regime de relevância da questão de
direito federal infraconstitucional, em vigor desde 3 de setembro de 2026.

## Fontes normativas

Todas as citações foram conferidas em fonte oficial:

- Constituição Federal, art. 105, §§ 2º e 3º (EC 125/2022)
- Lei nº 15.484, de 4 de agosto de 2026 — art. 1.035-A do CPC
- Emenda Regimental STJ nº 55, de 21 de agosto de 2026 (DJe de 26.8.2026)
- Emenda Regimental STJ nº 53, de 30 de junho de 2026

## Técnica

Página única, sem dependência de runtime: CSS 3D e JavaScript vanilla.
Tipografia servida pelo Google Fonts (Fraunces, Archivo, IBM Plex Mono).
Responde a tema claro e escuro, funciona em telefone e respeita `prefers-reduced-motion`.

A página é gerada a partir do arquivo de origem do projeto por `scripts/gerar_site.py`,
que a empacota como documento HTML autônomo.
