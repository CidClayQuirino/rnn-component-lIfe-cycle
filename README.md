# rnn-component-lIfe-cycle
Neural Network to project component life cycle for minor component on mining mobile equipments

**1.	Título do projeto**

__Otimização da condição de equipamentos de mineração, usando manutenção preditiva e IoT com Aprendizado de máquina.__

**2.	Introdução**

Nos últimos anos, diversos são os artigos e estudos demonstrando os avanços no monitoramento de equipamentos industriais, tendo como objetivos a redução a utilização de seres humanos devido aos riscos inerentes, dificuldade de acesso aos locais de execução alem da redução na parada dos equipamentos com a antecipação de falhas, Tian, Y. M. et al. (1992) aponta que por outro lado, a produtividade e utilização dos equipamentos mecânicos continua a aumentar, ou seja, a eficiência e produção com o aumento no nível de automação estão cada vez mais elevados, colaborando ainda mais com a necessidade de melhorar o monitoramento da saúde dos ativos.  

Acrescenta-se a isso a avaliação de que, os equipamentos industriais apresentam dificuldades mesmo com o avanço nas técnicas de automatização, como relatado por Schmidt and Berns (2013) , apontando o fato de a manutenção e inspeção de grandes estruturas com sistemas autônomos ainda é um problema sem solução, eles avaliaram que existem diversas possíveis abordagem com a utilização de robôs para automatizar as inspeções aumentar a qualidade e confiabilidade, contudo ainda existe muito espaço para avanço nestas técnicas em várias áreas.  

Para Park C. et al (2016), a manutenção preditiva atrai mais interesse do que a manutenção de rotina, que é descrita como sendo a manutenção realizada quando ocorre uma falha na máquina. Eles atribuem isso ao fato de que as técnicas de manutenção preditiva ajudam a determinar a condição dos equipamentos ou sistemas em serviço, e possibilitam avaliar e prever quando a manutenção deve ser realizada. A manutenção preditiva permite o agendamento conveniente de ações corretivas e evita paradas inesperadas do equipamento, sendo que a chave é a informação certa no momento certo.   

Ao saber quais equipamentos ou componentes precisam de manutenção, os responsáveis pelo departamento de manutenção podem antecipar as manutenções, e o que seriam paradas não planejadas, podem ser transformadas em paradas mais curtas e mais eficientes, aumentando assim a disponibilidade do equipamento. Esta abordagem geralmente utiliza técnicas estatísticas de controle de processos, para determinar em que ponto as futuras atividades de manutenção serão apropriadas. Para avaliar a condição do equipamento, a manutenção preditiva utiliza testes não destrutivos, sensoriamento e coleta de dados de parâmetros tais como temperatura e vibração, análise de nível sonoro e outros testes em tempo real.  

Além disso, Gbadamosi et al (2021) observa que algumas abordagens atuais exigem o envio de inspetores para áreas, para realizar verificações de rotina, o que representa riscos para a saúde e a segurança dos trabalhadores, por outro lado, quando temos um monitoramento eficiente dos ativos com métodos inovadores de coleta online por exemplo, esse risco pode ser reduzido e até mesmo eliminado.  

Quanto aos ativos utilizados em aplicações de mineração, é possível identificar diferentes níveis de monitoramento, visto que alguns sistemas e componentes possuem maior cobertura por sensoriamento, tais como os componentes principais: Motores de combustão interna, Transmissão, Pneus e Comandos Finais, já os componentes menores, como cilindros, bombas e motores hidráulicos, são poucos os pontos de monitoramento, e quando são identificados, a captura dos dados e o monitoramento é realizado de maneira indireta, como  exemplo podemos citar o monitoramento em alguns modelos de maquinário, onde a temperatura dos componentes do sistema hidráulicos que é feita no tanque, utilizando este dado como sendo a temperatura do sistema e não do componente em si, o que pode gerar retardo na tomada de decisão em caso de variação.   

Artur Skoczylas et al (2023) avalia que cada vez mais é necessário um sistema aprimorado que capture, gerencie e seja eficaz no apoio a decisão para o gestor da manutenção, para isso é fundamental que as empresas empenhem em ter ecossistemas com capacidade de centralizar os vários aspectos importantes dos ativos moveis, a fim de garantir o monitoramento continuo do estado das máquinas de maneira mais ampla, a fim de prever avarias e planejar trabalhos de reparação antecipadamente (Manutenção Preditiva).  

Ferreira, B et al. (2022) aborda a demanda crescente por processos digitalizados a partir da evolução tecnológica na Indústria 4.0, a necessidade de acesso a dados de maneira mais rápida, intuitiva e barata, e indica pontos de desenvolvimento de soluções viáveis e de baixo custo para auxiliar na visualização de dados e na utilização destes em antecipação de falhas.  

Artur Skoczylas et al. (2023) também avalia que na maioria das grandes empresas, as máquinas foram equipadas com sistemas que medem diversos parâmetros, como rotação do motor, temperatura do óleo, pressão do sistema hidráulico, temperatura dos componentes mais importantes, pressão dos pneus, consumo de combustível, velocidade de movimento etc. os sistemas podem enviar dados em tempo real, no entanto, isso não é praticado em grande escala no mercado, devido aos elevados custos operacionais dessa mudança.   

Este potencial de melhora no monitoramento para abranger também os pequenos componentes, foi a oportunidade identificada neste estudo, que indica uma das possibilidades de avançar sobre o processo de Gerenciamento de Monitoramento de Condições (CMMS) ampliando a cobertura para os pequenos componentes, com a aplicação de sensores de temperatura e vibração, a fim de coletar parâmetros e identificar mudanças no comportamento desses parâmetros ao longo de uma série temporal, com isso definir por uma intervenção antes da ocorrência de falhas.  


  - **2.1.	Objetivo**

A principal oportunidade identificada neste estudo, foi a necessidade de otimizar os atuais processos de Gerenciamento de Monitoramento de Condições (CMMS) para pequenos componentes, utilizando para tal, a aplicação de sensores de temperatura e vibração, possibilitando com isso, a coleta em tempo real de parâmetros ao longo de uma série temporal e identificar as variações nos padrões e definir por uma intervenção antes da ocorrência de falhas. 

Com base nessa oportunidade, foi elaborado um projeto de sensoriamento com Internet das Coisas (IoT), para pequenos componentes em uma escavadeira hidráulica de mineração e aplicado em campo em uma situação real de operação de mina de céu aberto.  

A justificativa deste estudo, está nas dificuldades identificadas nas máquinas moveis utilizadas em mineração, de se obter parâmetros preditivos para o monitoramento das condições em pequenos componentes, e com isso, melhorar a previsibilidade de intervenção antes das falhas. 

Logo, este estudo foca no desenvolvimento e aplicação de alternativas viáveis para coleta, análise de projeção de saúde em pequenos componentes, tendo como principal objetivo avançar na manutenção preditiva e na redução de falhas prematura, menor tempo de inatividade, atendendo também os requisitos de segurança, com a menor exposição aos riscos humanos para a inspeção.  

**3.	Material e Métodos**

Para a análise dos dados deste estudo, será utilizada uma base de dados com 8226 observações de temperatura e vibração de ambas as bombas principais da 395, coletados no período de 14 dias de operação como amostra, posteriormente, os dados estarão no PipeLine online, e serão avaliados assim que forem coletados e disponibilizados.  

Os dados foram extraídos em um formato .csv e importados do GitHub para o Python e bibliotecas a seguir:
  - NumPy: Biblioteca que fornece suporte para arrays multidimensionais, juntamente com a ampla coleção de funções matemáticas para operar com análise de dados, computação numérica.  
  - Satsmodels: Biblioteca Python que oferece classes e funções para estimar e interpretar diversos modelos estatísticos, incluindo métodos para ajustar modelos de regressão, análise de séries temporais, testes estatísticos etc.  
  - Scikit-learn: Biblioteca para aprendizado de máquina que fornece uma ampla variedade de algoritmos de aprendizado supervisionado e não supervisionado. 
  - PyGithub: Biblioteca Python que fornece uma interface para interagir com a API do GitHub, facilitando a automatização de tarefas como criação de repositórios.
  - TensorFlow: Biblioteca de código aberto para aprendizado de máquina e inteligência artificial desenvolvida pelo Google, oferece uma estrutura tanto para construir quanto treinar modelos de aprendizado profundo, incluindo redes neurais convolucionais, redes neurais recorrentes e muito mais.

  - **3.1.	Manutenção Preditiva, Preventiva e Corretiva**

A manutenção corretiva pode ser descrita, segundo Nascimento et al. (2020) como sendo a modalidade de manutenção aplicada após a ocorrência da falha, com a finalidade de colocar o ativo em funcionamento novamente ou quando há pera da funcionalidade do equipamento e se pretende reestabelecer a operação. Essa modalidade pode ser dividida em dois tipos, corretiva planejada e não planejada.  

Já a manutenção preventiva, também de acordo com Nascimento et al. (2020) é a modalidade de manutenção aplicada com o intuito de diminuir a probabilidade de falha e manter o desempenho, é desenvolvida através de procedimentos, planos de manutenção e inspeções, executada   em   intervalos   regulares, após os   quais   realiza-se   a substituição ou o reparo de itens em que foram detectadas anomalias, podendo citar como sendo as atividades de manutenção preventiva.

Por último, e considerando sua importância na Industria 4.0, temos a manutenção preditiva, essa modalidade de manutenção se utiliza de dados para as análises em pontos específicos do ativo, tais como, conferência de nível de óleo, análise de vibração e análise de temperatura, sendo comumente aplicada com a finalidade de monitorar o padrão de funcionamento do ativo e identificar potencial de falha quando existente.

Esta última modalidade de manutenção, a preditiva, se caracteriza pelo uso de instrumentos de medição e coleta massiva de dados como ferramenta de apoio a decisão de uma intervenção. Neste sentido, o uso de IoTs vem sendo amplamente usado pela indústria, para o avanço das técnicas de preditiva, e será mais bem detalhado a seguir.

O Avanço do uso de IoTs e seu avanço na indústria 4.0, pode ser considerado a base deste estudo que visa otimizar a condição de equipamentos de mineração, como apresentado no tópico posterior, onde pode ser visto o uso da manutenção preditiva e IoT como sendo a base para aumentar a coleta e disponibilidade de dados de máquina, e avançar na atuação preditiva.
 
Alexandre R. Oliveira (2023) cita essa problemática em seu estudo, descrevendo de forma clara que as máquinas e equipamentos industriais não foram construídos para durar para sempre contudo, podem durar muito mais. Ele acrescenta que os eventos de falhas de ativos são processos de degradação, e que podem ser didaticamente apresentados por meio da curva P-F visto na figura 1, que busca representar a condição de um equipamento ou componente ao longo do tempo, dando claramente uma indicação sobre o avanço da condição x tempo, indicando a necessidade de agir proativamente para evitar a falha.

![Figura 1. Intervalo P-F. Fonte: Oliveira (2023).](G:/RNN_Sensor%20Dynamox/Git%20Reposit%C3%B3rio/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%201.%20Intervalo%20P-F.png)

Oliveira (2023) em seu estudo, também aponta para utilização de tecnologias no monitoramento do intervalo P-F como sendo uma estratégia inteligente com maior assertividade e confiabilidade na manutenção dos seus equipamentos e com isso a equipe de manutenção pode evitar as quebras repentinas, e que as falhas identificadas entre os pontos P e F da curva, podem ser corrigidas evitando uma falha funcional com o uso de softwares, sensores e inteligência artificial realizando a coleta de dados das máquinas, para ter uma visão completa dos processos industriais.


- **3.2.	Internet das coisas IoT**

Como citado por Aguirre (2021), a IoT pode ser considerado um mundo onde os objetos físicos são perfeitamente à rede de informações se tornando parte ativa dos fluxos e processos de negócios Haller et al. (2015), este é um dos principais objetivos do estudo em questão, pois substitui em boa medida, a necessidade de um inspetor ir até o ativo expondo-se ao risco para coleta de dados que podem ser facilmente, e constantemente coletadas pelos sensores.

Aguirre (2021) comenta que o surgimento da IoT de baixo custo promete acesso generalizado a sensores e dados que podem ser usados para a tomada de decisões operacionais. Em seu estudo uso as IoT, foi elaborado em um caso real onde foi aplicado um sistema para informar mudanças na gestão operacional que resultaram na redução do tempo de carregamento, na Figura 2 ele apresenta uma sequência esquemática desde o dispositivo até a aplicação em si, utilizada para avaliar o processo com a otimização das rotas dos caminhões de mineração e no controle da velocidade dos caminhões para maior segurança sem aumento no custo de mineração.

![Figura 2: Device design and network.Fonte: H. Aguirre-Jofre et al (2021)](G:/RNN_Sensor_Dynamox/Git_Repositório/rnn-component-life-cycle/rnn-component-life-cycle-main/VsCode/Figura_2_Device_design_and_network.png)
](G:/RNN_Sensor_Dynamox/Git_Repositório/rnn-component-life-cycle/rnn-component-life-cycle-main/VsCode/Figura_2_Device_design_and_network.png)

O estudo aqui apresentado, também faz uso de dispositivos de IoTs de custo significativamente baixos, com uma camada de análise estática e algoritmos que buscam otimizar o processo de análise dos dados, usando de técnicas de Machine Learning na identificação de variações nos padrões de comportamento consideradas anômalos, demonstrando o potencial do CMMS e da integração de tecnologias avançadas para otimizar o monitoramento de condições em componentes críticos de equipamentos de mineração.

