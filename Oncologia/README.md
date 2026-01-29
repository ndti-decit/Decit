# Oncologia  
#### Dados abertos do Departamento de Ciência e Tecnologia (DECIT)

### 📝 Resumo

Repositório de dados abertos sobre pesquisas em Oncologia financiadas pelo DECIT/SECTICS/MS, reunindo informações sobre projetos, anos, programas de fomento, grupos temáticos e valores, para consulta e análise pública.

### 🔍 Descrição

O repositório apresenta informações estratégicas sobre pesquisas científicas e tecnológicas em oncologia fomentadas pelo Departamento de Ciência e Tecnologia (DECIT), da Secretaria de Ciência, Tecnologia, Inovação e do Complexo Econômico-Industrial da Saúde (SECTICS/MS).  
O objetivo é promover transparência e possibilitar a consulta pública dos projetos apoiados, oferecendo uma visão consolidada do fomento em câncer e subsidiando a gestão e a formulação de políticas públicas em saúde.

O painel congrega dados de projetos e ações estratégicas do DECIT de 2017 até 2024, com atualização semestral das informações.  
Os valores apresentados são estimativas consolidadas informadas pelas áreas técnicas responsáveis e não correspondem à totalidade dos recursos do Ministério da Saúde destinados à oncologia.

### 📁 Estrutura do repositório

- `dados-oncologia/`: arquivos em CSV com os dados abertos para download.  
- `documentacao/`: documentação técnica, especificação funcional e dicionário de dados.
-  Veja a descrição completa das variáveis em `/documentacao`

### 📖 Dicionário de Dados

Planilha base do painel (lista de projetos em oncologia):

| Coluna                | Descrição                                                                 | Tipo    |
|-----------------------|---------------------------------------------------------------------------|---------|
| id                    | Identificador único do projeto de pesquisa                                | Texto   |
| ano                   | Ano em que o projeto foi submetido/contratado                            | Inteiro |
| titulo_projeto        | Título do projeto de pesquisa                                            | Texto   |
| programa              | Nome do programa de fomento (ex.: PRONON, PROADI-SUS, GENOMAS Brasil)    | Texto   |
| grupo_tematico        | Grupo temático do câncer (ex.: Mama, Próstata, Leucemia, Colorretal)     | Texto   |
| tipo_pesquisa         | Tipo de pesquisa (Avaliação de Tecnologias em Saúde, Clínica, etc.)      | Texto   |
| tipo_terapia_avancada | Classificação quanto à terapia avançada (Terapia Celular, Gênica, etc.)  | Texto   |
| instituicao           | Nome da instituição proponente                                           | Texto   |
| uf_instituicao        | Unidade Federativa da instituição proponente                             | Texto   |
| status                | Situação do projeto (Em execução, Finalizado, Não iniciado)              | Texto   |
| valor_estimado        | Valor estimado do projeto em reais                                       | Decimal |

Observações:  
- Os campos de filtros do painel (Ano, Programa, Tipo de Pesquisa, Tipo de Terapia Avançada, Grupo Temático e Status) são derivados diretamente dessas colunas.  
- A planilha é a base para o cálculo de indicadores como número de projetos, valor estimado total e número de instituições.

### 🤝 Contribuições

Ministério da Saúde – MS  
Secretaria de Ciência, Tecnologia, Inovação e do Complexo Econômico-Industrial da Saúde – SECTICS  
Departamento de Ciência e Tecnologia – DECIT  
Núcleo de Gestão de Dados, Tecnologia e Inovação – NDTI/DECIT

Áreas técnicas parceiras responsáveis pelo fornecimento e validação dos dados das pesquisas em oncologia.

### 📊 Fonte de dados

O painel apresenta dados de projetos e ações estratégicas do DECIT, de 2017 até 2024.  
As informações devem ser atualizadas semestralmente, de acordo com a consolidação realizada pelas áreas técnicas do Departamento.

### ✏️ Notas

O painel está estruturado em blocos de informações, filtros, visão geral, projetos, instituições e detalhamento, permitindo explorar quantitativos de projetos, valores estimados, distribuição por grupo temático, tipo de pesquisa, programa, status de execução e localização das instituições.  
A lista de projetos exibe, para cada registro, título, instituição proponente, UF, ano, programa, grupo temático, status e valor estimado, além do total consolidado em reais.

### 📄 Como citar

Ministério da Saúde. Secretaria de Ciência, Tecnologia, Inovação e do Complexo Econômico-Industrial da Saúde (SECTICS). Departamento de Ciência e Tecnologia (DECIT). Painel de Pesquisas em Oncologia. Brasília: Ministério da Saúde, [Ano]. Dados obtidos a partir da planilha base do Painel de Pesquisas em Oncologia – DECIT/SECTICS/MS.
