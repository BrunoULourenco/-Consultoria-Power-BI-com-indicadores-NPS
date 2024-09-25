# Pesquisa-de-Satisfação-para-Empresa-de-Consultoria
O objetivo principal deste projeto é criar uma pesquisa de satisfação que forneça indicadores de Net Promoter Score (NPS), utilizando framework CRISP-DM

Etapas do Projeto:

1) BUSINESS UNDERSTANDING
2) DATA UNDERSTANDING|DATA PREPARATION
3) MODELING
4) EVALUATION
5) DEPLOYMENT
   

 
1) BUSINESS UNDERSTANDING

1.1 A Empresa:

A BT Consultoria é uma empresa especializada em fornecer soluções de consultoria e assessoria a empresas, destacando-se no segmento B2B. Com uma abordagem focada na excelência e inovação, a BT Consultoria se posiciona como um parceiro estratégico para organizações que buscam aprimorar sua comunicação e alcançar resultados mais eficazes.

1.2 Serviços Prestados:

A BT Consultoria oferece uma variedade de serviços especializados, que podem ser categorizados da seguinte forma:

 1.2.1 Criação e Gestão de Conteúdo
 
  A BT Consultoria atua na criação e administração do conteúdo digital das empresas, cobrindo desde o diagnóstico inicial, que avalia pontos fortes e áreas de melhoria, até a elaboração de estratégias de conteúdo. Após definir os pilares e temas de interesse, a empresa gerencia a produção e a publicação do conteúdo, seguindo um calendário tático. Relatórios mensais e feedbacks contínuos são fornecidos para garantir a eficácia e ajustar estratégias conforme necessário.
 
 1.2.2 Endomarketing

     A consultoria desenvolve e implementa estratégias de comunicação interna para fortalecer o vínculo entre a empresa e seus colaboradores. A abordagem visa criar um ambiente de trabalho mais engajado e coeso, utilizando métodos eficazes de comunicação para melhorar a moral e a produtividade da equipe.
 
1.2.3 Gestão de Crise

    A BT Consultoria prepara empresas para enfrentar crises com uma abordagem estruturada. Isso inclui a criação de manuais de crise e treinamentos para a equipe. Durante uma crise real, a empresa assume o controle da comunicação interna e externa, gerenciando interações com a mídia, redes sociais e outros canais para mitigar os impactos negativos e restaurar a reputação da empresa.


1.2.4 Assessoria de Imprensa

     A assessoria de imprensa da BT Consultoria visa melhorar a visibilidade e a reputação das empresas através de uma gestão estratégica da mídia. Isso envolve a criação de conteúdos relevantes, o relacionamento com jornalistas e a monitorização da cobertura de mídia para garantir uma imagem positiva e credível.


1.2.5 Media Training

     A BT Consultoria prepara executivos e equipes para uma comunicação eficaz com stakeholders. Os treinamentos são projetados para melhorar as habilidades de comunicação, garantir que a mensagem da empresa seja transmitida de forma clara e profissional, e lidar com situações de alta visibilidade com confiança.

2) DATA UNDERSTANDING|DATA PREPARATION

 2.1 Indicadores

  Para avaliar o desempenho da pesquisa de satisfação, serão utilizados os seguintes Indicadores-Chave de Desempenho (KPIs):
Satisfação: Mede o nível geral de contentamento dos clientes com os serviços oferecidos pela BT Consultoria.
Eficiência: Avalia a eficácia dos processos e serviços prestados, identificando áreas de melhoria para otimizar a entrega de valor.
Qualidade: Examina a qualidade do atendimento ao cliente, incluindo a capacidade de resposta, a resolução de problemas e a satisfação com o suporte recebido.
Análise Concorrencial: Compara o desempenho da BT Consultoria em relação aos concorrentes, identificando pontos fortes e áreas de oportunidade para se destacar no mercado.

 2.2 Coleta dos Dados

    
Foram criados três tipos de pesquisas de satisfação: a pesquisa de entrada, a pesquisa de acompanhamento e a pesquisa de saída. Cada uma dessas pesquisas é projetada para capturar diferentes aspectos da experiência do cliente ao longo do ciclo de vida do serviço. Elas foram elaboradas no Google Forms, um software gratuito e acessível em diversas plataformas.
  Pesquisa de Entrada
A pesquisa de entrada é realizada no início da relação com o cliente, logo após a assinatura do contrato ou o início da prestação de serviços. Seu principal objetivo é avaliar as expectativas iniciais do cliente em relação aos serviços da BT Consultoria e identificar quaisquer necessidades ou preocupações específicas desde o início.
Aqui tem-se perguntas de escala (0-10) e de campo aberto. O questionário é curto e a expectativa do cliente é capturada de forma qualitativa. O link para essa pesquisa é o seguinte: <https://forms.gle/q9qE8qUbTgMt9Y7Q6>.
   Pesquisa de Acompanhamento