J.P. Dias et al. (2022) em seu artigo “Projetando e construindo sistemas de internet das coisas: um Visão geral do ecossistema “, contribui com uma visão ampla e geral do atual estado da arte sobre como projetar e construir sistemas de IoT, e aponta com clareza os desafios de dessa área.

Na figura 3 e mostrado o aumento do número de dispositivos de IoT por ano, onde J.P. Dias et al. (2022) avaliam tanto o aumento considerável de projetos de pesquisa quando a quantidade de dispositivos, demonstrando o interesse tanto da academia quando das empresas/pessoas por esta solução.


![Figura 3. Contagem do número de dispositivos IoT por ano. Fonte: J.P. Dias et al.(2022)](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%203%20Contagem%20do%20número%20de%20dispositivos%20IoT%20por%20ano.png)

J.P. Dias et al. (2022) relembram que o termo Internet das Coisas foi cunhado por Kevin Ashton por volta de 1999 em uma apresentação sobre o gerenciamento da cadeia de suprimentos, e que posteriormente o termo foi apresentado pelo comitê técnico conjunto da International Organization for Standardization (ISO) e a Comissão Eletrotécnica Internacional (IEC), definiram Internet das Coisas como sendo uma infraestrutura composta por objetos, pessoas, sistemas e recursos de informação todos interconectados, acrescenta-se a isso os serviços inteligentes para permitir que eles processem informações sobre o mundo físico e virtual.

Este trabalho teve como ponto de partida, um estudo prévio que obteve resultados promissores em termos de monitoramento preditivo, utilizando câmera termográfica, e será explicado em detalhes a seguir neste estudo. Com base nesse trabalho anterior, avançamos com este estudo, a fim de expandir o método, empregando mecanismos de Internet das Coisas (IoT) para obter dados diretamente dos componentes, possibilitando a análise de dados para detectar alterações de temperatura e vibração antes de uma falha catastrófica.

A instalação e configuração dos sensores no equipamento foi realizada, considerando a cobertura de 100% dos pequenos componentes, que não são cobertos pelo monitoramento do fabricante, tal como descrito posteriormente nas Figuras 3, a seguir.

![Figuras 4a 4b 4c 4a 4d 4e 4f 4g 4h 4i. Instalação dos dispositivos IoT Temperatura_Vibração nos componentes em campo. Fonte: Próprio Autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figuras%204a%204b%204c%204a%204d%204e%204f%204g%204h%204i.%20Instalação%20dos%20dispositivos%20IoT%20Temperatura_Vibração%20nos%20componentes%20em%20campo.png)

Estes são sensores que coleta e enviam para um repositório na nuvem, os dados de temperatura e vibração dos componentes, o detalhamento deste fluxo e a configuração estão mais bem descritos nos tópicos posteriores de 3.3. e 3.7, onde será descrito com detalhes a aplicação, coleta e tratamento dos dados.

  - **3.3.	Armazenamento na Nuvem**

Neste estudo, considerando os desafios de implementação e o foco na implementação de soluções mais focado na camada de Data Science, foi definido pelo uso de um sensor que coleta temperatura e vibração e que já possui, todo o ecossistema de IoT desenvolvido, eliminando assim a necessidade de estabelece e implementar estes pontos, e permitindo avançar diretamente para a parte de Análise estatística dos Dados após estarem disponibilizados na Nuvem. Ou seja, existe boas opções de soluções compatíveis e disponíveis no mercado para coletar e disponibilizar os dados, sendo algumas de custo mais elevado, outras com mais facilidade de instalação e menor complexidade do possibilitando que o foco desse trabalho fosse direcionado para a análise e projeção dos dados após estarem disponíveis. Na Figura 5 tem uma estrutura básica de camadas de IoTs desde a coleta dos dados, armazenamento e posterior análise dos dados utilizando neste caso, a nuvem.

Como apontado também por J.P. Dias et al. (2022), existem pontos críticos nesta etapa do processo, ligados a heterogeneidade, distribuição lógica e geográfica, preocupações humanas, necessidades de comunicação em tempo real e restrições de energia desempenham um papel fundamental no projeto, desenvolvimento, testes e manutenção da IoT.

![Figura 5. Visão logica de uma Camada comum de Sistema IoT](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%205.%20Visão%20logica%20de%20uma%20Camada%20comum%20de%20Sistema%20IoT.png)

Com isso, definimos pela solução integrada da empresa nacional Dynamox, adquirimos os sensores para instalação em campo + o Gateway, possibilitando o foco de nosso estudo na camada de ETL dos dados. 

O Sistema DynaPredict, coleta e disponibiliza em tempo real todos os dados via API da base da empresa no Google Could para nossa base na nuvem, também no Google Cloud, conforme apresentado na Figura 4. Posteriormente foi desenvolvida todo tratamento e análise dos dados de Temperatura e Vibração conforme será detalhado a seguir neste estudo, tendo como principal foco, as Bombas Principais da escavadeira Caterpillar modelo 395.

A estrutura da Figura 6, já está predisposta para receber os dados de campo de cada um dos sensores de forma online, via o Gateway utilizando sistema GSN 2, 3 ou 4g.

![Figura 6. Visão Arvore de componentes Nuvem de Dados. Fonte: Próprio Autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%206.%20Visão%20Arvore%20de%20componentes%20Nuvem%20de%20Dados.jpg)


  - **3.4.	Series temporais**

Aliene Nielsen (2021) descreve uma história sobre a importância das series temporais em nosso dia a dia, e correlaciona isso a evolução das IoTs, salientando a relevância e importância deles em nosso cotidiano, ele ressalta aumento exponencial do uso das series temporais inicialmente na medicina como tendo o pioneirismo na geração de dados, meteorologia e crescimento econômico vindo posteriormente bem como o mercado de trading e astronomia.

Anderson et al. (2023) avalia uma série temporal como sendo um conjunto de variáveis ordenadas em função do tempo, e que o estudo e modelagem destes dados, é fundamental para compreender o comportamento e realizar previsões sobre determinados dados. Ele orienta para a necessidade de realização de um estudo do tipo de serie temporal que está sendo objeto de análise e projeção, e que em caso de observar que os dados possuem tendência estocástica, é preciso avaliar pois isso pode tornar as previsões imprecisas conforme se afastam do último ponto da amostra. Para tanto, ele orienta a utilização do procedimento para a avaliação da estacionariedade da série, por meio do teste de Dickey-Fuller, como sendo um dos testes de raiz unitária mais tradicionais. A seguir, temos na Eq (1, 2 e 3) representando o teste de Dickey-Fuller.

y_t=∅y_(t-1)+u_t                                                                                                                                   (1)

y_t=β_1+∅y_(t-1)+ u_t                                                                                                                              (2)

y_t=β_1+β_2 t+ ∅y_(t-1)+ u_t                                                                                                                       (3)


em que 𝜙 é um parâmetro a ser estimado, 𝑢𝑡 é um processo de ruído branco, que se caracteriza como uma sequência de variáveis aleatórias independentes e identicamente distribuídas (iid), com média zero e variância constante (𝑢𝑡∼𝑅𝐵 (0, 𝜎2)), 𝛽1é uma constante que representa o intercepto e 𝛽2 é um efeito de tendência. O teste considera como hipótese nula, 𝐻0 ∶ 𝜙= 1, a presença de raiz unitária e como hipótese alternativa, 𝐻1∶𝜙 <|1|, a série sendo estacionária.

Silveira et al. (2022) Na presença de estacionariedade, a função amostral que descreve o processo gerador dos da dos tem a mesma forma em todos os instantes, facilitando a identificação de estimativas dos parâmetros desconhecidos dos modelos especificados, e relaciona alguns avanços nos testes de ADF e sugere a utilização do cálculo do valor- p como determinado a partir da estatística τ no teste ADF, e possíveis interferências no resultado.
	
Em nosso estudo, definiremos o valor-p (p-value) e em caso de valores próximo de zero, indica que há forte evidência estatística contra a hipótese nula de que a série temporal é não estacionária, ou seja, é possível concluir com confiança que a série temporal é estacionária. 
	
Aileen Nielsen (2021) explica, que se a série temporal é estacionária simplifica significativamente a análise e modelagem pois indica que suas propriedades estatísticas, como média, variância e autocorrelação, permanecem constantes ao longo do tempo. Isso permite aplicar uma variedade de técnicas de modelagem e previsão com mais confiança.
	
Aliene Nielsen (2021) separa os modelos estatísticos de series temporais entre, estáticos, modelos de esparo de estado e aprendizado de máquina, sendo que em nosso estudo, utilizaremos alguns destes descritos a seguir, sendo que a avaliação e definição do modelo mais aderente estará condicionada aos resultados de MAE (), MSE e R2 para os seguintes modelos, conforme descrito por Aurélien Géron (2021) como sendo alguns dos métodos estatísticos desenvolvidos para series temporais:

Regressão Linear Simples ou Múltipla: Aurélien Géron (2021) A regressão linear é um modelo simples que pode ser eficaz se houver uma relação linear direta entre as variáveis de entrada e saída.

Modelos Autorregressivos (AR): Modelos autorregressivos consideram a relação entre uma observação atual e observações passadas. Eles são úteis quando há dependência temporal nas séries temporais.

Médias Móveis (MA): Modelos de médias móveis consideram a relação entre uma observação e um erro residual das observações passadas. Eles podem ser combinados com modelos AR para formar modelos ARMA.

Modelos ARIMA (Autoregressive Integrated Moving Average): Aurélien Géron (2021) avalia que os modelos ARIMA combinam componentes de regressão autorregressiva, médias móveis e diferenciação para modelar séries temporais estacionárias ou com tendências conhecidas.

Suavização Exponencial (Exponential Smoothing): Modelos recomendados para suavizar séries temporais e capturar padrões sazonais.

Redes Neurais Recorrentes (RNNs): Como dito por Aurélien Géron (2021), modelos de redes neurais recorrentes, como LSTM e GRU, são eficazes para capturar dependências de longo prazo em séries temporais, sendo a LSTM tem resultados melhores, contudo a GRU e mais rápida no treinamento mesmo que em determinados estudos o resultado da GRU tenha sido melhor.

State Space Models: Modelos recomendados para modelar séries temporais que podem ser decompostas em estados latentes.

Também como concluído por Aliene Nielsen (2021), modelos complicados nem sempre são os melhores, pois o custo-benefício compensa o uso de recursos computacionais adicionais requeridos para sua operação.

Em uma análise e definição de um modelo, e importante pensar se o tempo de treinamento adicional para operar com um modelo de aprendizagem de máquinas complexo valem a pena. 

Aliene Nielsen (2021) também apresenta as diferenças entre os modelos de series temporais univariadas e multivariadas, ou seja, series temporais univariadas possuem apenas uma variável medida ao longo do tempo, já as series temporais multivariadas são series com múltiplas variáveis medidas a cada timestamp. Esta última, são muito uteis para análise, pois muitas vezes as variáveis calculadas são inter-relacionadas, e mostram dependências temporais entre si.

Neste estudo, a serie temporal base para o trabalho de Data Science, possui dados de temperatura e vibração de pequenos componentes da escavadeira Caterpillar 395, contudo, a análise se concentrará em somente uma variável ao longo do tempo.

  - **3.5.	Trabalhos relacionados**

Inicialmente, e como comentado acima, este estudo foi aplicado sem quaisquer usos de tecnologia embarcada, e com a utilização de um inspetor e uma câmera tecnográfica. 

  - **3.6.	Estudo de caso**

Este procedimento operacional requerido anteriormente, demandava uma série de atividades obrigatórias para a compreensão de algum desvio nos parâmetros, sendo seguidas todas as etapas de avaliação de desempenho seguindo as diretrizes do fabricante tais como: 
•	Tempo de descida e subida do cilindro,
•	Pressão hidráulica durante os testes,
•	Taxa de fluxo das bombas hidráulicas.
As Figuras 7a e b representam as pressões hidráulicas do equipamento, antes de realizar o teste de velocidade de descida e subida do implemento.

![Figura 7a. Temperatura do Fluido e Figura 7b. Pressão Hidráulica. Fonte: Próprio autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%207a.%20Temperatura%20do%20Fluido%20e%20Figura%207b.%20Pressão%20Hidráulica.png)

Somente após estes pontos estarem dentro do parâmetro especificação, o teste de temperatura por termografia foi conduzido, em paralelo aos testes de tempo de ciclo e pressão.

Utilizando uma câmera termográfica para registrar o diferencial de temperatura dos cilindros eram feitas medições nas temperaturas, procurando identificar possíveis diferencial térmico foi entre os cilindros, neste caso, e conforme ilustrado na Figura 8, foi possível identificar um diferencial de temperatura de 4,7°C em relação ao lado esquerdo.

![Figura 8. Termografia nos Cilindros de Elevação da Escavadeira. Fonte: Próprio autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%207a.%20Temperatura%20do%20Fluido%20e%20Figura%207b.%20Pressão%20Hidráulica.png)

Os pontos mais quentes dos cilindros foram capturados pela câmera, revelando uma diferença de temperatura de ~5°C entre o cilindro de elevação do lado direito (l/d) e o cilindro de elevação do lado esquerdo (l/e) (Figura 9).

![Figura 9. Termográfica com 5°C entre os pontos dos cilindros de elevação da lança. Fonte: Próprio autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%209.%20Termográfica%20com%205°C%20entre%20os%20pontos%20dos%20cilindros%20de%20elevação%20da%20lança.png)

Após remover e desmontar o cilindro na oficina de reparos, foi possível confirmar que os sintomas observados no campo foram importantes para definir e concluir que o método termográfico pode ser usado com mais segurança para determinar a necessidade de remoção, conforme mostra a Figura 10 a seguir. Isso resultou em uma redução, embora não significativa que iremos explicar mais a seguir, nos custos de reparo e no impacto na contaminação do sistema hidráulico.

