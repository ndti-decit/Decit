# Oncologia  
#### Dados abertos do Departamento de Ciência e Tecnologia (DECIT)

### 📝 Resumo

Repositório de dados abertos sobre pesquisas em Oncologia financiadas pelo DECIT/SECTICS/MS, reunindo informações sobre projetos, anos, programas de fomento, grupos temáticos e valores para consulta pública.

### 🔍 Descrição

O repositório apresenta informações estratégicas sobre pesquisas científicas e tecnológicas em oncologia fomentadas pelo Departamento de Ciência e Tecnologia (DECIT), da Secretaria de Ciência, Tecnologia, Inovação e do Complexo Econômico-Industrial da Saúde (SECTICS/MS).  
O objetivo é promover transparência e possibilitar a consulta pública dos projetos apoiados, oferecendo uma visão consolidada do fomento a pesquisas em câncer e subsidiando a gestão e a formulação de políticas públicas em saúde.

A base disponibiliza dados de projetos e ações estratégicas do DECIT de 2017 até 2025, com atualização semestral das informações.  
Os valores apresentados são estimativas consolidadas informadas pelas áreas técnicas responsáveis e não correspondem à totalidade dos recursos do Ministério da Saúde destinados à oncologia.

### 📁 Estrutura do repositório

- `dados-oncologia/`: arquivos em CSV com os dados abertos para download.  
- `documentacao/`: documentação técnica, especificação funcional e dicionário de dados.


### 📖 Dicionário de Dados

A seguir, é possível visualizar o nome, a descrição e o tipo dos campos da tabela:

| Coluna                | Descrição                                                                 | Tipo     |
|-----------------------|---------------------------------------------------------------------------|----------|
| id                    | Identificador único do projeto de pesquisa                                | Texto    |
| ano_contratacao       | Ano em que o projeto foi submetido/contratado                             | Inteiro  |
| titulo                | Título da pesquisa                                                        | Texto    |
| objetivo              | Objetivo da pesquisa                                                      | Texto    |
| grupo_tematico        | Grupo temático relacionado ao tipo de câncer (ex.: Mama, Próstata)        | Texto    |
| tipo_pesquisa         | Tipo de pesquisa (Observacional, Pré-clínica, etc)                        | Texto    |
| programa              | Nome do programa de fomento (ex.: PRONON, PROADI-SUS, GENOMAS Brasil)     | Texto    |
| instituicao           | Nome da instituição proponente                                            | Texto    |
| sigla_instituicao     | Sigla da instituição proponente                                           | Texto    |
| uf_instituicao        | Unidade Federativa da instituição proponente                              | Texto    |
| valor_projeto         | Valor estimado do projeto em reais (R$)                                   | Decimal  |
| status                | Situação do projeto (Em execução, Finalizado, Não iniciado)               | Texto    |
| mes_previsao          | Mês de previsão de término do projeto                                     | Inteiro  |
| ano_previsao          | Ano de previsão de término do projeto                                     | Inteiro  |
| terapia_avancada      | Indica se é um projeto de terapia avançada ou não                         | Booleana |
| tipo_terapia_avancada | Classificação quanto à terapia avançada (Terapia Celular, Gênica, etc.)   | Texto    |



Observações:  
- A planilha é a base para o cálculo de indicadores como número de projetos, valor estimado total e número de instituições.
- Veja a descrição completa das variáveis em `documentacao/`

### 🤝 Contribuições

Ministério da Saúde – MS

Secretaria de Ciência, Tecnologia e Inovação em Saúde - SCTIE

Departamento de Ciência e Tecnologia – DECIT

Núcleo de Gestão de Dados e Tecnologia da Informação – NDTI/DECIT

Coordenação-Geral de Ações Estratégicas em Pesquisa – CGAEP/DECIT

Coordenação-Geral de Evidências e Pesquisa em Saúde – CGPS/DECIT

Coordenação de Gestão de Programas de Pesquisa – COPP/DECIT

Coordenação de Evidências em Saúde – COEVIS/DECIT

### 📊 Fonte de dados

O painel apresenta dados de projetos e ações estratégicas do DECIT, de 2017 até 2025.  
As informações são atualizadas semestralmente, de acordo com a consolidação realizada pelas áreas técnicas do Departamento.

### ✏️ Notas

Os dados apresentados refletem valores consolidados informados pelas áreas técnicas responsáveis.

### 📄 Como citar

Ministério da Saúde. Secretaria de Ciência, Tecnologia e Inovação em Saúde (SCTIE). Departamento de Ciência e Tecnologia (DECIT). Base de Pesquisas Estratégicas em Oncologia. Brasília: Ministério da Saúde, 2026. Disponível em: https://github.com/ndti-decit/Decit/edit/main/Oncologia