A pesquisa de acompanhamento (follow up) é realizada durante a execução dos serviços, em intervalos regulares acordados com o cliente. Seu objetivo é monitorar a satisfação contínua, avaliar o progresso e identificar áreas que podem exigir ajustes ou melhorias. Permite a identificação precoce de problemas ou insatisfações, possibilitando a implementação de correções rápidas e a manutenção de um alto nível de satisfação ao longo da prestação dos serviços.
A pesquisa encontra-se no seguinte link <https://forms.gle/ViCSUZyMUjDGwn3o9> e conta com perguntas de escala (0-10), “sim ou não” e resposta aberta. No caso da pergunta que permite ao usuário digitar um texto, “Cite alguns exemplos de como ajudamos sua empresa a ter mais autoridade, credibilidade e posicionamento estratégico”, trata-se de um item que gera dados qualitativos.
   Pesquisa de Saída
A pesquisa de saída é realizada ao final da prestação de serviços, quando o cliente conclui a sua relação com a BT Consultoria. O objetivo é avaliar a satisfação geral com o serviço prestado e entender a experiência global do cliente. Ao identificar o motivo da saída e possibilidade de retorno, tem-se insights valiosos para a empresa.
A pesquisa encontra-se no seguinte link <https://forms.gle/wTK38e73MqM1KoGv7> e conta com perguntas de escala (0-10), “sim ou não”, múltipla escolha e resposta aberta. Novamente há a possibilidade de extrair dados qualitativos através do texto informado pelo usuário, enquanto as outras perguntas geram gráficos no dashboard. Aqui tem-se um questionário pequeno, visto que na saída o (ex)cliente pode ter menor disposição em responder.

2.3 Preparação dos Dados

   Após definirmos as perguntas-chave em nosso formulário, utilizamos uma abordagem inovadora para coletar os dados. Criamos um formulário com perguntas de 0 a 10, projetadas para medir diferentes aspectos da satisfação do cliente. O objetivo era obter uma visão detalhada de como os clientes percebem nossos serviços e identificar áreas de melhoria.
Em vez de esperar pela resposta manual de clientes reais, decidimos simular um cenário com o uso de inteligência artificial. A IA foi programada para responder aos formulários com base em padrões realistas de comportamento do cliente. Esse processo não apenas acelerou a coleta de dados, mas também nos permitiu trabalhar com uma amostra ampla e variada de respostas.
Essa abordagem nos deu uma base sólida para construir o nosso dashboard e realizar análises mais profundas, garantindo que pudéssemos visualizar diferentes cenários de satisfação e comportamento, além de otimizar o tempo de desenvolvimento.

2.4 Limpeza dos Dados

     Durante o processo de tratamento dos dados, percebemos que os números fornecidos pela IA estavam, em sua maioria, muito baixos. Isso poderia comprometer a análise final e não forneceria insights úteis sobre a performance da empresa. Identificamos que, com os dados nesse formato, seria difícil tirar conclusões relevantes sobre a satisfação dos clientes.
Por conta disso, decidimos ajustar alguns dos dados para refletir um cenário mais equilibrado e realista. Fizemos a edição cuidadosa de certas respostas, garantindo que o resultado final fosse mais representativo das variações esperadas no comportamento dos clientes. Com essa abordagem, conseguimos otimizar as informações no dashboard e gerar insights mais acionáveis para o projeto.

3) MODELING

3.1 Ajuste dos Dados


  Utilizamos o Net Promoter Score (NPS) como nosso principal indicador de desempenho para medir a satisfação e lealdade dos clientes. O NPS é uma métrica amplamente adotada por empresas para avaliar a probabilidade de um cliente recomendar a empresa para outras pessoas, o que é um forte sinal de satisfação e confiança.
A metodologia é simples: os clientes respondem a uma pergunta-chave, que geralmente é algo como: "Em uma escala de 0 a 10, quão provável é que você recomende nossa empresa/produto/serviço a um amigo ou colega?". Com base nas respostas, os clientes são classificados em três categorias:
Promotores (9-10): Aqueles que estão muito satisfeitos e entusiasmados com a empresa.
Neutros (7-8): Clientes satisfeitos, mas não tão engajados.
Detratores (0-6): Clientes insatisfeitos ou indiferentes.
O cálculo do NPS é feito subtraindo a porcentagem de detratores da porcentagem de promotores. O resultado pode variar de -100 a 100. Essa métrica nos permitiu identificar não apenas o nível de satisfação geral, mas também áreas específicas onde podemos melhorar, como o atendimento ao cliente ou a qualidade dos nossos produtos.
No nosso dashboard, o NPS foi representado de forma clara, permitindo uma visão rápida e eficiente do desempenho da empresa. Ele se destacou como um termômetro importante para entender como nossos clientes veem nosso serviço ao longo do tempo.