![Figura 10. Cilindro na Centro de Reforma. Fonte: Próprio autor](G:\RNN_Sensor%20Dynamox\Git%20Repositório\rnn-component-lIfe-cycle\rnn-component-lIfe-cycle-main\VsCode\Figura%2010.%20Cilindro%20na%20Centro%20de%20Reforma.png)

As Figuras 11a, 11b e 11c fornecem detalhes adicionais após a desmontagem e análise do cilindro, sendo que o modo de falha apresentado na Imagem 7 ilustra a causa do aumento de temperatura no processo termográfico de campo.

![Figura 11ª, b e c. Falha interna cilindro após desmontagem e peritagem. Fonte: Próprio autor](G:\RNN_Sensor%20Dynamox\Git%20Repositório\rnn-component-lIfe-cycle\rnn-component-lIfe-cycle-main\VsCode\Figura%2011a%20b%20e%20c.%20Falha%20interna%20Cilindro%20após%20desmontagem.png)

Com isso, o que foi possível entender é que mesmo tendo sido avaliado antecipadamente, a frequência em que foram realizadas as inspeções e coletas em campo permitiram um avanço da falha até um nível que o sistema já havia sido contaminado, apesar de ter sido removido antes de uma falha catastrófica, tal abordagem permitiu avanço nos significativos na parte interna do componente.

Após os resultados utilizando fluxo anterior, e consequentemente com base na conclusão após desmontagem e reforma, o principal questionamento a ser respondido foi, qual seria a forma de avançar neste processo de coleta e análise dos dados de temperatura a tempo de remover o componente, sem que ele possa estar em um estado de degradação avançado? Como mitigar isso? Como antecipar a falha, a ponto de não deixar esse Modo de Falha ocorrer?

  - **3.7.	Métodos**
As etapas deste trabalho são descritas a seguir no Figura 12, desde a análise inicial até a conclusão.

![Figura 12. EAP projeto produto/processo. Fonte: Próprio autor](G:\RNN_Sensor%20Dynamox\Git%20Repositório\rnn-component-lIfe-cycle\rnn-component-lIfe-cycle-main\VsCode\Figura%2012%20_%20EAP%20projeto%20produto%20processo.png)

  - **3.7.1.	Definição dos requisitos do projeto Brainstorm**

O projeto anterior, apresentado como parte de uma estratégia de evoluir no monitoramento de pequenos componentes em campo, alguns pontos de evolução identificados, e são apresentados a seguir na Figura 13 como sendo as possíveis causas do avanço na falha potencial do cilindro anteriormente analisado, e sugerido ações para mitigar tais anormalidades.

![Figura 13. Ishikawa: Análise possíveis causas. Fonte: Próprio autor](G:\RNN_Sensor%20Dynamox\Git%20Repositório\rnn-component-lIfe-cycle\rnn-component-lIfe-cycle-main\VsCode\Figura%2013.%20Ishikawa%20Análise%20possíveis%20causas.png)

  - **3.7.2.	Definição da tecnologia IoT**

Consequentemente, uma proposta de solução foi requerida, e esquematizada na Figura 14, com sendo um aprimoramento no processo de monitoramento, a fim de estruturar uma análise robusta, com uso de tecnologia de sensoriamento online e métodos estatísticos e suporte decisório mais sólido. 

![Figura 14. New Online Data Collect. Fonte: Próprio autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%2014.%20New%20Online%20Data%20Collect.png)

  - **3.7.3.	Definição do equipamento/componentes para teste/validação em campo**

O equipamento/modelo definido para o piloto deste estudo em campo, foi a Escavadeira Hidráulica Caterpillar 395 primeiramente, por ter sido o modelo de ativo utilizado no primeiro trabalho, utilizando a câmera termográfica apesentado na introdução desse estudo, segundo pela quantidade de ativos deste modelo em campo e terceiro pela sua criticidade para a produção nos clientes.

Já os componentes, foram todos os pequenos componentes que não possuem monitoramento direto pelo sistema embarcado do ativo.

Na Figura 15 temos a escavadeira Caterpillar 395 e os componentes definidos para monitoramento online.

![Figura 15. Escavadeira 395 e componentes a serem monitorados. Fonte: Próprio autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%2015.%20Escavadeira%20395%20e%20componentes%20a%20serem%20monitorados.png)

Já para gerenciamento dos parâmetros, foi definido uma estrutura de Sistema/Componentes conforme apresentado na Figura 16.

![Figura 16. Estrutura de sistemas/Componentes Modelo 395. Fonte: Próprio autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%2016.%20Estrutura%20de%20sistemas_Componentes%20Modelo%20395.png)
** Em verde, o componente definido para análise neste estudo

  - **3.7.4.	Pontos de Instalação e Coleta**

Para a análise e apresentação dos resultados, foi utilizando alguns modelos de análise estatística de series temporais, com foco nos dados coletados para os componentes Bomba Principal P1 e P2, como apresenta a Figura 17 a seguir, tanto por ser o componente mais crítico para o funcionamento do ativo pelo custo, impacto na disponibilidade física e por causar um dado consequentes alto quando em uma parada não programada.

Os dados de temperatura e vibração da bomba principal foram separados e tratados conforme apresentado a seguir, para posteriormente, ser elaborada a abordagem de Machine Learning mais apropriada.

![Figura 17. Componentes monitorados. Fonte: Próprio autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%2017.%20Componentes%20monitorados.png)

%pip install markdown
%pip install statsmodels
%pip install scikit-learn
%pip install PyGithub
%pip install gitpython
%pip install statsmodels
%pip install dash
%pip install xlwt
%pip install openpyxl
%pip install tensorflow
%pip install scipy


# Atualizar pacotes
import numpy as np
import os
import pandas as pd
from datetime import datetime
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.graph_objects as go
from plotly.subplots import make_subplots
from IPython.display import Image
from sklearn.svm import SVR

from zipfile import ZipFile
from io import BytesIO
import requests

# URL do repositório no GitHub
repo_url = 'https://github.com/CidClayQuirino/rnn-component-lIfe-cycle/archive/main.zip'
dataframes = []

# Baixe e extraia o arquivo zip do repositório
response = requests.get(repo_url)
with ZipFile(BytesIO(response.content)) as zip_file:
    zip_file.extractall()

# Diretório onde os arquivos .xlsx foram extraídos
extracted_dir = 'rnn-component-lIfe-cycle-main'

# Loop pelos arquivos no diretório extraído
for arquivo in os.listdir(extracted_dir):
    if arquivo.endswith('.xlsx'):
        # Construa o caminho completo para o arquivo
        caminho_completo = os.path.join(extracted_dir, arquivo)

        # Leia o arquivo Excel e adicione-o à lista de DataFrames
        df = pd.read_excel(caminho_completo)

        # Adicione uma coluna 'TagComp' contendo o nome do arquivo sem a extensão
        df['nome_arquivo'] = os.path.splitext(arquivo)[0]

        # Adicione o DataFrame à lista
        dataframes.append(df)
# Concatene todos os DataFrames em um único DataFrame
BDadosTemp = pd.concat(dataframes, ignore_index=True)
BDadosTemp = BDadosTemp[(BDadosTemp != 0).all(axis=1)]
BDadosTemp['Value'] = BDadosTemp['Value'].round(1)
BDadosTemp = BDadosTemp.rename(columns={'Tag': 'Parametro'})
BDadosTemp = BDadosTemp.rename(columns={'nome_arquivo': 'NmeComp'})

# Filtrar as linhas onde a coluna 'NmeComp' é igual a 'MainPumpP2' ou 'MainPumpP1'
df_MainPumps = BDadosTemp[BDadosTemp['NmeComp'].isin(['MainPumpP2', 'MainPumpP1'])]
#df_MainPumps = df_MainPumps.query("Parametro == 'Temperature'")

# Utilize o método groupby para agrupar os dados por 'NmeComp' e, em seguida, aplique describe() a cada grupo
summary = df_MainPumps.groupby('NmeComp').describe()

# Exiba a sumarização dos dados
print(df_MainPumps)

# Filtrar os dados para MainPumpP1 e MainPumpP2
df_MainPumpP1 = df_MainPumps[df_MainPumps['NmeComp'] == 'MainPumpP1']
df_MainPumpP2 = df_MainPumps[df_MainPumps['NmeComp'] == 'MainPumpP2']

# Filtrar as linhas onde a coluna 'NmeComp' é igual a 'MainPumpP2' ou 'MainPumpP1'
df_MainPumpsTemp = df_MainPumps[df_MainPumps['Parametro'].isin(['Temperature'])]
#df_MainPumps = df_MainPumps.query("Parametro == 'Temperature'")

# Utilize o método groupby para agrupar os dados por 'NmeComp' e, em seguida, aplique describe() a cada grupo
summary = df_MainPumpsTemp.groupby('NmeComp').describe()

from scipy import stats
# Filtrar os valores correspondentes a 'MainPumpP1' e 'MainPumpP2'
df_MainPumpsTempP1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']['Value']
df_MainPumpsTempP2 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP2']['Value']
#calcular o Z-score para cada valor na Series de 'MainPumpP1'
z_scores_MainPumpsTempP1 = stats.zscore(df_MainPumpsTempP1)
# Definir um limite para o Z-score (por exemplo, 1 desvio padrão)
z_score_threshold = 0.2
# Encontrar os índices dos outliers para 'MainPumpP1'
outlier_indices_MainPumpsTempP1 = abs(z_scores_MainPumpsTempP1) > z_score_threshold
# Remover as linhas que contêm outliers para 'MainPumpP1'
dfZscore_MainPumpsTempP1 = df_MainPumpsTempP1[~outlier_indices_MainPumpsTempP1]
# Calcular o Z-score para cada valor na Series de 'MainPumpP2'
z_scores_MainPumpsTempP2 = stats.zscore(df_MainPumpsTempP2)
# Encontrar os índices dos outliers para 'MainPumpP2'
outlier_indices_MainPumpsTempP2 = abs(z_scores_MainPumpsTempP2) > z_score_threshold
# Remover as linhas que contêm outliers para 'MainPumpP2'
dfZscore_MainPumpsTempP2 = df_MainPumpsTempP2[~outlier_indices_MainPumpsTempP2]

import pandas as pd
# Aqui está um exemplo de como você poderia definir o outlier_threshold usando o intervalo interquartil (IQR):
Q1 = df_MainPumpsTemp['Value'].quantile(0.25)
Q3 = df_MainPumpsTemp['Value'].quantile(0.75)
IQR = Q3 - Q1
# Definir o limite para considerar algo como outlier
outlier_threshold = 0.2  # Pode ajustar conforme necessário
# Calcular os limites inferior e superior para identificar outliers
lower_bound = Q1 - outlier_threshold * IQR
upper_bound = Q3 + outlier_threshold * IQR
# Filtrar os outliers sem remover os valores maximos superiores
df_filtered = df_MainPumpsTemp[(df_MainPumpsTemp['Value'] >= lower_bound)]
# Separar os resultados para os componentes 'MainPumpP1' e 'MainPumpP2'
df_MainPumpsTempP1IQR = df_filtered[df_filtered['NmeComp'] == 'MainPumpP1']
df_MainPumpsTempP2IQR = df_filtered[df_filtered['NmeComp'] == 'MainPumpP2']
# Coletar e registrar os valores mínimos e máximos para 'MainPumpP1'
min_MainPumpsTempP1 = df_MainPumpsTempP1IQR['Value'].min()
max_MainPumpsTempP1 = df_MainPumpsTempP1IQR['Value'].max()
# Coletar e registrar os valores mínimos e máximos para 'MainPumpP2'
min_MainPumpsTempP2 = df_MainPumpsTempP2IQR['Value'].min()
max_MainPumpsTempP2 = df_MainPumpsTempP2IQR['Value'].max()


  - **3.7.5.	ETL dados de temperatura Bombas Principais 1 e 2.**

A escavadeira de mineração Caterpillar 395 foi selecionada por ser um ativo importante para a produção do cliente, oferecendo versatilidade e por ter sido o mesmo ativo utilizado no projeto anterior, onde a coleta foi feita manualmente. 

Assim, foram instalados os sensores nos componentes, conforme apresentado na Figura 18, e feita a integração com a base de dados da Dynamox, posteriormente foi feita a integração dos dados disponibilizadas na Cloud que iremos utilizar para a análise dos dados de temperatura apresenta o comportamento apresentado no Figura 18 a seguir:

![Figura 18. Distribuição das temperaturas das Bombas 1 e Bombas 2. Fonte: Próprio Autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%2018.%20Distribuição%20das%20temperaturas%20das%20Bombas%201%20e%20Bombas%202.png)

A base de dados original fornecida pela plataforma da Dynamox possui a estrutura mostrada na Figura 19 a seguir, sendo necessário um tratamento nos dados para seguirmos com a análise e projeção:

![Figura 19. Estrutura dos dados de temperatura e vibração. Fonte: Próprio Autor](G:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%2019.%20Estrutura%20dos%20dados%20de%20temperatura%20e%20vibração.png)

Já na Figura 20 foram removidos os dados de Vibração para ambas as Bombas, para que este estudo de análise de dados possamos focar somente na temperatura de ambas as bombas.

![Figura 20. Estrutura dos dados somente com a temperatura.Fonte: Próprio Autor](G:/RNN%20Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figura%2020.%20Estrutura%20dos%20dados%20somente%20com%20a%20temperatura.png)

