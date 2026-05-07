# IBC · Dashboard GRH PME Portugal

Ferramenta de gestão da framework de Gestão de Recursos Humanos da IBC para empresas clientes PME em Portugal.

---

## Acesso

**URL:** `https://<username>.github.io/ibc-grh/`

Abre diretamente no browser — não requer instalação, login ou servidor de base de dados.

---

## O que inclui

| Secção | Descrição |
|---|---|
| **Visão Geral** | Métricas consolidadas de todas as empresas, progresso médio por pilar, roadmap da framework e benchmarks de maturidade do mercado português |
| **Empresas** | Registo completo de cada empresa cliente com setor, fase, contacto e progresso individual por pilar GRH |
| **Pilares GRH** | As 8 áreas da framework com ações práticas organizadas por fase (Arranque / Crescimento / Consolidação) |
| **Tarefas** | Lista de ações associadas a empresa e pilar, com filtros e tags |
| **Alertas Legais** | Obrigações legais críticas do Código do Trabalho português |
| **Notas** | 4 blocos de notas livres (projeto, próximas ações, obstáculos, quick wins) |

---

## Como guardar e recuperar dados

Os dados ficam guardados no `localStorage` do browser. Para não perder informação ou para trabalhar em computadores diferentes:

**Exportar (fazer backup):**
1. Abre o dashboard
2. Clica em **"↓ Exportar dados JSON"** na sidebar
3. Guarda o ficheiro `ibc-grh-YYYY-MM-DD.json` no Google Drive ou Dropbox

**Importar (recuperar ou mudar de computador):**
1. Abre o dashboard no novo browser/computador
2. Clica em **"↑ Importar dados JSON"** na sidebar
3. Seleciona o ficheiro `.json` guardado

> **Recomendação:** exportar o JSON no final de cada sessão de trabalho.

---

## Os 8 pilares da framework GRH

| Pilar | Obrigação legal | Fase de entrada |
|---|---|---|
| Compliance laboral | ✅ | Arranque |
| Recrutamento e seleção | — | Arranque |
| Integração (onboarding) | — | Arranque |
| Desempenho e feedback | — | Arranque |
| Remuneração e benefícios | ✅ | Crescimento |
| Formação e desenvolvimento | ✅ | Crescimento |
| Retenção e clima | — | Crescimento |
| People analytics | — | Consolidação |

---

## Alertas legais principais (Portugal)

- **Registo de tempos** — obrigatório desde 2019 (Lei n.º 93/2019). Coimas ACT: €612–€9.180
- **Comunicação de admissão** — até ao fim do dia útil anterior ao início do contrato
- **40h de formação/ano** — por trabalhador (art.º 131.º CT). Registo obrigatório no SIGO
- **IRCT aplicável** — verificar sempre o instrumento de regulamentação coletiva do setor
- **Falsos recibos verdes** — fiscalização ACT/AT em aumento
- **Salário mínimo 2025** — €870/mês (verificar mínimos setoriais do IRCT)

---

## Atualizar o dashboard

Quando existir uma nova versão do ficheiro `index.html`:

1. Vai ao repositório no GitHub
2. Clica no ficheiro `index.html`
3. Clica no ícone de lápis (**Edit**)
4. Substitui o conteúdo pelo novo ficheiro
5. Clica **"Commit changes"**

O GitHub Pages atualiza automaticamente em 1–2 minutos.

> Os dados no `localStorage` não são afetados por atualizações do ficheiro HTML.

---

## Estrutura do repositório

```
ibc-grh/
├── index.html     ← dashboard completo (ficheiro único)
└── README.md      ← este ficheiro
```

---

## Desenvolvido por

**IBC** · Framework de GRH para PME Portugal  
Consultoria de Recursos Humanos · 2026
