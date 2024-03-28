# DIO-Power-BI-transformando-dados
Bootcamp Python Data Analytics - DIO

## Desafio Processando e Transformando Dados com Power BI
**DESCRIÇÃO:**

Neste desafio será a sua vez de aplicar as etapas de coleta, obtenção e transformação de dados com Power BI e MySQL na Azure.

Descrição do desafio módulo 3 – Processamento de Dados Simplificado com Power BI

* Criação de uma instância na Azure para MySQL
* Criar o Banco de dados com base disponível no github
* Integração do Power BI com MySQL no Azure
* Verificar problemas na base a fim de realizar a transformação dos dados
* Diretrizes para transformação dos dados

Verifique os cabeçalhos e tipos de dados
* Modifique os valores monetários para o tipo double preciso
* Verifique a existência dos nulos e analise a remoção
* Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente
* Verifique se há algum departamento sem gerente
* Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas
* Verifique o número de horas dos projetos
* Separar colunas complexas
* Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção
* Neste processo elimine as colunas desnecessárias.
* Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.
* Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores
* Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.
* Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.
* Agrupe os dados a fim de saber quantos colaboradores existem por gerente
* Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela
