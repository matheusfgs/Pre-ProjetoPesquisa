# Avaliação de Ferramentas de Teste de software Baseadas em IA para Engenharia de Software em relação aos desenvolvedores.

* João Pedro Moura Santos
* Matheus Fuscaldi Gomes Santos
* Lesandro Ponciano (orientador acadêmico)

# Introdução

1. A área da Engenharia de Software tratada neste trabalho é Testes de Software ( tradicionais) e Testes de Software Automatizados baseados em Inteligência Artificial.

2. O problema que este trabalho busca resolver nessa área é conforme as questões de pesquisa (RQ, do inglês Research Questions) a seguir: (RQ1) Quais são os riscos associados ao uso de ferramentas de IA em testes de software, em comparação com métodos tradicionais, como os testes manuais, e qual é o impacto desse uso no desempenho dos desenvolvedores?

3. Resolver este problema é relevante por que a avaliação da eficácia das ferramentas de teste automatizado baseadas em IA em comparação com as ferramentas e métodos tradicionais busca saber se as ferramentas de teste atuais que utilizam IA são mais ou menos eficazes aos padrões originais, tentando também compreender se há algum impacto referente ao uso dessas ferramentas em relação ao gasto ou aproveitamento de tempo e a mudança na qualidade. 

4. O objetivo geral a ser alcançado na pesquisa é avaliar a eficácia das ferramentas de teste automatizado baseadas em IA em comparação com as ferramentas tradicionais em projetos de engenharia de software, no que diz respeito à cobertura de código, detecção de defeitos e impacto no processo de desenvolvimento com relação ao tempo e qualidade.

5. Os 4 objetivos específicos são: Comparar a cobertura de testes gerados por ferramentas tradicionais e por ferramentas baseadas em IA;
   
    Medir a eficácia das ferramentas de IA na detecção de defeitos comparada às técnicas e ferramentas tradicionais de testes, em específico os testes manuais;

    Comparar o impacto dessas ferramentas de IA e manuais no tempo de desenvolvimento;

    Comparar o tempo gasto por grupos de desenvolvedores antes e depois de utilizarem IA para realizar os testes de softwares.

# Fundamentação Téorica


