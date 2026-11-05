---
Componente: "Cookie Banner"          # Entre as aspas escreve o nome do website
date: "05/11/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://preprod.dados.gov.pt/"   # Entre as aspas escreve o domínio do website
status: "Auditoria a decorrer" # Entre as aspas escreve uma das seguintes opções: "Auditoria a decorrer", "A aguardar correções da entidade", "Concluído" 
---

# Relatório de auditoria

Sítio Web: {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
- Validade do selo: {{ page.validity }}
- Estado: {{ page.status }}

## Relatório {{ page.website }}

<p>O presente relatório resultou da auditoria da informação publicada na <a href="{{ page.a11y_statement }}">Declaração de Acessibilidade e Usabilidade</a>.</p>

Consulte aqui a última atualização: [Relatório {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="ddmmaaaa_report.html">(dd/mm/aaaa). Relatório {{ page.website }}</a></li>
  </ul>
</details>

<hr>

<p><small>2025 - 2026, GitTemplateReports Web (v.1.0.4)</small></p>