3.2 Conexões dos Dados

  Para se conectar as diferentes bases de dados foi usado o modelo (Star Schema), no se tem tabelas do tipo FACT e DIM, modelo este organizado, em tabelas fato, dimensão e conexão, conforme descrição abaixo:
Tabelas Fato (FACT): São as tabelas centrais do modelo que contêm dados transacionais no caso elas armazenam métricas numéricas de  notas de 0 a 10 que são analisadas.
Tabelas Dimensão (DIM): Fornecem contexto para as métricas da tabela fato. Elas contêm descrições e atributos que enriquecem os dados, no caso descrição dos clientes, perguntas e datas.
Conexão: As tabelas DIM se conectam à FACT através de chaves primárias e estrangeiras, criando um relacionamento que facilita a análise cruzada dos dados.
A técnica usada para se explorar dados no nosso relatório foram visualizações de métricas agregadas (no caso o NPS), através de gráficos do tipo pizza e “gauge”; análise de séries temporais, com uso de gráfico de cascata, e por fim segmentações por filtro (slicers,) referentes a categoria do indicador NPS analisado.


https://drive.google.com/file/d/11VHV0hAtEUxLK-qFMyXsJuszDIrOwZza/view?usp=sharing


4) EVALUATION

Após a coleta e análise dos dados gerados pela Inteligência Artificial (IA), conseguimos identificar insights valiosos que ajudam a traçar um panorama sobre a satisfação e as percepções dos clientes em relação à empresa.

4.1 Nível Geral de Satisfação

O nível geral de satisfação dos clientes, medido pelo NPS, apresentou uma pontuação moderada, com uma média de 50% dos clientes que voltariam a contratar os serviços da empresa. Isso indica que, apesar de um bom número de clientes satisfeitos, ainda há espaço para melhorias, especialmente em questões como atendimento e personalização de soluções.

4.2 Áreas de Maior Satisfação

As maiores pontuações vieram das seguintes áreas:
Atendimento cordial: Os clientes relataram que o atendimento foi cordial e respeitoso, com uma média de 52%, sendo 25 pesquisas e 13 promotores, 5 neutros e 7 detratores. Isso sugere que a equipe de atendimento está desempenhando bem seu papel na resolução de problemas.
Satisfação ao suporte e acompanhamento: A eficiência dos suportes também foi destacada, com uma média de 64% das respostas classificadas como promotor. De 25 respostas 16 foram classificadas como promotores, somente 1 como neutro e 8 detratores. refletindo a eficiência ao suporte e acompanhamento aos clientes.

4.3 Áreas de Menor Satisfação

Identificamos algumas áreas onde a empresa pode focar em melhorias:
Clareza na Comunicação: Muitos clientes sentiram que a comunicação poderia ser mais transparente e clara, com uma média de 66% de detrator.
Valor pelo Custo: A relação custo-benefício foi outro ponto que recebeu uma avaliação relativamente baixa, com uma média de 66% sendo detrator. Com 9 pesquisas realizadas somente 2 foram classificadas como promotores, 1 como neutro e 6 detratores, sugerindo que alguns clientes não percebem o valor que esperam pelo preço pago.

4.4 Feedback Relevante

Os dados coletados indicaram que, apesar de serem gerados por IA, foi possível estruturar informações úteis e relevantes para o cliente. Ao ajustar alguns dados para torná-los mais realistas, conseguimos construir uma base sólida para futuras análises e tomada de decisões. Esses resultados oferecem uma visão inicial de onde a empresa está se destacando e onde pode melhorar, permitindo que ações estratégicas sejam tomadas de forma mais assertiva.

4.5 Visualização dos Resultados

Os dashboards criados no Power BI permitiram uma visualização clara dos dados e facilitaram a identificação dos pontos fortes e fracos. As seguintes capturas de tela destacam as visualizações principais:

   
   Dashboard de Entrada

   https://drive.google.com/file/d/11Xpc44jvKFbKi4f_hv1ax_dy1hH4lJtd/view?usp=sharing

   Dashboard de Follow Up

   https://drive.google.com/file/d/11e-VGk4VCbF0CMiYm3HylOJVovicIhHF/view?usp=sharing


  Dashboard de Saída

    https://drive.google.com/file/d/11gMoEU1M-ELFsxbHiUqEim6HlQk8-yM5/view?usp=sharing

    


 5) DEPLOYMENT


   O dashboard foi otimizado tanto para visualização mobile, quanto no PC, e publicado no Workspace do Power BI.

   
  https://drive.google.com/file/d/11m6_K1Xn7gOBBYYht29-CRs8huaWHf-0/view?usp=sharing
 











