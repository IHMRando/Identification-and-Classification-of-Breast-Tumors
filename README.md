# Processamento de Imagens como Ferramenta para Identificação e Classificação de Tumores de Mama
# Image Processing as a Tool for Identifying and Classifying Breast Tumors
## Apresentação
O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação EA979A - Introdução a Computação Gráfica e Processamento de Imagens, oferecida no primeiro semestre de 2022, na Unicamp, sob supervisão da Profa. Dra. Paula Dornhofer Paro Costa, do Departamento de Engenharia de Computação e Automação (DCA) da Faculdade de Engenharia Elétrica e de Computação (FEEC).

| Nome |	RA |	Curso |
| --- |	--- |	--- |
| Igor Rando |	171959 |	Física Médica |

## Descrição do Projeto
O câncer de mama é o segundo tipo de câncer mais frequente no mundo e o primeiro entre mulheres. Devido à desinformação e à falta de acesso a exames adequados o câncer de mama ainda causa muitas mortes no Brasil.

Este projeto teve como motivação uma iniciação científica que o aluno participou que teve como objeto de estudo redes neurais convolucionais e suas aplicações em imagens médicas. Como o foco da disciplina é o processamento de imagens e não o desenvolvimento de redes neurais, é uma boa oportunidade para explorar o outro lado de um projeto que foi realizado.

O objetivo deste projeto é estudar o diagnóstico do câncer de mama e um possível meio de melhorar a classificação dos tumores. Para isso, serão estudados diversos métodos de processamento de imagens que ajudam na identificação desses tumores. Inicialmente não há intenção de montar um script que faça a classificação automática, pois isso envolve diversos fatores e resultaria em uma rede neural, no entanto, alguns fatores serão analisados e comparados com os dados.

## Plano de Trabalho
- Etapa 1 (2 semanas): Estudos de operações aritméticas e filtros digitais em imagens

Será feito um estudo mais aprofundado de todas as operações aritméticas em imagens, visto que são a base para o entendimento pleno do restante das operações. Após isso, o estudo será focado nos tipos de filtros digitais e suas aplicações, tais como passa-baixa e passa-alta, com foco no último, já que será o mais utilizado posteriormente.

- Etapa 2 (2 semanas): Estudo de detecção de bordas e operações morfológicas em imagens

Em seguida, será conduzido um estudo sobre limiarização alguns operadores de detecção de borda, que serão bem importantes na diferenciação e classificação dos tumores. Os filtros morfológicos e outros possíveis tratamentos da imagem também serão objetos de estudo nesta etapa.

- Etapa 3 (3 semana): Estudo de métodos para diferenciação e classificação de tumores na mama

Nesta etapa o estudo será mais teórico, tendo foco na geometria fractal, na excentricidade de uma elipse e em índices de compacidade e como tais análises podem classificar um tumor. Outras fontes e metodologias também serão pesquisadas neste período, buscando aumentar o número de fatores que podem diferenciar os tumores.

- Etapa 4 (1 semanas): Obtenção de dados

Será feita uma busca para encontrar bases de imagens mamográficas para utilizar nos testes. Pesquisando previamente já foi encontrado um banco de dados pertencente ao LAPIMO (Laboratorio de análise e processamento de imagens médicas e odontológicas), pertencente à USP (Universidade de São Paulo), que contém imagens mamográficas. No entanto, o acesso é liberado somente à pesquisadores cadastrados, então uma busca de como realizar tal cadastro deve ser realizada.

- Etapa 5 (2 semanas): Codificação e testes

Já com acesso à base de imagens, as ferramentas de processamento de imagens serão aplicadas em busca de um algoritmo que, independente do tamanho e formato da mama, consiga identificar os nódulos nas mamas. Diversos testes devem ser feitos para uma maior precisão.

- Etapa 6 (2 semanas): Escrita do relatório final

Por fim, um relatório final será redigido. O tempo de 2 semanas leva em consideração possíveis atrasos em outras etapas e contratempos que possam retardar o andamento do projeto.

## Referências Bibliográficas
PADILHA, Renata Junges; CHICON, Patricia Mariotto Mozzaquatro; ANTONIAZZI, Rodrigo Luiz; DE LIMA, Claudinei. **Processamento de Imagens como Método na Diferenciação dos Tumores de Mama**. Revista Interdisciplinar de Ensino, Pesquisa e Extensão V.5 N.1 2017.

DA SILVA, Thayse Christine. **Detecção de Tumores em Mamografias via Processamento de Imagens**. São José, 2013.

LOPES, Daniel Soares; DA SILVA, Flávio Henrique; BONFIM, Matheus Ferreira. **Desenvolvimento do Algoritmo para Processamento
de Imagens Digitais para Diagnóstico de Melanoma**. Centro Universitário Católico Salesiano Auxilium, Araçatuba, 2013.

CRÓSTA, Á. P. **Processamento digital de imagens de sensoriamento remoto**. UNICAMP, Instituto de Geociencias, 1992.
