# LeadsDashboard - Versão Web

Este projeto é um painel interativo desenvolvido em Python utilizando Dash, voltado para a análise de leads e desempenho de vendas a partir de planilhas Excel. O sistema permite a visualização de métricas, gráficos e tabelas dinâmicas, facilitando a tomada de decisões estratégicas para equipes de marketing e vendas.

## Funcionalidades

- Upload de arquivos Excel com dados de leads e vendas.
- Filtros por cidade, período e origem dos leads.
- Visualização de diferentes análises:
  - Visão geral dos resultados.
  - Desempenho por canal de aquisição.
  - Evolução mensal de leads e vendas.
  - Eficiência de vendas e conversão.
  - Correlação entre leads e vendas.
- Geração de gráficos interativos e tabelas dinâmicas.
- Exportação de relatórios em PDF e Excel.

## Instalação

1. **Clone o repositório:**
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd VersãoWeb
   ```

2. **Instale as dependências:**
   > Certifique-se de ter o Python 3.8+ instalado.
   ```bash
   pip install dash dash-bootstrap-components pandas numpy plotly openpyxl xlsxwriter reportlab matplotlib seaborn
   ```

3. **Execute o aplicativo:**
   ```bash
   python main.py
   ```

4. **Acesse o painel:**
   Abra o navegador e acesse o endereço exibido no terminal (geralmente http://127.0.0.1:8050).

## Estrutura do Projeto

```
LeadAnalyzer/
  ├── main.py
  └── requirements.txt
```

- `main.py`: Código principal do aplicativo Dash.
- `requirements.txt`: Lista de dependências do projeto.

## Observações

- Os arquivos de dados devem estar em formato Excel (.xlsx).

## Licença

Este projeto é de uso livre para fins acadêmicos e profissionais. Sinta-se à vontade para contribuir! 