Para estratificação e análise dos dados foi utilizado o Software Python com interface do Google Colab. Iniciando pela avaliação dos dados gerais, apresentado nas Figuras 21 e 22a seguir para a temperatura da Bomba Principal 1 e 2. 

Os dados analisados e apresentados no Figuras 21 a seguir, são de um período de 17 dias de coleta de temperaturas, iniciando em 11/03/2023 até 28/04/2023, compondo 8226 observações.

![Figuras 21. Resumo dados temperatura Bomba 1 e 2. Fonte: Próprio autor](G:/RNN%20Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figuras%2021.%20Resumo%20dados%20temperatura%20Bomba%201%20e%202.png)

Já a dispersão dos dados é apresentada no Figuras 22 e 23 a seguir, são de um período separadas pela bomba 1 e bomba 2,

![Figuras 22a e b. Perfil temperatura Bomba principal 1 e 2. Fonte: Próprio autor](G:/RNN%20Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figuras%2022a%20e%20b.%20Perfil%20temperatura%20Bomba%20principal%201%20e%202.png)

Na amostra coletada para este estudo, observou-se uma concentração de valores de temperatura formando uma assíntota a esquerda para os dados da Bomba 1, e uma assíntota a direita para os dados da Bomba 2.
Avançando na análise dos dados, utilizamos o pacote “scikit-learn” que como apresentado no livro Géron, A. (2019) são capazes de realizar tarefas de análise de dados de regressão.

import pandas as pd
import matplotlib.pyplot as plt

# Filtrando os dados para MainPumpP1 e MainPumpP2
data_p1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']['Value']
data_p2 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP2']['Value']
# Configurando o layout dos subplots
fig, axes = plt.subplots(nrows=1, ncols=2, figsize=(12, 6))
# Plotando o histograma para MainPumpP1
n1, bins1, patches1 = axes[0].hist(data_p1, bins=30, color='blue', alpha=0.5)
axes[0].set_title('Histograma MainPumpP1')
axes[0].set_xlabel('Frequência Ocorrência MainPumpP1')
axes[0].set_ylabel('Valor de Temperatura')
# Adicionando os valores das barras para MainPumpP1
for rect1 in patches1:
    height1 = rect1.get_height()
    axes[0].text(rect1.get_x() + rect1.get_width()/2., height1, '%d' % int(height1),
            ha='center', va='bottom')
# Plotando o histograma para MainPumpP2
n2, bins2, patches2 = axes[1].hist(data_p2, bins=30, color='red', alpha=0.5)
axes[1].set_title('Histograma MainPumpP2')
axes[1].set_xlabel('Frequência Ocorrência MainPumpP2')
axes[1].set_ylabel('Valor de Temperatura')
# Adicionando os valores das barras para MainPumpP2
for rect2 in patches2:
    height2 = rect2.get_height()
    axes[1].text(rect2.get_x() + rect2.get_width()/2., height2, '%d' % int(height2),
            ha='center', va='bottom')
# Ajustando o layout
plt.tight_layout()
# Exibindo os subplots
plt.show()


from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score

df_MainPumpsTempP1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Selecionar o parâmetro 'Value' como feature (X) e 'NmeComp' como o alvo (y)
X = df_MainPumpsTemp[['Value']].values
y = df_MainPumpsTemp['NmeComp']
# Dividir os dados em conjunto de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
# Criar e treinar o modelo de árvore de decisão
tree_clf = DecisionTreeClassifier(max_depth=2)
tree_clf.fit(X_train, y_train)
# Fazer previsões no conjunto de teste
y_pred = tree_clf.predict(X_test)
# Calcular a precisão do modelo
accuracy = accuracy_score(y_test, y_pred)
print("Precisão do modelo:", accuracy)

df_MainPumps_Trans = df_MainPumpsTemp.pivot(index='Timestamp', columns='NmeComp', values='Value').reset_index()

import pandas as pd
import plotly.graph_objects as go
from plotly.subplots import make_subplots

# Criar um novo dataframe com duas colunas do dataframe sem NA
BDadosTemp_MainPump = df_MainPumps_Trans[['MainPumpP1', 'MainPumpP2', 'Timestamp']].dropna()

# Adicionar uma coluna de dados sequenciais começando em 1 até o número de registros
BDadosTemp_MainPump['Sequence'] = range(1, len(BDadosTemp_MainPump) + 1)

# Criar subplots com plotly
fig_BDadosTemp_MainPump = make_subplots(rows=2, cols=1, shared_xaxes=True, subplot_titles=['(C°)MainPumpP1', '(C°)MainPumpP2'])

# Adicionar traces para MainPumpP1
fig_BDadosTemp_MainPump.add_trace(go.Scatter(x=BDadosTemp_MainPump['Sequence'], y=BDadosTemp_MainPump['MainPumpP1'],
                                             mode='lines', fill='tozeroy', line=dict(color='blue'), name='(C°)MainPumpP1'),
                                  row=1, col=1)

# Adicionar traces para MainPumpP2
fig_BDadosTemp_MainPump.add_trace(go.Scatter(x=BDadosTemp_MainPump['Sequence'], y=BDadosTemp_MainPump['MainPumpP2'],
                                             mode='lines', fill='tozeroy', line=dict(color='blue'), name='(C°)MainPumpP2'),
                                  row=2, col=1)

# Definir limite máximo para o eixo y como 125
fig_BDadosTemp_MainPump.update_yaxes(range=[0, 125], row=1, col=1)
fig_BDadosTemp_MainPump.update_yaxes(range=[0, 125], row=2, col=1)

# Atualizar layout com títulos personalizados e aumentar o tamanho das fontes
fig_BDadosTemp_MainPump.update_layout(
    title_text='Temperatura MainPumpP1 e MainPumpP2 ao longo do tempo',
    title_font_size=24,  # Tamanho da fonte do título
    showlegend=False,  # Desativar a legenda global
    height=800,  # Aumentar a altura do gráfico
    xaxis=dict(
        title='',
        titlefont=dict(size=24),  # Tamanho da fonte do título do eixo x
        tickfont=dict(size=22),  # Tamanho da fonte dos rótulos do eixo x
    ),
    yaxis=dict(
        title='Temperatura (C°)',
        titlefont=dict(size=24),  # Tamanho da fonte do título do eixo y
        tickfont=dict(size=22)  # Tamanho da fonte dos rótulos do eixo y
    ),
    font=dict(size=20)  # Tamanho da fonte para o gráfico inteiro
)

# Ajustar o layout dos subplots
fig_BDadosTemp_MainPump.update_annotations(font_size=20)  # Tamanho da fonte dos títulos dos subplots

# Exibir o gráfico interativo
fig_BDadosTemp_MainPump.show()

  - **3.7.6.	Modelagem matemática**

A seguir as Figuras 23a e b, mostra o teste de Dickey-Fuller, utilizando a biblioteca do python “import adfuller” para identificar o padrão estacionário ou não dos dados. Os resultados dessa análise para a amostra de dados do estudo, apresentaram um Valor-p = 0.000003 para a Bomba P1 e de Valor-p = 0.000009 para a Bomba P2, estão muito próximo de zero, ou seja, indicando que há forte evidência estatística para rejeitar a hipótese nula de que a série é não estacionária, ou seja, este resultado tanto para a Base de dados da Bomba 1 quanto para a Bomba 2, sugere-se que a série temporal seja estacionária.

![Figuras 23a e b. Valor-p para dados Bomba 1 e 2.Fonte: Próprio Autor](G:/RNN%20Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figuras%2023a%20e%20b.%20Valor-p%20para%20dados%20Bomba%201%20e%202.png)


import pandas as pd
from statsmodels.tsa.stattools import adfuller

# Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Primeiro, vamos filtrar a série temporal desejada (por exemplo, usando a coluna 'Parametro' para selecionar)
serie_temporalP1 = Df_Pump1['Value']
# Função para testar estacionariedade da série temporal
def test_stationarity(timeseries):
    # Verificar se a série temporal não está vazia
    if timeseries.empty:
        print("Série temporal está vazia.")
        return
    # Estatísticas de rolamento
    rolmean = timeseries.rolling(window=12).mean()
    rolstd = timeseries.rolling(window=12).std()
    # Plotar estatísticas de rolamento
    import matplotlib.pyplot as plt
    plt.plot(timeseries, color='blue',label='Original')
    plt.plot(rolmean, color='red', label='Média Móvel')
    plt.plot(rolstd, color='black', label = 'Desvio Padrão Móvel')
    plt.legend(loc='best')
    plt.title('Estatísticas de Rolamento')
    plt.show()
    # Teste de Dickey-Fuller:
    print('Resultados do Teste Dickey-Fuller:')
    dftest = adfuller(timeseries, autolag='AIC')
    dfoutput = pd.Series(dftest[0:4], index=['Estatística do Teste','Valor-p','#Lags Usados','Número de Observações Usadas'])
    for key,value in dftest[4].items():
        dfoutput['Valor Crítico (%s)'%key] = value
    print(dfoutput)
# Aplicar teste de estacionariedade à série temporal selecionada
test_stationarity(serie_temporalP1)

import pandas as pd
from statsmodels.tsa.stattools import adfuller

# Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump2 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP2']
# Primeiro, vamos filtrar a série temporal desejada (por exemplo, usando a coluna 'Parametro' para selecionar)
serie_temporalP2 = Df_Pump2['Value']
# Função para testar estacionariedade da série temporal
def test_stationarity(timeseries):
    # Verificar se a série temporal não está vazia
    if timeseries.empty:
        print("Série temporal está vazia.")
        return
    # Estatísticas de rolamento
    rolmean = timeseries.rolling(window=12).mean()
    rolstd = timeseries.rolling(window=12).std()
    # Plotar estatísticas de rolamento
    import matplotlib.pyplot as plt
    plt.plot(timeseries, color='blue',label='Original')
    plt.plot(rolmean, color='red', label='Média Móvel')
    plt.plot(rolstd, color='black', label = 'Desvio Padrão Móvel')
    plt.legend(loc='best')
    plt.title('Estatísticas de Rolamento')
    plt.show()
    # Teste de Dickey-Fuller:
    print('Resultados do Teste Dickey-Fuller:')
    dftest = adfuller(timeseries, autolag='AIC')
    dfoutput = pd.Series(dftest[0:4], index=['Estatística do Teste','Valor-p','#Lags Usados','Número de Observações Usadas'])
    for key,value in dftest[4].items():
        dfoutput['Valor Crítico (%s)'%key] = value
    print(dfoutput)
# Aplicar teste de estacionariedade à série temporal selecionada
test_stationarity(serie_temporalP2)

import pandas as pd
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
# Separação dos dados de temperatura das Bombas P1
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Criar o DataFrame para armazenar os resultados
df_results_corelacao = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Calcular a correlação entre as séries temporais
correlation = Df_Pump1['Value'].corr(Df_Pump1['Value'].shift(1))
# Calcular as métricas de erro (MAE, MSE, R^2)
y_true = Df_Pump1['Value'].iloc[1:]  # Remover o primeiro valor, pois não há valor anterior para comparar
y_pred = Df_Pump1['Value'].shift(1).iloc[1:]  # Remover o primeiro valor, pois não há valor anterior para comparar
mae = mean_absolute_error(y_true, y_pred)
mse = mean_squared_error(y_true, y_pred)
r2 = r2_score(y_true, y_pred)
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_corelacao.loc[len(df_results_corelacao)] = {'Modelo': 'Correlação', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_corelacao)

import pandas as pd
from sklearn.svm import SVR
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
#Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
#Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
df_results_SVR = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
#Definir as features (X) e o target (y)
X = Df_Pump1['Timestamp'].values.reshape(-1, 1) # Feature é o timestamp
y = Df_Pump1['Value']
#Dividir os dados em conjuntos de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
#Treinar o modelo SVR
svr_model = SVR(kernel='rbf') # Use o kernel 'rbf' para SVR
svr_model.fit(X_train, y_train)
#Fazer previsões com o modelo SVR
y_pred_svr = svr_model.predict(X_test)
#Avaliar o desempenho do modelo SVR
mae = mean_absolute_error(y_test, y_pred_svr)
mse = mean_squared_error(y_test, y_pred_svr)
r2 = r2_score(y_test, y_pred_svr)
#Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_SVR.loc[len(df_results_SVR)] = {'Modelo': 'SVR', 'MAE': mae, 'MSE': mse, 'R2': r2}
#Exibir o DataFrame df_results
print(df_results_SVR)

import pandas as pd
from statsmodels.tsa.arima.model import ARIMA
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)

# Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
df_results_ARIMA = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Definir os dados de treinamento e teste
train_size = int(len(Df_Pump1) * 0.8)  # 80% dos dados para treinamento
train_data = Df_Pump1['Value'].iloc[:train_size]
test_data = Df_Pump1['Value'].iloc[train_size:]
# Ajustar o modelo ARIMA aos dados de treinamento
order = (5, 1, 0)  # Parâmetros p, d e q do ARIMA (ajuste conforme necessário)
model = ARIMA(train_data, order=order)
arima_model = model.fit()
# Fazer previsões com o modelo ajustado
start_index = len(train_data)
end_index = start_index + len(test_data) - 1
predictions = arima_model.predict(start=start_index, end=end_index, typ='levels')
# Calcular as métricas de erro (MAE, MSE, R^2)
mae = mean_absolute_error(test_data, predictions)
mse = mean_squared_error(test_data, predictions)
r2 = r2_score(test_data, predictions)
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_ARIMA.loc[len(df_results_ARIMA)] = {'Modelo': 'ARIMA', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_ARIMA)

import pandas as pd
import numpy as np
import statsmodels.api as sm
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)

# Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Inicializar o DataFrame para armazenar os resultados
df_results_ModelAR = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Ajustar o modelo AR aos dados de temperatura
lags = 1  # Especificando o número de lags
X = Df_Pump1['Value'].shift(lags).dropna()  # Variável de entrada (com lag)
y = Df_Pump1['Value'][lags:]  # Variável de saída (sem lag)
# Dividir os dados em conjuntos de treinamento e teste
split_index = int(len(X) * 0.8)  # 80% dos dados para treinamento
X_train, X_test = X[:split_index], X[split_index:]
y_train, y_test = y[:split_index], y[split_index:]
# Ajustar o modelo AR aos dados de treinamento
model = sm.OLS(y_train, sm.add_constant(X_train))
ar_model = model.fit()
# Fazer previsões com o modelo ajustado
predictions = ar_model.predict(sm.add_constant(X_test))
# Calcular as métricas de erro (MAE, MSE, R^2)
mae = mean_absolute_error(y_test, predictions)
mse = mean_squared_error(y_test, predictions)
r2 = r2_score(y_test, predictions)
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_ModelAR.loc[len(df_results_ModelAR)] = {'Modelo': 'Model AR', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_ModelAR)


import pandas as pd
import numpy as np
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
# Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Definir o tamanho da janela da Média Móvel
window_size = 7  # Por exemplo, usar uma janela de 7 dias
# Calcular a Média Móvel
Df_Pump1['Moving_Average'] = Df_Pump1['Value'].rolling(window=window_size).mean()
# Inicializar o DataFrame para armazenar os resultados
df_results_MediaMovel = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Remover os valores nulos resultantes da Média Móvel
Df_Pump1.dropna(inplace=True)
# Calcular as métricas de erro (MAE, MSE, R²)
mae = mean_absolute_error(Df_Pump1['Value'], Df_Pump1['Moving_Average'])
mse = mean_squared_error(Df_Pump1['Value'], Df_Pump1['Moving_Average'])
r2 = r2_score(Df_Pump1['Value'], Df_Pump1['Moving_Average'])
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_MediaMovel.loc[len(df_results_MediaMovel)] = {'Modelo': 'Media Movel', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_MediaMovel)


import numpy as np
import pandas as pd
import tensorflow as tf
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import LSTM, Dense
from sklearn.metrics import mean_absolute_error, r2_score, mean_squared_error
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler
import logging
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
# Configurar TensorFlow para ignorar avisos
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'
tf.get_logger().setLevel(logging.ERROR)

# Configurar logging para absl
logging.getLogger('tensorflow').setLevel(logging.ERROR)

# Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Inicializar o DataFrame para armazenar os resultados
df_results_RNNLSTM = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Normalizar os dados
scaler = MinMaxScaler()
Df_Pump1['Value'] = scaler.fit_transform(Df_Pump1[['Value']])
# Função para preparar os dados em sequências para RNN
def create_sequences(data, seq_length):
    X, y = [], []
    for i in range(len(data) - seq_length):
        X.append(data[i:i+seq_length])
        y.append(data[i+seq_length])
    return np.array(X), np.array(y)
# Definir o comprimento da sequência (número de passos de tempo)
seq_length = 10
# Criar sequências de dados
X, y = create_sequences(Df_Pump1['Value'].values, seq_length)
# Dividir os dados em conjuntos de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
# Construir o modelo RNN
model = Sequential([
    LSTM(units=15, input_shape=(X_train.shape[1], 1)),
    Dense(1)
])
# Compilar o modelo
model.compile(optimizer='adam', loss='mean_squared_error')
# Treinar o modelo
model.fit(X_train, y_train, epochs=25, batch_size=32, verbose=1)
# Fazer previsões
predictions = model.predict(X_test)
# Calcular as métricas de erro
mae = mean_absolute_error(y_test, predictions)
mse = mean_squared_error(y_test, predictions)
r2 = r2_score(y_test, predictions)
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_RNNLSTM.loc[len(df_results_RNNLSTM)] = {'Modelo': 'RNN-LSTM', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_RNNLSTM)


import numpy as np
import pandas as pd
import tensorflow as tf
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import GRU, Dense
from sklearn.metrics import mean_absolute_error, r2_score, mean_squared_error
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler
import logging
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
# Configurar TensorFlow para ignorar avisos
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'
tf.get_logger().setLevel(logging.ERROR)

# Configurar logging para absl
logging.getLogger('tensorflow').setLevel(logging.ERROR)
# Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Inicializar o DataFrame para armazenar os resultados
df_results_RNNGRU = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Normalizar os dados
scaler = MinMaxScaler()
Df_Pump1['Value'] = scaler.fit_transform(Df_Pump1[['Value']])
# Função para preparar os dados em sequências para GRU
def create_sequences(data, seq_length):
    X, y = [], []
    for i in range(len(data) - seq_length):
        X.append(data[i:i+seq_length])
        y.append(data[i+seq_length])
    return np.array(X), np.array(y)
# Definir o comprimento da sequência (número de passos de tempo)
seq_length = 10
# Criar sequências de dados
X, y = create_sequences(Df_Pump1['Value'].values, seq_length)
# Dividir os dados em conjuntos de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
# Construir o modelo GRU
model = Sequential([
    GRU(units=15, input_shape=(X_train.shape[1], 1)),
    Dense(1)
])

# Compilar o modelo
model.compile(optimizer='adam', loss='mean_squared_error')
# Treinar o modelo
model.fit(X_train, y_train, epochs=25, batch_size=32, verbose=1)
# Fazer previsões
predictions = model.predict(X_test)
# Calcular as métricas de erro
mae = mean_absolute_error(y_test, predictions)
mse = mean_squared_error(y_test, predictions)
r2 = r2_score(y_test, predictions)
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_RNNGRU.loc[len(df_results_RNNGRU)] = {'Modelo': 'RNN-GRU', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_RNNGRU)



import pandas as pd
import numpy as np
import statsmodels.api as sm
from statsmodels.tsa.holtwinters import ExponentialSmoothing
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
import logging
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
# Configurar TensorFlow para ignorar avisos
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'
tf.get_logger().setLevel(logging.ERROR)

# Configurar logging para absl
logging.getLogger('tensorflow').setLevel(logging.ERROR)
# Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Inicializar o DataFrame para armazenar os resultados
df_results_ExponentialSmoothing = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Ajustar o modelo de suavização exponencial aos dados de temperatura
model = ExponentialSmoothing(Df_Pump1['Value'])
exp_smoothing_model = model.fit()
# Fazer previsões com o modelo ajustado
predictions = exp_smoothing_model.predict(start=len(Df_Pump1), end=len(Df_Pump1) + len(X_test) - 1)
# Calcular as métricas de erro (MAE, MSE, R^2)
mae = mean_absolute_error(y_test, predictions)
mse = mean_squared_error(y_test, predictions)
r2 = r2_score(y_test, predictions)
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_ExponentialSmoothing.loc[len(df_results_ExponentialSmoothing)] = {'Modelo': 'Exponential Smoothing', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_ExponentialSmoothing)



import pandas as pd
import numpy as np
import statsmodels.api as sm
from statsmodels.tsa.statespace.sarimax import SARIMAX
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
import logging
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
# Configurar TensorFlow para ignorar avisos
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'
tf.get_logger().setLevel(logging.ERROR)

# Configurar logging para absl
logging.getLogger('tensorflow').setLevel(logging.ERROR)
# Separação dos dados de temperatura das Bombas P1 e P2
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Inicializar o DataFrame para armazenar os resultados
df_results_SARIMAX = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Ajustar o modelo SARIMAX aos dados de temperatura
order = (1, 0, 1)  # Ordem do modelo SARIMA (p, d, q)
seasonal_order = (1, 1, 1, 12)  # Ordem sazonal do modelo SARIMA (P, D, Q, S)
model = SARIMAX(Df_Pump1['Value'], order=order, seasonal_order=seasonal_order)
sarimax_model = model.fit()
# Fazer previsões com o modelo ajustado
predictions = sarimax_model.predict(start=len(Df_Pump1), end=len(Df_Pump1) + len(X_test) - 1)
# Calcular as métricas de erro (MAE, MSE, R^2)
mae = mean_absolute_error(y_test, predictions)
mse = mean_squared_error(y_test, predictions)
r2 = r2_score(y_test, predictions)
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_SARIMAX.loc[len(df_results_SARIMAX)] = {'Modelo': 'SARIMAX', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_SARIMAX)


import pandas as pd
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
import logging
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
# Configurar TensorFlow para ignorar avisos
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'
tf.get_logger().setLevel(logging.ERROR)

# Configurar logging para absl
logging.getLogger('tensorflow').setLevel(logging.ERROR)
# Separação dos dados de temperatura das Bombas P1
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Converter a coluna 'Timestamp' para um formato numérico (por exemplo, número de dias desde o início da época)
Df_Pump1['NumericTimestamp'] = Df_Pump1['Timestamp'].astype('int64') / 10**9 / 86400  # Converter nanossegundos para dias
# Definir as features (X) e o target (y)
X = Df_Pump1[['NumericTimestamp']]  # Feature é o timestamp numérico
y = Df_Pump1['Value']
# Dividir os dados em conjuntos de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
# Ajustar o modelo de regressão linear aos dados de treinamento
model = LinearRegression()
model.fit(X_train, y_train)
# Fazer previsões com o modelo ajustado
y_pred = model.predict(X_test)
# Calcular as métricas de erro (MAE, MSE, R^2)
mae = mean_absolute_error(y_test, y_pred)
mse = mean_squared_error(y_test, y_pred)
r2 = r2_score(y_test, y_pred)
# Criar o DataFrame para armazenar os resultados
df_results_RLM = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_RLM.loc[len(df_results_RLM)] = {'Modelo': 'Regressão Linear Múltipla', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_RLM)



import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split, RandomizedSearchCV
from sklearn.preprocessing import StandardScaler
from sklearn.svm import SVR
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
from scipy.stats import uniform
import logging
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
# Configurar TensorFlow para ignorar avisos
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'
tf.get_logger().setLevel(logging.ERROR)

# Configurar logging para absl
logging.getLogger('tensorflow').setLevel(logging.ERROR)
# Criar o DataFrame para armazenar os resultados
df_results_SVR_Ajus = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Separação dos dados de temperatura das Bombas P1
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Definir o número de valores anteriores como 10% do volume de dados originais para projeção
n_prev_values = int(0.10 * len(Df_Pump1))
# Criar features e target usando os últimos 10% dos dados
X = []
y = []
for i in range(n_prev_values, len(Df_Pump1)):
    X.append(Df_Pump1['Value'].values[i - n_prev_values:i])
    y.append(Df_Pump1['Value'].values[i])
X = np.array(X)
y = np.array(y)
# Dividir os dados em conjuntos de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
# Normalizar os dados
scaler = StandardScaler()
X_train = scaler.fit_transform(X_train)
X_test = scaler.transform(X_test)
# Definir o modelo SVR
svr = SVR()
# Definir a grade de parâmetros para RandomizedSearchCV
param_dist = {
    'C': uniform(0.1, 10),  # Ajuste a distribuição de C
    'epsilon': uniform(0.01, 1),  # Ajuste a distribuição de epsilon
    'kernel': ['linear', 'poly', 'rbf']
}
# Utilizar RandomizedSearchCV para encontrar os melhores parâmetros
random_search = RandomizedSearchCV(svr, param_distributions=param_dist, n_iter=50, cv=5, scoring='neg_mean_absolute_error', n_jobs=-1, random_state=42)
random_search.fit(X_train, y_train)
# Melhor modelo
best_svr = random_search.best_estimator_
# Fazer previsões com o melhor modelo
y_pred = best_svr.predict(X_test)
# Calcular as métricas de erro
mae = mean_absolute_error(y_test, y_pred)
mse = mean_squared_error(y_test, y_pred)
r2 = r2_score(y_test, y_pred)
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_SVR_Ajus.loc[len(df_results_SVR_Ajus)] = {'Modelo': 'SVR_1', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_SVR_Ajus)
print(f"Melhores Parâmetros: {random_search.best_params_}")
print(f"MAE: {mae}")
print(f"MSE: {mse}")
print(f"R2: {r2}")



import pandas as pd
import numpy as np
import statsmodels.api as sm
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
from sklearn.model_selection import train_test_split
import logging
import warnings

# Suprimir avisos específicos
warnings.simplefilter(action='ignore', category=pd.errors.PerformanceWarning)
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)
warnings.filterwarnings("ignore")
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
# Configurar TensorFlow para ignorar avisos
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'
tf.get_logger().setLevel(logging.ERROR)

# Configurar logging para absl
logging.getLogger('tensorflow').setLevel(logging.ERROR)

# Separação dos dados de temperatura das Bombas P1
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Inicializar o DataFrame para armazenar os resultados
df_results_StateSpaceModel = pd.DataFrame(columns=['Modelo', 'MAE', 'MSE', 'R2'])
# Dividindo os dados em treinamento e teste
train_data, test_data = train_test_split(Df_Pump1, test_size=0.2, shuffle=False)
# Ajustando o modelo State Space Model (SSM)
model = sm.tsa.UnobservedComponents(train_data['Value'], 'local linear trend')
results = model.fit()
# Fazendo previsões
predictions = results.forecast(steps=len(test_data))
# Calculando as métricas de erro
mae = mean_absolute_error(test_data['Value'], predictions)
mse = mean_squared_error(test_data['Value'], predictions)
r2 = r2_score(test_data['Value'], predictions)
# Adicionar as métricas de erro ao DataFrame df_results_corelacao
df_results_StateSpaceModel.loc[len(df_results_StateSpaceModel)] = {'Modelo': 'State Space Model', 'MAE': mae, 'MSE': mse, 'R2': r2}
# Exibir o DataFrame df_results
print(df_results_StateSpaceModel)


