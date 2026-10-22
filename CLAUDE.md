# Central Integrada

Portal único (`index.html`) que reúne as ferramentas internas da Vanbro: menu lateral à esquerda e cada ferramenta aberta num `iframe`.

- **Repositório:** https://github.com/Jonatha-Vanbro/Central_Integrada (GitHub Pages, branch `main`, raiz)
- **Stack:** HTML estático + Bootstrap 5.3.3 + Bootstrap Icons 1.11.3 (CDN). Sem build.
- **Arquivos:** `index.html` (tudo), `logo.png`, `favicon.png`.

## Ferramentas no menu (atributo `data-url`)
| Ferramenta | Endereço |
|---|---|
| Agenda de Treinamentos | jonatha-vanbro.github.io/Agenda-de-Treinamentos/ |
| Agenda de Tarefas – Engenharia | jonatha-vanbro.github.io/Agenda-de-Tarefas-Engenharia-/ |
| Dashboard de Qualidade | jonatha-vanbro.github.io/dashboard-qualidade/ |
| Controle de Materiais – Bobinagem | jonatha-vanbro.github.io/Controle-de-Materiais_Bobinagem/ |
| Procedimentos de Trabalho | jonatha-vanbro.github.io/Procedimentos-de-Trabalho/ |
| Contratos e Licitações | jonatha-vanbro.github.io/Controle-de-Contratos-e-Licita-es-/ |
| Controle de Pedidos – AEGEA | jonatha-vanbro.github.io/Controle-de-Pedidos---AEGEA/ |
| Inspeção de Matéria-Prima | App da Web do Apps Script (URL `script.google.com/.../exec`) |

## Regras de trabalho
- Ao incluir uma ferramenta nova, **não alterar nada do que já está pronto**: só acrescentar o item de menu.
- Nomes curtos no menu.
- Cabeçalho padrão de todas as ferramentas: o do *Controle de Contratos e Licitações* (faixa navy, título + subtítulo, botões de ícone à direita), com título e botões alinhados às bordas dos cards. Ao padronizar, mexer **só** no cabeçalho.
- Publicar = commit + push na `main`; o Pages atualiza em 1–2 min.
