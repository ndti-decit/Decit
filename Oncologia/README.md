# Oncologia  
#### Dados abertos do Departamento de Ciência e Tecnologia (DECIT)

### 📝 Resumo

Repositório de dados abertos sobre pesquisas em **oncologia** financiadas pelo DECIT/SCTIE/MS, reunindo informações sobre projetos, anos de contratação, tipos de câncer, modalidades de pesquisa, programas de fomento e valores, para consulta e análise pública.
### 🔍 Descrição

O repositório apresenta informações estratégicas sobre pesquisas científicas em oncologia fomentadas pelo Departamento de Ciência e Tecnologia (DECIT), da Secretaria de Ciência, Tecnologia e Inovação em Saúde (SCTIE/MS).  
O objetivo é promover transparência e possibilitar a consulta pública dos projetos apoiados, evidenciando o esforço institucional na pesquisa em câncer e na produção de evidências científicas para subsidiar políticas públicas e a atenção oncológica no SUS. 

Considerando a relevância da temática do câncer e o volume de estudos apoiados em diferentes tipos de neoplasias, modalidades de pesquisa (pré-clínica, translacional, clínica, observacional, avaliação de tecnologias em saúde, entre outras) e linhas inovadoras (como terapias avançadas, medicina de precisão e genômica), o painel reúne dados que permitem visualizar a distribuição dos investimentos e das iniciativas em oncologia no país. [file:1]  
Os valores apresentados se referem apenas às pesquisas fomentadas pelo DECIT/SCTIE/MS e por programas vinculados, como PRONON, PROADI-SUS e GENOMAS Brasil, não correspondendo à totalidade dos recursos destinados pelo Ministério da Saúde ao tema. 

### 📁 Estrutura do repositório

- `dados-oncologia/`: arquivos em CSV com os dados abertos para download.
- `documentacao/`: documentação e dicionário de dados. 

### 📖 Dicionário de Dados

| Coluna                 | Descrição                                                             | Tipo     |
|------------------------|-----------------------------------------------------------------------|----------|
| id                     | Identificador único do projeto                                       | Texto    |
| ano_contratacao        | Ano de contratação                                                   | Texto    |
| titulo                 | Título do projeto                                                    | Texto    |
| objetivo               | Objetivo do projeto                                                  | Texto    |
| tipo_cancer            | Tipo de câncer ou grupo tumoral principal                            | Texto    |
| area_tematica          | Área ou grupo temático da pesquisa em oncologia                      | Texto    |
| tipo_pesquisa          | Tipo de pesquisa (pré-clínica, translacional, clínica, etc.)         | Texto    |
| programa               | Programa de financiamento (ex.: PRONON, PROADI-SUS, GENOMAS Brasil)  | Texto    |
| instituicao            | Nome da instituição proponente                                       | Texto    |
| sigla_instituicao      | Sigla da instituição proponente                                      | Texto    |
| uf_instituicao         | Unidade Federativa da instituição                                    | Texto    |
| valor_projeto          | Valor do projeto                                                     | Decimal  |
| status                 | Status de execução do projeto                                        | Texto    |
| duracao_meses          | Duração prevista em meses                                            | Inteiro  |
| ano_previsao_conclusao | Ano previsto para a finalização do projeto                           | Texto    |
| terapia_avancada       | Indica se o projeto envolve terapia celular, gênica ou similar       | Texto    |
| subprograma            | Subprograma ou eixo específico (quando aplicável)                    | Texto    |

Veja a descrição completa das variáveis em `/documentacao`. 

### 🤝 Contribuições

Ministério da Saúde – MS 
Secretaria de Ciência, Tecnologia e Inovação em Saúde – SCTIE 
Departamento de Ciência e Tecnologia – DECIT  

Programas e iniciativas de fomento: [file:1]  
- Programa Nacional de Apoio à Atenção Oncológica – PRONON  
- Programa de Apoio ao Desenvolvimento Institucional do SUS – PROADI-SUS  
- Iniciativa Genomas Brasil  
- Outras chamadas públicas e parcerias em oncologia

Unidades e parceiros técnicos:   
- Núcleo de Gestão de Dados e Tecnologia da Informação – NDTI/DECIT  
- Coordenação-Geral de Ações Estratégicas em Pesquisa – CGAEP/DECIT  
- Coordenação-Geral de Evidências e Pesquisa em Saúde – CGPS/DECIT  
- Coordenação de Gestão de Programas de Pesquisa – COPP/DECIT  
- Coordenação de Evidências em Saúde – COEVIS/DECIT  
- Instituições de pesquisa, hospitais de câncer e universidades em todas as regiões do país

### 📊 Fonte de dados

Departamento de Ciência e Tecnologia – DECIT/SCTIE/MS.   
As informações do repositório são atualizadas periodicamente, de acordo com a consolidação dos dados pelas áreas técnicas responsáveis. 

### ✏️ Notas

O painel apresenta dados de projetos e ações estratégicas em oncologia fomentadas pelo DECIT/SCTIE/MS em diversos tipos de câncer (mama, próstata, pulmão, colorretal, hematológicos, infantojuvenis, entre outros) e em diferentes fases da pesquisa (da pré-clínica à avaliação de tecnologias em saúde).  
Os dados refletem valores consolidados informados pelas instituições executoras e pelas áreas técnicas de gestão dos programas. 

### 📄 Como citar

Ministério da Saúde. Secretaria de Ciência, Tecnologia e Inovação em Saúde (SCTIE). Departamento de Ciência e Tecnologia (DECIT). Base de Pesquisas Estratégicas em Oncologia. Brasília: Ministério da Saúde, [Ano]. Dados obtidos em: Repositório de Pesquisas em Oncologia – DECIT/SCTIE/MS.