A definição pela técnica de AST&P (Advanced Statistical Techniques & Procedures) para análise de dados e tomada de decisão foram feitos utilizando técnicas estatísticas clássicas e avançadas. Dentre estes, o modelo mais aderente para trabalhar com séries temporais lineares, depende de vários fatores, incluindo a estrutura dos dados, a quantidade de dados disponíveis, a presença de tendências ou sazonalidades, entre outros, contudo os modelos que foram testados para avaliar os resultados nessa série temporal de temperatura foram:

•	Regressão Linear Simples ou Múltipla: A regressão linear é um modelo simples que pode ser eficaz se houver uma relação linear direta entre as variáveis de entrada e saída.

•	Modelos Autoregressivos (AR): Modelos autorregressivos consideram a relação entre uma observação atual e observações passadas. Eles são úteis quando há dependência temporal nas séries temporais.

•	Médias Móveis (MA): Modelos de médias móveis consideram a relação entre uma observação e um erro residual das observações passadas. Eles podem ser combinados com modelos AR para formar modelos ARMA.

•	Modelos ARIMA (Autoregressive Integrated Moving Average): Modelos ARIMA combinam componentes de regressão autorregressiva, médias móveis e diferenciação para modelar séries temporais estacionárias ou com tendências conhecidas.

•	Suavização Exponencial (Exponential Smoothing): Modelos recomendados para suavizar séries temporais e capturar padrões sazonais.

•	Redes Neurais Recorrentes (RNNs): Modelos de redes neurais recorrentes, como LSTM e GRU, são eficazes para capturar dependências de longo prazo em séries temporais.

•	State Space Models: Modelos recomendados para modelar séries temporais que podem ser decompostas em estados latentes.

Com base nos resultados obtidos tanto no teste de Dickey-Fuller quanto nos resultados de MAE, MSE e R2, como apresentado na Figuras 24, com os resultados consolidados dos modelos, e possível identificar quais os modelos apresentam maior aderência aos dados coletados.

![Figuras 24. Resumo dados temperatura Bomba 1. Fonte: Próprio Autor](G:/RNN%20Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/rnn-component-lIfe-cycle-main/VsCode/Figuras%2024.%20Resumo%20dados%20temperatura%20Bomba%201.png)

As métricas de desempenho para os diferentes modelos de previsão de séries temporais aplicados aos dados de temperatura das bombas P1, foram avaliados em termos de três métricas:
- MAE (Mean Absolute Error): Erro absoluto médio, que mede a média dos erros absolutos entre os valores previstos e os valores reais. Valores menores indicam melhor desempenho.
- MSE (Mean Squared Error): Erro quadrático médio, que mede a média dos quadrados dos erros entre os valores previstos e os valores reais. Valores menores indicam melhor desempenho.
- R² (Coeficiente de Determinação): Mede a proporção da variação dos dados que é explicada pelo modelo. Valores próximos de 1 indicam um modelo que explica bem a variação dos dados, enquanto valores negativos indicam um modelo que está performando pior do que uma simples média.

State Space Model
- MAE: 1294.020169, MSE: 2.247582e+06, R²: -4729.475731
*Análise:* Este modelo tem um desempenho extremamente ruim. O MAE é muito alto, indicando previsões imprecisas. O MSE também é extremamente alto, e o R² negativo indica que o modelo está performando muito pior do que a média.

SARIMAX
- MAE: 13.243707, MSE: 2.736540e+02, R²: -0.012671
*Análise:* O modelo SARIMAX também não performa bem, com um R² ligeiramente negativo e um MAE e MSE altos, indicando que não é um bom modelo para esses dados.

RNN-GRU
- MAE: 0.028991, MSE: 2.431490e-03, R²: 0.948623
*Análise:* O modelo RNN-GRU apresenta um excelente desempenho, com um MAE muito baixo, um MSE extremamente baixos e um R² muito próximo de 1, indicando que o modelo explica bem a variação dos dados.

RNN-LSTM
- MAE: 0.026283, MSE: 2.256681e-03, R²: 0.952317
*Análise:* O modelo RNN-LSTM também apresenta um desempenho excelente, similar ao GRU, com um MAE, MSE e R² muito bons.
Regressão Linear Múltipla
- MAE: 12.297906, MSE: 2.145145e+02, R²: 0.206178
*Análise:* Este modelo tem um desempenho mediano, com um MAE e MSE relativamente altos e um R² baixo, indicando que não explica bem a variação dos dados.

Média Móvel
- MAE: 2.440817, MSE: 1.502500e+01, R²: 0.945099
*Análise:* A técnica de média móvel tem um bom desempenho, com um MAE razoavelmente baixo, um MSE baixo e um R² alto.

Modelo AR
- MAE: 5.576465, MSE: 8.251220e+01, R²: 0.826393
*Análise:* O modelo AR (Autorregressivo) tem um desempenho decente, com um MAE e MSE moderados e um R² relativamente alto.

ARIMA
- MAE: 22.282574, MSE: 6.968059e+02, R²: -0.466564
*Análise:* O modelo ARIMA não performa bem, com um MAE e MSE altos e um R² negativo, indicando desempenho ruim.

SVR
- MAE: 9.104204, MSE: 1.485951e+02, R²: 0.450116
*Análise:* O modelo SVR tem um desempenho razoável, com um MAE e MSE moderados e um R² relativamente baixo.

SVR_Ajustado
- MAE: 1.866355, MSE: 1.356212e+01, R²: 0.943082
*Análise:* O modelo SVR_Ajustado apresenta um desempenho muito bom, com um MAE baixo, um MSE baixo e um R² alto.

Exponential Smoothing
- MAE: 16.322945, MSE: 4.441108e+02, R²: -0.643456
*Análise:* O modelo de suavização exponencial não performa bem, com um MAE e MSE altos e um R² negativo.

Correlação
- MAE: 1.827380, MSE: 1.808035e+01, R²: 0.933978
*Análise:* A técnica de correlação apresenta um bom desempenho, com um MAE baixo, um MSE relativamente baixo e um R² alto.

import pandas as pd

# Suponha que você tenha os DataFrames contendo os resultados de diferentes modelos
df_results = pd.concat([df_results_StateSpaceModel,
                        df_results_SARIMAX,
                        df_results_RNNGRU,
                        df_results_RNNLSTM,
                        df_results_RLM,
                        df_results_MediaMovel,
                        df_results_ModelAR,
                        df_results_ARIMA,
                        df_results_SVR,
                        df_results_SVR_Ajus,
                        df_results_ExponentialSmoothing,
                        df_results_corelacao], ignore_index=True)
# Exibir o DataFrame resultante
print(df_results)
df_results.head(10)

Neste caso, os modelos de RNN-GRU e RNN-LSTM obtiveram resultados bem mais aderentes ao modelo, com os menores MAE e MSE e os R² mais altos. Alinhado a isso, também o modelo SVR_Ajustado com Randomized Search CV também apresentou bom desempenho e foram definidos como sendo os métodos para projeção dos dados.

Esta projeção tem como objetivo fundamental, a identificação de quando os valores de temperatura podem atingir o limite de temperatura que indique uma falha potencial, conforme pode ser visto na Figuras 25 e Figuras 26.

import pandas as pd
import numpy as np
import plotly.graph_objects as go
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error

# Separação dos dados de temperatura das Bombas P1
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Definir o número de valores anteriores como 20% do volume de dados originais para cálculo da média histórica
n_prev_values_20 = int(0.10 * len(Df_Pump1))
# Calcular a média histórica dos últimos 20% dos dados
historical_mean = Df_Pump1['Value'].iloc[-n_prev_values_20:].mean()
upper_limit_value = historical_mean * 1.28
# Definir o número de valores anteriores como 10% do volume de dados originais para projeção
n_prev_values_10 = int(0.20 * len(Df_Pump1))
# Criar features e target usando os últimos 10% dos dados
X = []
y = []
for i in range(n_prev_values_10, len(Df_Pump1)):
    X.append(Df_Pump1['Value'].values[i - n_prev_values_10:i])
    y.append(Df_Pump1['Value'].values[i])

X = np.array(X)
y = np.array(y)
# Dividir os dados em conjuntos de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
# Treinar o modelo LinearRegression
linear_model = LinearRegression()
linear_model.fit(X_train, y_train)
# Fazer previsões no conjunto de teste
y_pred_test = linear_model.predict(X_test)
# Calcular os resíduos
residuos = y_test - y_pred_test
# Criar um DataFrame para armazenar os resíduos
df_residuosSVM = pd.DataFrame({'y_true': y_test, 'y_pred': y_pred_test, 'residuos': residuos})
# Fazer previsões para o período futuro
n_days_future = 100
# Criar um range contínuo de datas para previsão
future_dates = pd.date_range(start=Df_Pump1['Timestamp'].iloc[-1] + pd.Timedelta(seconds=1), periods=n_days_future, freq='D')
last_values = X[-1]  # Últimos valores conhecidos
future_values = []
for _ in range(n_days_future):
    # Fazer previsão para o próximo dia
    next_value = linear_model.predict([last_values])[0]
    future_values.append(next_value)

    # Atualizar os últimos valores conhecidos para incluir a nova previsão
    last_values = np.roll(last_values, -1)
    last_values[-1] = next_value
# Calcular os limites mínimo e máximo para o intervalo de confiança
std_residuals = np.std(y_test - y_pred_test)  # Desvio padrão dos resíduos
z_critical = 1.96  # Para intervalo de confiança de 95%
lower_bound = np.array(future_values) - z_critical * std_residuals
upper_bound = np.array(future_values) + z_critical * std_residuals
# Criar DataFrame com as previsões
df_future = pd.DataFrame({'Timestamp': future_dates, 'Value': future_values, 'Lower_Bound': lower_bound, 'Upper_Bound': upper_bound})
# Criar o gráfico interativo com Plotly
fig = go.Figure()
# Adicionar os dados originais
fig.add_trace(go.Scatter(x=Df_Pump1['Timestamp'], y=Df_Pump1['Value'], mode='lines', name='Dados Originais'))
# Adicionar a linha de limite superior (25% acima da média histórica dos últimos 20% dos dados)
fig.add_trace(go.Scatter(x=Df_Pump1['Timestamp'], y=[upper_limit_value]*len(Df_Pump1), mode='lines', line=dict(color='red', dash='dash'), name='Limite Superior Histórico'))
# Adicionar a projeção e o intervalo de confiança
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=df_future['Value'], mode='lines', name='Projeção'))
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=df_future['Lower_Bound'], mode='lines', line=dict(width=0), marker=dict(color="#444"), name='Limite Inferior'))
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=df_future['Upper_Bound'], mode='lines', line=dict(width=0), marker=dict(color="#444"), fillcolor='rgba(68, 68, 68, 0.3)', fill='tonexty', name='Limite Superior'))
# Adicionar a linha de limite superior também na projeção
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=[upper_limit_value]*len(df_future), mode='lines', line=dict(color='red', dash='dash'), name='Limite Superior Histórico Projeção'))
# Personalizar o layout, incluindo o tamanho da fonte
fig.update_layout(
    title={
        'text': 'Projeção de Temperatura com Regressão Linear e Intervalo de Confiança',
        'font': {'size': 24}
    },
    xaxis_title={
        'text': 'Timestamp',
        'font': {'size': 20}
    },
    yaxis_title={
        'text': 'Value',
        'font': {'size': 20}
    },
    hovermode='x',
    template='plotly_white',
    font=dict(size=16)  # Aumentar o tamanho da fonte para outros elementos
)
fig.show()
# Mostrar os resíduos
print(df_residuosSVM.head())


import warnings
import pandas as pd
import numpy as np
import plotly.graph_objects as go
from sklearn.model_selection import train_test_split
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import LSTM, Dense, Dropout
from tensorflow.keras.regularizers import l1, l2
from sklearn.metrics import mean_squared_error
import logging
import os

# Suprimir avisos
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)

# Configurar TensorFlow para ignorar mensagens de log menos importantes
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'
tf.get_logger().setLevel(logging.ERROR)
logging.getLogger('tensorflow').setLevel(logging.ERROR)

# Separação dos dados de temperatura das Bombas P1
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']

# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])

# Definir o número de valores anteriores como 20% do volume de dados originais para cálculo da média histórica
n_prev_values_20 = int(0.10 * len(Df_Pump1))

# Calcular a média histórica dos últimos 20% dos dados
historical_mean = Df_Pump1['Value'].iloc[-n_prev_values_20:].mean()
upper_limit_value = historical_mean * 1.28

# Definir o número de valores anteriores como 10% do volume de dados originais para projeção
n_prev_values_10 = int(0.75 * len(Df_Pump1))

# Criar features e target usando os últimos 10% dos dados
X = []
y = []
for i in range(n_prev_values_10, len(Df_Pump1)):
    X.append(Df_Pump1['Value'].values[i - n_prev_values_10:i])
    y.append(Df_Pump1['Value'].values[i])
X = np.array(X)
y = np.array(y)

# Expandir as dimensões de X para ser compatível com LSTM (número de amostras, passos de tempo, número de features)
X = np.expand_dims(X, axis=-1)

# Dividir os dados em conjuntos de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Criar o modelo LSTM com L1, L2 e Dropout
model = Sequential()
model.add(LSTM(100, activation='tanh', input_shape=(X_train.shape[1], X_train.shape[2]),
               kernel_regularizer=l1(0.01), recurrent_regularizer=l2(0.01), bias_regularizer=l2(0.01)))