1. O conceito/teoria principal associado a este trabalho é Testes de Software. A sua definição neste trabalho é "testes de software são realizados para garantir um nível suficiente de qualidade no produto final e para descobrir quaisquer erros no código. É uma solução barata para qualquer problema.", conforme é definido no trabalho "Analyses of Software Testing Approaches" (https://ieeexplore.ieee.org/document/10060147) pelos autores S. Joshi e I. Kumari (2022).
    
2. O conceito/teoria secundário associado a este trabalho é uso da Inteligência Artificial em testes de software. A sua definição neste trabalho é "Os testes com IA combinam algoritmos inteligentes para criar processos automatizados, como a geração de casos de teste baseados em requisitos funcionais e a análise de cobertura de testes", conforme é definido no artigo " The Impact of Artificial Intelligence on Software Testing" (https://ieeexplore.ieee.org/document/8717439) pelos autores H. Hourani, A. Hammad and M. Lafi (2019)
   
3. O conceito/teoria terciário associado a este trabalho é Equipes de Testes de Software, A sua definição neste trabalho é "Uma equipe pessoal qualificada é necessária para realizar a implementação da fase de testes, mas o tamanho da equipe depende de vários fatores. Esses fatores incluem o tamanho do software e a complexidade do projeto desenvolvido". Essa definição é conforme definido no trabalho "A Hybrid Salp Swarm Algorithm with Artificial Neural Network Model for Predicting the Team Size Required for Software Testing Phase" (https://doi.org/10.1109/ICEEI52609.2021.9611128) pelos autores S. Kassaymeh, S. Abdullah, M. Alweshah and A. I. Hammouri(2021).



# Trabalhos Relacionados

1. O trabalho mais relacionado é " Software Testing of Generative AI Systems:Challenges and Opportunities" (https://doi.org/10.1109/ICSE-FoSE59343.2023.00009), publicado no ano de 2023, por que ele estuda e exibe como que ferramentas de inteligência artificial ( em específico o GenAl) permitem a realização de um teste de software autônomo especificando quais são os maiores benefícios e prejuízos encontrados com base no uso da Inteligência artificial em testes de softwares.

3. O segundo trabalho mais relacionado é "Software Testing Research Challenges: An Industrial Perspective" (https://doi.org/10.1109/ICST57152.2023.00008), publicado no ano de 2023, por que ele ressalta os principais desafios enfrentados nas grandes empresas ao implementar testes de softwares em softwares complexos, trazendo a utilização da Inteligência artificial e ML para otimizar testes de software e auxiliar no encontro de erros e manutenções necessárias.

4. O terceiro trabalho mais relacionado é "An Empirical Study of Software Testing Quality based on Natural Experiments" (https://doi.org/10.1109/QRS-C57518.2022.00080), publicado no ano de 2022,  por que o artigo destaca, através de um modelo de análise de robustez, que o tamanho das equipes de teste de software podem influenciar a qualidade dos testes tradicionais: uma equipe maior consegue melhores resultados comparados com outras equipes menores. Levando a compreensão de como mudanças institucionais influenciam os processos de teste, reforçando a aplicabilidade e potencial dos métodos naturais em pesquisas de qualidade de testes de software futuras, que poderão ser utilizadas para comparar com o uso de IA.

   
# Materiais e Métodos

Este trabalho adota uma abordagem **quantitativa**, pois busca comparar métricas de desempenho entre ferramentas de teste de software tradicionais e aquelas baseadas em inteligência artificial (IA). Os dados coletados incluem atributos como cobertura de código, detecção de defeitos, tempo de execução e impacto na qualidade do software. Além disso, a pesquisa é **descritiva**, uma vez que explora características e comportamentos observados no uso dessas ferramentas em diferentes contextos.


* (2). Os materiais utilizados neste trabalho são:

- **Ferramentas de teste tradicionais**: JUnit, Selenium, Visual Studio Code.
- **Ferramentas de teste baseadas em IA**: Testim.io, Applitools, GenAI.

Essas ferramentas foram escolhidas devido à sua popularidade no mercado e à disponibilidade de recursos adequados para a pesquisa.

* (3). Os métodos empregados neste trabalho são:

- Método de Coleta de Dados:
Os dados serão coletados a partir de dois grupos de desenvolvedores: 

1. **Grupo Controle**: Utilizará ferramentas tradicionais de teste de software.
2. **Grupo Experimental**: Utilizará ferramentas baseadas em IA.

Cada grupo será submetido às mesmas tarefas de teste, aplicadas a projetos simulados e reais de engenharia de software. 


- Método de Análise de Dados:
Os dados serão analisados por meio de estatística descritiva e inferencial:
. Comparação entre os resultados do Grupo Controle e Grupo Experimental utilizando testes estatísticos como teste t para duas amostras independentes, teste de software com chat gpt e teste de softwares tradicionais.
. Análise qualitativa dos questionários para identificar percepções subjetivas dos desenvolvedores sobre a eficácia das ferramentas.


* (4). As métricas de avaliação neste trabalho são:
 . Cobertura de Código;
 . Taxa de Detecção de Defeitos;
 . Tempo de Execução;
 . Impacto na qualidade;

* (5). As Etapas de execução do trabalho são:
     

1. **Seleção de Cenários de Teste**:
   
   - Sistemas desenvolvidos em diferentes linguagens e culturas.

2. **Definição de Métricas**:
   - **Cobertura de Código**: Percentual de linhas de código exercitadas pelos testes.
   - **Taxa de Detecção de Defeitos**: Proporção de erros encontrados em relação ao total existente.
   - **Tempo de Execução**: Tempo médio gasto na execução dos testes.
   - **Impacto na Qualidade**: Avaliado por meio de questionários aplicados aos desenvolvedores e análises do software final.

3. **Execução dos Testes**:
   - Ambos os grupos realizarão testes em dois ciclos: antes e depois da introdução das ferramentas de IA.

4. **Coleta de Percepção dos Desenvolvedores**:
   - Questionários para avaliar o impacto no processo de desenvolvimento, incluindo usabilidade e confiança nas ferramentas.
 

###


