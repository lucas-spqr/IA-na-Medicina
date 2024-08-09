# Projeto de Aplicação

Projeto desenvolvido como conclusão da disciplina de Inteligência Artificial e Tecnologia na Medicina.

Professores: Flávio Seixas, Érito Marques, Cláudio Tinoco.

Alunos: Lucas Maia e Rodrigo Gonçalves.

# Motivação

O Câncer de Tireoide representa o <b> 12° câncer mais comum </b>, com estimativas de 44.020 novos casos e 2.170 óbitos para 2024.

Apresenta uma <b> sobrevida média em 5 anos de 98,4%.</b> 

Os <b>subtipos histológicos diferenciados (papilífero, folicular) são os mais comuns (90%)</b>, apresentando excelente prognóstico, entretanto, <b>15% dos casos em follow-up durante tratamento inicial sofrem recorrência </b>, seja por disseminação tumoral não reconhecida inicialmente (caracterizando persistência), seja por possuir um componente biológico de maior agressividade.

A maioria dos pacientes (> 90%) pode ser classificada nos estágios I e II a partir da classificação TNM, sendo as taxas de recorrência próximas a <b>13% (pacientes de baixo risco)</b>, <b>21 - 36% (pacientes de  moderado risco) </b> e <b>68% (pacientes de alto risco)</b>.

> https://seer.cancer.gov/statfacts/html/thyro.html
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10216352/

# Objetivo

Permitir a <b>avaliação dos fatores associados à maior probabilidade de recorrência do CA de tireoide diferenciado</b>, a fim de determinar os casos que merecem <b>acompanhamento mais estreito </b> durante o follow-up, de modo a facilitar a identificação dos casos recorrentes.

# Link para dataset

> https://archive.ics.uci.edu/dataset/915/differentiated+thyroid+cancer+recurrence

# Próximos passos

<b>Dificuldades identificadas:</b>
- Ausência de explicação das variáveis na página de acesso ao repositório.
- Desproporcionalidade dentro da amostra de instâncias disponíveis para cada variável.
- Dataset pode ser considerado pequeno.
- Possível prejuízo na validação do modelo em outras amostras populacionais.

<b>Possíveis melhorias:</b>
- Identificação dos tipos e tempos de tratamento em cada caso.
- Maior detalhamento das categorias.
- Acompanhamento de um número maior de pacientes, objetivando também maior proporcionalidade dentro das categorias.
- Criação de uma interface intuitiva para inserção de dados de novos pacientes e classificação do desfecho (risco de recorrência).