model.add(Dropout(0.2))
model.add(Dense(1))

# Compilar o modelo
model.compile(optimizer='adam', loss='mse')

# Treinar o modelo
model.fit(X_train, y_train, epochs=25, batch_size=32, validation_data=(X_test, y_test))

# Fazer previsões no conjunto de teste
y_pred_test = model.predict(X_test)

# Calcular os resíduos
residuos = y_test - y_pred_test.flatten()

# Criar um DataFrame para armazenar os resíduos
df_residuosLSTM = pd.DataFrame({'y_true': y_test, 'y_pred': y_pred_test.flatten(), 'residuos': residuos})

# Fazer previsões para os próximos 10 passos de tempo
n_days_future = 100
last_sequence = X[-1]  # Última sequência conhecida nos últimos 10% dos dados
future_values = []
for _ in range(n_days_future):
    # Prever o próximo valor
    next_value = model.predict(np.expand_dims(last_sequence, axis=0))[0, 0]
    future_values.append(next_value)

    # Atualizar a sequência conhecida para incluir a nova previsão
    last_sequence = np.roll(last_sequence, -1)
    last_sequence[-1, 0] = next_value

# Criar datas futuras para plotagem
future_dates = pd.date_range(start=Df_Pump1['Timestamp'].iloc[-1] + pd.Timedelta(seconds=1), periods=n_days_future, freq='D')

# Criar DataFrame com as previsões
df_future = pd.DataFrame({'Timestamp': future_dates, 'Value': future_values})

# Criar o gráfico interativo com Plotly
fig = go.Figure()

# Adicionar os dados originais
fig.add_trace(go.Scatter(x=Df_Pump1['Timestamp'], y=Df_Pump1['Value'], mode='lines', name='Dados Originais'))

# Adicionar a linha de limite superior (25% acima da média histórica dos últimos 20% dos dados)
fig.add_trace(go.Scatter(x=Df_Pump1['Timestamp'], y=[upper_limit_value]*len(Df_Pump1), mode='lines', line=dict(color='red', dash='dash'), name='Limite Superior Histórico'))

# Adicionar a projeção
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=df_future['Value'], mode='lines', name='Projeção'))

# Adicionar a linha de limite superior também na projeção
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=[upper_limit_value]*len(df_future), mode='lines', line=dict(color='red', dash='dash'), name='Limite Superior Histórico Projeção'))

# Personalizar o layout, incluindo o tamanho da fonte
fig.update_layout(
    title={
        'text': 'Projeção de Temperatura com LSTM e Intervalo de Confiança',
        'font': {'size': 24}
    },
    xaxis_title={
        'text': 'Timestamp',
        'font': {'size': 20}
    },
    yaxis_title={
        'text': 'Value',
        'font': {'size': 20}
    },
    hovermode='x',
    template='plotly_white',
    font=dict(size=16)  # Aumentar o tamanho da fonte para outros elementos
)

fig.show()

# Mostrar os resíduos
print(df_residuosLSTM.head())


import pandas as pd
import numpy as np
import plotly.graph_objects as go
from sklearn.model_selection import train_test_split
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import GRU, Dense, Dropout
from tensorflow.keras.regularizers import l1, l2
from sklearn.metrics import mean_squared_error

# Separação dos dados de temperatura das Bombas P1
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']
# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])
# Definir o número de valores anteriores como 10% do volume de dados originais para cálculo da média histórica
n_prev_values_20 = int(0.10 * len(Df_Pump1))
# Calcular a média histórica dos últimos 20% dos dados
historical_mean = Df_Pump1['Value'].iloc[-n_prev_values_20:].mean()
upper_limit_value = historical_mean * 1.28
# Definir o número de valores anteriores como 50% do volume de dados originais para projeção
n_prev_values_10 = int(0.50 * len(Df_Pump1))
# Criar features e target usando os últimos 10% dos dados
X = []
y = []
for i in range(n_prev_values_10, len(Df_Pump1)):
    X.append(Df_Pump1['Value'].values[i - n_prev_values_10:i])
    y.append(Df_Pump1['Value'].values[i])
X = np.array(X)
y = np.array(y)
# Expandir as dimensões de X para ser compatível com GRU (número de amostras, passos de tempo, número de features)
X = np.expand_dims(X, axis=-1)
# Dividir os dados em conjuntos de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
# Criar o modelo GRU com L1, L2 e Dropout
model = Sequential()
model.add(GRU(100, activation='tanh', input_shape=(X_train.shape[1], X_train.shape[2]),
              kernel_regularizer=l1(0.01), recurrent_regularizer=l2(0.01), bias_regularizer=l2(0.01)))
model.add(Dropout(0.2))
model.add(Dense(1))
# Compilar o modelo
model.compile(optimizer='adam', loss='mse')
# Treinar o modelo
model.fit(X_train, y_train, epochs=25, batch_size=32, validation_data=(X_test, y_test))
# Fazer previsões no conjunto de teste
y_pred_test = model.predict(X_test)
# Calcular os resíduos
residuos = y_test - y_pred_test.flatten()
# Criar um DataFrame para armazenar os resíduos
df_residuosGRU = pd.DataFrame({'y_true': y_test, 'y_pred': y_pred_test.flatten(), 'residuos': residuos})
# Fazer previsões para os próximos 100 passos de tempo
n_days_future = 100
last_sequence = X[-1]  # Última sequência conhecida nos últimos 10% dos dados
future_values = []
for _ in range(n_days_future):
    # Prever o próximo valor
    next_value = model.predict(np.expand_dims(last_sequence, axis=0))[0, 0]
    future_values.append(next_value)

    # Atualizar a sequência conhecida para incluir a nova previsão
    last_sequence = np.roll(last_sequence, -1)
    last_sequence[-1, 0] = next_value
# Criar datas futuras para plotagem
future_dates = pd.date_range(start=Df_Pump1['Timestamp'].iloc[-1] + pd.Timedelta(seconds=1), periods=n_days_future, freq='D')
# Criar DataFrame com as previsões
df_future = pd.DataFrame({'Timestamp': future_dates, 'Value': future_values})
# Criar o gráfico interativo com Plotly
fig = go.Figure()
# Adicionar os dados originais
fig.add_trace(go.Scatter(x=Df_Pump1['Timestamp'], y=Df_Pump1['Value'], mode='lines', name='Dados Originais'))
# Adicionar a linha de limite superior (25% acima da média histórica dos últimos 20% dos dados)
fig.add_trace(go.Scatter(x=Df_Pump1['Timestamp'], y=[upper_limit_value]*len(Df_Pump1), mode='lines', line=dict(color='red', dash='dash'), name='Limite Superior Histórico'))
# Adicionar a projeção
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=df_future['Value'], mode='lines', name='Projeção'))
# Adicionar a linha de limite superior também na projeção
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=[upper_limit_value]*len(df_future), mode='lines', line=dict(color='red', dash='dash'), name='Limite Superior Histórico Projeção'))
# Personalizar o layout, incluindo o tamanho da fonte
fig.update_layout(
    title={
        'text': 'Projeção de Temperatura com GRU e Intervalo de Confiança',
        'font': {'size': 24}
    },
    xaxis_title={
        'text': 'Timestamp',
        'font': {'size': 20}
    },
    yaxis_title={
        'text': 'Value',
        'font': {'size': 20}
    },
    hovermode='x',
    template='plotly_white',
    font=dict(size=16)  # Aumentar o tamanho da fonte para outros elementos
)
fig.show()
# Mostrr os resíduos
print(df_residuosGRU.head())



import pandas as pd
from github import Github
from io import BytesIO

# Defina suas credenciais do GitHub
seu_token = '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'
seu_usuario = 'CidClayQuirino'
seu_repositorio = 'rnn-component-lIfe-cycle'
# Dicionário de DataFrames com seus nomes originais
dataframes = {
    'df_MainPumpsTemp': df_MainPumpsTemp,
    'df_MainPumps': df_MainPumps,
    'df_results': df_results,
    'BDadosTemp':BDadosTemp,
    'df_residuosGRU':df_residuosGRU,
    'df_residuosSVM':df_residuosSVM,
    'df_residuosLSTM':df_residuosLSTM, 
    'df_residuosGRU': df_residuosGRU,
    'df_residuosLSTM':df_residuosLSTM,
    'df_residuosSVM': df_residuosSVM,
 }

# Função para salvar e enviar para o GitHub
def salvar_e_enviar_para_github(dataframe, nome_arquivo, usuario, repositorio, token):
    # Salvar DataFrame como CSV em um BytesIO
    csv_bytes = BytesIO()
    dataframe.to_csv(csv_bytes, index=False)

    # Autenticar no GitHub
    g = Github(token)

    # Obter o repositório
    repo = g.get_user(usuario).get_repo(repositorio)

    # Criar ou atualizar o arquivo no repositório
    try:
        arquivo = repo.get_contents(nome_arquivo)
        repo.update_file(nome_arquivo, f'Atualizando {nome_arquivo}', csv_bytes.getvalue(), arquivo.sha)
        print(f'{nome_arquivo} atualizado com sucesso!')
    except Exception as e:
        repo.create_file(nome_arquivo, f'Adicionando {nome_arquivo}', csv_bytes.getvalue())
        print(f'{nome_arquivo} criado com sucesso!')

# Iterar sobre os DataFrames e salvá-los no GitHub
for nome, df in dataframes.items():
    nome_arquivo = f'{nome}.csv'  # Nome do arquivo usando o nome original do DataFrame
    salvar_e_enviar_para_github(df, nome_arquivo, seu_usuario, seu_repositorio, seu_token)


Análise de Resíduos pelo teste de Shapiro-Wilk (shapiro()) a fim de verificar:
 - Média dos Resíduos
 - Dispersão dos Resíduos
 - Resíduos Extremos
 - Quartis

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy.stats import shapiro

# Carregar os dados
#df_residuosGRU = pd.read_csv('df_residuosGRU.csv')
#df_residuosSVM = pd.read_csv('df_residuosSVM.csv')
#df_residuosLSTM = pd.read_csv('df_residuosLSTM.csv')

# Função para realizar o teste de Shapiro-Wilk e exibir o resultado
def shapiro_test(residuos, model_name):
    stat, p_value = shapiro(residuos)
    print(f'Teste de Shapiro-Wilk para {model_name}:')
    print(f'Estatística={stat}, p-valor={p_value}\n')
    return stat, p_value

# Realizar o teste de Shapiro-Wilk nos resíduos
stat_gru, p_gru = shapiro_test(df_residuosGRU['residuos'], 'GRU')
stat_svm, p_svm = shapiro_test(df_residuosSVM['residuos'], 'SVM')
stat_lstm, p_lstm = shapiro_test(df_residuosLSTM['residuos'], 'LSTM')

# Plotar histogramas dos resíduos
plt.figure(figsize=(18, 6))

plt.subplot(1, 3, 1)
sns.histplot(df_residuosGRU['residuos'], kde=True, color='blue')
plt.title('Histograma dos Resíduos - GRU')
plt.xlabel('Resíduos')
plt.ylabel('Frequência')

plt.subplot(1, 3, 2)
sns.histplot(df_residuosSVM['residuos'], kde=True, color='green')
plt.title('Histograma dos Resíduos - SVM')
plt.xlabel('Resíduos')
plt.ylabel('Frequência')

plt.subplot(1, 3, 3)
sns.histplot(df_residuosLSTM['residuos'], kde=True, color='red')
plt.title('Histograma dos Resíduos - LSTM')
plt.xlabel('Resíduos')
plt.ylabel('Frequência')

plt.tight_layout()
plt.show()

# Plotar gráficos de dispersão dos resíduos
plt.figure(figsize=(18, 6))

plt.subplot(1, 3, 1)
plt.scatter(range(len(df_residuosGRU)), df_residuosGRU['residuos'], color='blue')
plt.axhline(0, color='red', linestyle='--')
plt.title('Gráfico de Dispersão dos Resíduos - GRU')
plt.xlabel('Índice')
plt.ylabel('Resíduos')

plt.subplot(1, 3, 2)
plt.scatter(range(len(df_residuosSVM)), df_residuosSVM['residuos'], color='green')
plt.axhline(0, color='red', linestyle='--')
plt.title('Gráfico de Dispersão dos Resíduos - SVM')
plt.xlabel('Índice')
plt.ylabel('Resíduos')

plt.subplot(1, 3, 3)
plt.scatter(range(len(df_residuosLSTM)), df_residuosLSTM['residuos'], color='red')
plt.axhline(0, color='red', linestyle='--')
plt.title('Gráfico de Dispersão dos Resíduos - LSTM')
plt.xlabel('Índice')
plt.ylabel('Resíduos')

plt.tight_layout()
plt.show()

# Estatísticas descritivas dos resíduos
print("Estatísticas descritivas dos resíduos - GRU")
print(df_residuosGRU['residuos'].describe())
print("\nEstatísticas descritivas dos resíduos - SVM")
print(df_residuosSVM['residuos'].describe())
print("\nEstatísticas descritivas dos resíduos - LSTM")
print(df_residuosLSTM['residuos'].describe())

