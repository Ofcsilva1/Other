# Relatórios e visualizações exportadas

Este repositório reúne dois relatórios PDF e um dashboard HTML de RH. Os arquivos são entregáveis exportados; não contêm, por si só, um processo completo de preparação e reprodução dos dados.

## Materiais

- [Dashboard de Vendas](Dashboard%20de%20Vendas.pdf) — PDF de quatro páginas, para leitura estática. Não oferece os filtros interativos do Power BI.
- [Dashboards Prontuário](Dashboards%20Prontu%C3%A1rio.pdf) — PDF de seis páginas. A exportação não comprova relações do modelo, RLS, atualização ou fórmulas.
- [Dashboard de RH em HTML R](Dashboad%20Com%20R.html) — três visualizações: modelo de trabalho, salário médio por departamento e senioridade. O runtime HTML contém flexdashboard/htmlwidgets/Plotly; o fonte R/Rmd não está disponível neste pacote.

## Como abrir

Baixe os PDFs e use um leitor PDF. Para o HTML, baixe o arquivo completo e abra no navegador ou sirva a pasta com `python -m http.server 8000`. Nenhum ambiente R é necessário para visualizar a exportação já gerada. A solicitação opcional a MathJax pode depender de rede; abrir o HTML não equivale a regenerar o relatório em R.

O [portfólio principal](https://ofcsilva1.github.io/Projetos/) reúne os demais projetos. Os Power BI disponíveis no repositório Projetos têm documentação própria; não foi demonstrada equivalência exata entre esses modelos e os PDFs deste acervo.

## Limites de reprodução e próximos arquivos necessários

Para reproduzir as análises, ainda faltam: fonte R/Rmd, versão do R e dependências, dados de entrada publicáveis, regras de limpeza, grão/período, fórmulas e denominadores. Para os PDFs, documentar qual fonte e revisão produziram cada exportação. Nenhuma dessas lacunas foi preenchida com código ou dataset inventado.

A natureza publicável dos dados deve ser confirmada pelo autor antes de ampliar a distribuição. A presença de arquivos neste repositório não comprova que dados tenham sido sintetizados ou anonimizados adequadamente. Não inserir credenciais, dados institucionais ou registros pessoais ao completar as fontes.

Não há suíte de cálculo, build ou lint configurado neste acervo. Verificações de existência de arquivos, links e integridade não certificam a correção das métricas ou a apresentação visual de todas as páginas. Os três originais foram preservados nesta melhoria documental.
