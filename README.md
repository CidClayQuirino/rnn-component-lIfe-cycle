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