Os resultados apresentados no teste de Shapiro-Wilk para GRU, LSTM e SVM, 
 - Média dos Resíduos: A média dos resíduos é próxima de zero para SVM (-0.10) e LSTM (0.31), indicando que, em média, as previsões não estão muito deslocadas dos valores reais. A média dos resíduos do GRU (1.08) é ligeiramente maior, sugerindo um pequeno viés nas previsões.
 - Dispersão dos Resíduos: O desvio padrão dos resíduos é menor para o modelo LSTM (3.75), sugerindo que as previsões do LSTM são mais consistentes e têm menor variabilidade. O desvio padrão é maior para o modelo SVM (6.46), indicando maior variabilidade nas previsões.
 - Resíduos Extremos: Os resíduos mínimos e máximos são maiores para o modelo SVM, sugerindo a presença de outliers ou erros de previsão mais extremos. O GRU e LSTM têm menores extremos em comparação ao SVM, com LSTM apresentando os menores valores de resíduos extremos.
 - Quartis:Os quartis (25%, 50%, 75%) indicam a distribuição dos resíduos. O SVM tem a maior dispersão interquartil (IQR), seguido pelo GRU e LSTM.

TESTE: Incluir Tendência na Previsão: Explicitamente adicionar uma componente de tendência aos valores previstos.

Cálculo da Tendência:

Calcula a tendência usando uma regressão linear nos últimos 15% dos dados.
  -n_last_values define o número de últimos valores a serem usados para calcular a tendência.
  - reg.coef_[0] fornece o coeficiente angular da regressão linear, que é usado como a tendência.

Adição da Tendência:

No loop de previsão, next_value += trend adiciona a tendência calculada ao próximo valor previsto.
Validação da Tendência:

Imprime o valor do coeficiente angular para validação.


import warnings
import pandas as pd
import numpy as np
import plotly.graph_objects as go
from sklearn.model_selection import train_test_split
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import LSTM, Dense, Dropout
from tensorflow.keras.regularizers import l1, l2
from sklearn.metrics import mean_squared_error
import logging
import os

# Suprimir avisos
warnings.simplefilter(action='ignore', category=pd.errors.SettingWithCopyWarning)
warnings.simplefilter(action='ignore', category=FutureWarning)

# Configurar TensorFlow para ignorar mensagens de log menos importantes
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'
tf.get_logger().setLevel(logging.ERROR)
logging.getLogger('tensorflow').setLevel(logging.ERROR)

# Separação dos dados de temperatura das Bombas P1
Df_Pump1 = df_MainPumpsTemp[df_MainPumpsTemp['NmeComp'] == 'MainPumpP1']

# Converter a coluna 'Timestamp' para o tipo datetime, se necessário
Df_Pump1['Timestamp'] = pd.to_datetime(Df_Pump1['Timestamp'])

# Definir o número de valores anteriores como 20% do volume de dados originais para cálculo da média histórica
n_prev_values_20 = int(0.10 * len(Df_Pump1))

# Calcular a média histórica dos últimos 20% dos dados
historical_mean = Df_Pump1['Value'].iloc[-n_prev_values_20:].mean()
upper_limit_value = historical_mean * 1.28

# Definir o número de valores anteriores como 10% do volume de dados originais para projeção
n_prev_values_10 = int(0.25 * len(Df_Pump1))

# Criar features e target usando os últimos 10% dos dados
X = []
y = []
for i in range(n_prev_values_10, len(Df_Pump1)):
    X.append(Df_Pump1['Value'].values[i - n_prev_values_10:i])
    y.append(Df_Pump1['Value'].values[i])
X = np.array(X)
y = np.array(y)

# Expandir as dimensões de X para ser compatível com LSTM (número de amostras, passos de tempo, número de features)
X = np.expand_dims(X, axis=-1)

# Dividir os dados em conjuntos de treinamento e teste
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Criar o modelo LSTM com L1, L2 e Dropout
model = Sequential()
model.add(LSTM(100, activation='tanh', input_shape=(X_train.shape[1], X_train.shape[2]),
               kernel_regularizer=l1(0.01), recurrent_regularizer=l2(0.01), bias_regularizer=l2(0.01)))
model.add(Dropout(0.2))
model.add(Dense(1))

# Compilar o modelo
model.compile(optimizer='adam', loss='mse')

# Treinar o modelo
model.fit(X_train, y_train, epochs=25, batch_size=32, validation_data=(X_test, y_test))

# Fazer previsões no conjunto de teste
y_pred_test = model.predict(X_test)

# Fazer previsões para os próximos 100 passos de tempo
n_days_future = 100
last_sequence = X[-1]  # Última sequência conhecida nos últimos 10% dos dados
future_values = []
trend = 0.2  # Ajustar a tendência conforme necessário

for _ in range(n_days_future):
    # Prever o próximo valor
    next_value = model.predict(np.expand_dims(last_sequence, axis=0))[0, 0]
    next_value += trend  # Adicionar a tendência

    future_values.append(next_value)

    # Atualizar a sequência conhecida para incluir a nova previsão
    last_sequence = np.roll(last_sequence, -1)
    last_sequence[-1, 0] = next_value

# Criar datas futuras para plotagem
future_dates = pd.date_range(start=Df_Pump1['Timestamp'].iloc[-1] + pd.Timedelta(seconds=1), periods=n_days_future, freq='D')

# Criar DataFrame com as previsões
df_future = pd.DataFrame({'Timestamp': future_dates, 'Value': future_values})

# Criar o gráfico interativo com Plotly
fig = go.Figure()

# Adicionar os dados originais
fig.add_trace(go.Scatter(x=Df_Pump1['Timestamp'], y=Df_Pump1['Value'], mode='lines', name='Dados Originais'))

# Adicionar a linha de limite superior (25% acima da média histórica dos últimos 20% dos dados)
fig.add_trace(go.Scatter(x=Df_Pump1['Timestamp'], y=[upper_limit_value]*len(Df_Pump1), mode='lines', line=dict(color='red', dash='dash'), name='Limite Superior Histórico'))

# Adicionar a projeção
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=df_future['Value'], mode='lines', name='Projeção'))

# Adicionar a linha de limite superior também na projeção
fig.add_trace(go.Scatter(x=df_future['Timestamp'], y=[upper_limit_value]*len(df_future), mode='lines', line=dict(color='red', dash='dash'), name='Limite Superior Histórico Projeção'))

# Personalizar o layout, incluindo o tamanho da fonte
fig.update_layout(
    title={
        'text': 'Projeção de Temperatura com LSTM e Intervalo de Confiança',
        'font': {'size': 24}
    },
    xaxis_title={
        'text': 'Timestamp',
        'font': {'size': 20}
    },
    yaxis_title={
        'text': 'Value',
        'font': {'size': 20}
    },
    hovermode='x',
    template='plotly_white',
    font=dict(size=16)  # Aumentar o tamanho da fonte para outros elementos
)

fig.show()


**4.	Resultados e Discussões**

Com base nos resultados apresentados para a amostra de dados coletados, os modelos estudados anteriormente apresentaram diferentes comportamentos, sendo que os modelos de aprendizado de máquina RNN-GRU e RNN-LSTM apresentaram o melhor desempenho em termos de métricas de erro (MAE e MSE) e explicação da variância (R2), ou seja, estes modelos foram capazes de capturar padrões complexos nos dados temporais.

Muito próximo aos resultados dos modelos de aprendizado está o modelo de Média Móvel, que também obteve um bom desempenho, como esperado, com baixas métricas de erro e um R2 alto, sugerindo como um modelo simples como a média móvel pode ser eficaz na previsão de séries temporais em certos casos.

Por outro lado, o modelo ARIMA apresentou um desempenho relativamente ruim em comparação com demais, tendo resultado em altos valores de MAE e MSE e um R2 negativo, o que indica que o modelo ARIMA pode não ter sido capaz de capturar adequadamente a estrutura dos dados de temperatura para a Bomba 1.

Já o caso dos modelos de regressão linear múltipla e SVR, estes mostraram desempenho intermediário, com valores moderados de MAE, MSE e R2, podendo ser mais bem estudado para ajustar os dados aos requisites destes modelos.

Complementando a análise, os modelos de State Space Model, SARIMAX e Exponential Smoothing apresentaram um desempenho inferior em comparação com outros métodos, com valores relativamente altos de MAE e MSE e R2 negativos, indicando que estes modelos podem não ser adequados para capturar a complexidade dos dados temporais de temperatura para a Bomba 1.

Portanto, para o conjunto de dados considerados neste estudo, os modelos RNN-GRU e RNN-LSTM e o Modelo SVR com Randomized Search CV foram os mais adequados considerando o ajuste dos MAE e MSE e R2 aos dados coletados, sendo os mais adequados para realizar previsões. 

Em contrapartida, os tempos de processamento para os modelos os modelos RNN-GRU e RNN-LSTM foram consideravelmente altos, indicando a necessidade de aprofundamento sobre o impacto deste tempo, quando na análise dos dados contínuos.

Normalidade dos Resíduos: Nenhum dos modelos possui resíduos normalmente distribuídos.

Desempenho Relativo: O modelo LSTM parece ter uma melhor performance em termos de menor variabilidade dos resíduos e menor presença de 
outliers.

Ajuste do Modelo: Pode ser necessário ajustar ou refinar os modelos, ou considerar transformações nos dados para melhorar a normalidade e reduzir a variabilidade dos resíduos.

Os pequenos componentes dos ativos de mineração considerados neste estudo, não possuem monitoramento que possibilite antecipar anormalidades, e consequentemente auxiliar na identificação de falhas prematuras. 

As possíveis análises são feitas por inspeção sensitiva e ou avaliações indiretas de parâmetros relacionados aos sistemas, que são registrados em relatórios mensais e nos backlogs diários. Os resultados obtidos nas coletas de dados apresentam resultados potenciais e que podem ser utilizadas para identificar com maior assertividade, o momento ótimo de manutenção ou realizar uma melhoria de projeto naquele ponto específico. 

O uso desta técnica trouxe benefícios adicionais ao que foi identificado no estudo de caso anterior, com a redução do número de intervenções de manutenções (coleta online) e garantir que o intervalo P-F seja mais bem entendido com a análise dos dados de temperatura.

Adicionalmente, a falta de parâmetros claros de monitoramento aliado ao considerável número de pequenos componentes que podem ser cobertos por este modelo de monitoramento, a abordagem realizada neste estudo pode ser indicada para viabilizar tais técnicas de monitoramento para garantir a confiabilidade do sistema, aumentar a precisão na tomada de decisão das manutenções e atualizações das máquinas e equipamentos.



**7.	Referências Bibliográficas**

Aguirre-Jofré, H. Eyre, M.Valerio, S. Vogt, D 2021. Low-cost internet of things (IoT) for monitoring and optimising mining small-scale trucks and surface mining shovels. Camborne School of Mines, University of Exeter, Exeter, United Kingdom and ndependent Consultant, Dataquest 131: 103918. 

Aileen Nielsen 2021. Análise prática de séries temporais: predição com estatística e aprendizado de máquina. Alta Books: Rio de Janeiro

Artur Skoczylasa,Paweł Stefaniaka, Wiesława Gryncewiczb, Artur Rotb 2023. The Concept of an Intelligent Decision Support System for Ore Transportation in Underground Mine. 27th International Conference on Knowledge Based and Intelligent Information and Engineering Sytems 2023: 922–931. 

Aurélien Géron 2021. Maos à Obra: Aprendizagem de Máquina com Scikit-Learn, Keras e TensrFlow - 2nd edição atualizada com TensorFlow2. O'Reilly Media, Inc.: Rio de Janeiro.

Daniel Schmidt, Karsten Berns 2013. Climbing robots for maintenance and inspections of vertical structures - A survey of design aspects and technologies. Robotics and Autonomous Systems 61: 1288-1305. 

FÁVERO, Luiz Paulo Lopes e BELFIORE, Patrícia Prado 2024. Manual de Análise de Dados – Estatística e Machine Learning com Excel®, SPSS®, Stata®, R® e Python®. GEN LTC: Rio de janeiro

Ferreira, B., Seruffo, M., & Pires, Y.  2022. Planejamento e construção de um protótipo de aplicativo mobilem para visualização de dados de sistema de monitoramento de máquinas e equipamentos. Revista Principia - Divulgação Científica e Tecnológica do IFPB 59(3): 947-966. 

Gbadamosi, Abdul-Quayyum & Oyedele, Lukumon & Davila Delgado, Manuel & Kusimo, Habeeb & Akanbi, Lukman & Olawale, Oladimeji & Muhammed -Yakubu, Naimah 2021. IoT for predictive assets monitoring and maintenance: An implementation strategy for the UK rail industry. Automation in Construction 122: 103486. 10.1016/j.autcon.2020.103486.

João Pedro Dias, André Restivo, Hugo Sereno Ferreira 2022. Designing and constructing internet-of-Things systems: An overview of the ecosystem. Internet of Things. journal homepage: www.elsevier.com/locate/io 19: 100529. 

Manh-Kien Tran, Satyam Panchal, Vedang Chauhan, Niku Brahmbhatt, Anosh Mevawalla, Roydon Fraser, Michael Fowler 2021. Python-based scikit-learn machine learning models forthermal and electrical performance prediction of high-capacity lithium-ion battery. Int J Energy Res.2022 46: 786–794. 

Nascimento, E. dos S., Maroli, K. R., Dias, G. C. M., & Bovério, M. A.  2020. GESTÃO DE MANUTENÇÃO INDUSTRIAL: eletrificação de acionamento de terno de moenda. SITEFA 3(1): 180–191.

Pedro A. Morettin, Clélia M. C. Toloi 2020. Análise de Series Temporais Modelos multivariados e não lineares. Edgard Blucher : São Paulo, SP.

scikit-learn.org scikit-learn. 2024 scikit-learn: Machine Learning in Python: https://scikit-learn.org/stable/

Yingming Tian, Fan Gao and Peng Wu2 1992. Intelligent Diagnosis of Equipment Health Based on IOT and Operation Large Data Analysis. Journal of Physics: Conference Series : 1742-6596.
