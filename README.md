ZenBot: O robô instrutor de ioga

Nov 11, 2026
Trabalho de Interação Humano-Robô (IHR) apresentado ao Centro Universitário FEI, como parte dos requisitos para aprovação na disciplina de Interação Humano-Robô (CCR230) do curso de Engenharia de Robôs, orientado pelo Prof. Dr. Fagner de Assis Moura Pimentel.

Componentes do grupo
Sofia Linheira Romeiro	11.120.371-7
Matheus Marcondes Pereira Rufino	11.122.028-1
Gabriel Ueno Vertamatti	11.122.159-4
Dereck Nasser Garcia Santos 	11.122.
	
Resumo
O ZenBot é um robô humanoide instrutor de ioga que conduz aulas em grupo para idosos de casas de repouso, com foco na Saudação ao Sol (Surya Namaskar), a sequência clássica do ioga. Sua forma humanoide foi projetada para executar as posturas de maneira correta e servir de modelo visual para os alunos.
Uma câmera no tronco observa a turma e estima a postura de cada aluno. Com alto-falantes e microfones, o robô conduz a respiração, dá instruções e indica correções de forma gentil e individual. O objetivo é oferecer um momento diário de calma e exercício moderado, sem substituir os cuidadores da instituição.

Introdução:
Em uma sociedade cada vez mais agitada e ansiosa, é importante reservar momentos de pausa para relaxar e praticar exercícios. Para idosos em casas de repouso, a atividade física regular ajuda a manter mobilidade, equilíbrio e bem-estar emocional, mas essas instituições costumam ter poucos profissionais e equipes sobrecarregadas, o que limita a oferta de aulas diárias.
O ZenBot ministra uma aula guiada da Saudação ao Sol, adaptada para idosos (com opções na cadeira), demonstrando cada postura com o próprio corpo, conduzindo a respiração pela voz e observando os alunos pela câmera para sugerir correções.
Objetivo em uma frase: conduzir aulas diárias, seguras e acolhedoras de ioga para grupos de idosos, demonstrando e corrigindo as posturas da Saudação ao Sol.
Experiência proporcionada: calma e tranquilidade. Voz suave, movimentos lentos, nenhuma cobrança por desempenho e elogios frequentes, para que o aluno saia da aula relaxado e com vontade de voltar no dia seguinte.
Público-alvo e stakeholders
Público-alvo: idosos (60 anos ou mais) residentes ou frequentadores de casas de repouso e instituições de longa permanência, com mobilidade preservada ou levemente reduzida, que buscam exercício moderado e relaxamento em grupo.
Tipo	Quem	Relação com o robô
Primário	Funcionários do estabelecimento (cuidadores, enfermeiros, educador físico)	Configuram o robô, agendam as aulas, acompanham a turma e respondem a alertas
Secundário	Alunos idosos	Observam os movimentos do robô, repetem as posturas e ajustam a pose quando o robô indica
Terciário	Donos da casa de repouso, familiares dos idosos, médicos e fisioterapeutas	Não interagem diretamente, mas são afetados pela receptividade, pela segurança e pelo custo do robô

Personas:
Persona	Perfil	Contexto social, econômico e cultural	Relação com o ZenBot
-> Primária: Cláudio, 46 anos	Funcionário (cuidador) de uma casa de repouso, acorda cedo	Classe média baixa, ensino médio completo, usa smartphone no dia a dia, rotina corrida de plantões	Configura o robô pelo tablet para iniciar a aula no horário definido e acompanha a turma
-> Secundária: Dona Maria Cláudia, 67 anos	Moradora da casa de repouso	Aposentada, pouca familiaridade com tecnologia, católica, gosta de conversar e de música	Reúne-se com as amigas após o café da manhã para a sessão de ioga, buscando tranquilidade e exercício moderado
-> Terciária: Ademar, 47 anos	Dono da casa de repouso	Empresário de pequeno porte, preocupado com custos e com a reputação da casa	Está animado (e um pouco ansioso) para saber a opinião dos hóspedes sobre o robô
O que o robô precisa saber sobre os usuários antes de iniciar:
•	Lista de alunos inscritos e seus nomes (para cumprimentar e chamar pelo nome).
•	Restrições físicas informadas pela equipe de saúde (ex.: não pode se abaixar, faz a aula na cadeira, usa andador).
•	Nível de experiência e histórico das aulas anteriores.
•	Preferências de volume de voz e de música ambiente.
•	Quem é o funcionário responsável pela sessão, para enviar alertas.

Mapas de empatia:

* Cláudio (persona primária)

 Quadrante	Descrição
-> Vê:	O salão de atividades da casa de repouso, os idosos chegando devagar, o tablet de configuração e o robô em espera
-> Ouve	Conversas dos idosos, pedidos de colegas, o rádio da recepção, a voz do robô iniciando a aula
-> Diz e faz:	Liga e agenda o robô, ajuda os idosos a se posicionarem nos tapetes ou cadeiras, observa a aula de longe
-> Pensa e sente:	“Espero que seja fácil de configurar”; receio de que o robô substitua seu trabalho; alívio por ganhar tempo para outras tarefas
-> Dores:	Pouco tempo, muitas tarefas simultâneas, medo de quedas dos idosos, interfaces complicadas
-> Ganhos:	Aulas que começam sozinhas no horário, alertas claros em caso de problema, relatório simples de participação

* Dona Maria Cláudia (persona secundária)

Quadrante	Descrição
-> Vê	As amigas da clínica, os tapetes e cadeiras, o robô à frente da turma demonstrando as posturas
-> Ouve	A voz calma do robô, música suave, risadas e comentários das amigas
-> Diz e faz	Repete os movimentos, pergunta “assim está certo?”, comenta com as amigas, faz pausas quando cansa
-> Diz e faz	Repete os movimentos, pergunta “assim está certo?”, comenta com as amigas, faz pausas quando cansa
-> Diz e faz	Repete os movimentos, pergunta “assim está certo?”, comenta com as amigas, faz pausas quando cansa
-> Diz e faz	Repete os movimentos, pergunta “assim está certo?”, comenta com as amigas, faz pausas quando cansa
-> Pensa e sente	Curiosidade e um pouco de desconfiança; quer um robô simpático, que não assuste nem pareça gente demais; medo de errar na frente das outras
-> Dores	Dificuldade de equilíbrio, dores nas articulações, audição reduzida, vergonha de ser corrigida em público
-> Ganhos	Momento de tranquilidade, exercício leve, socialização com as amigas, sensação de progresso e de ser elogiada

Contexto de uso:

O ZenBot atua no salão de atividades de uma casa de repouso: um ambiente interno, plano e iluminado, com cerca de 6 a 10 alunos dispostos em semicírculo sobre tapetes ou cadeiras, logo após o café da manhã. Um funcionário permanece no local durante a aula.
Contexto social, econômico e cultural: os alunos são idosos, muitos com pouca familiaridade com tecnologia, e a aula é também um momento de socialização. A instituição tem equipe reduzida e orçamento limitado, por isso o robô precisa ser simples de operar e de manter. Culturalmente, o ioga é visto como prática de relaxamento e saúde; a linguagem deve ser acolhedora, em português brasileiro, evitando termos técnicos em sânscrito sem tradução.
O que o robô precisa saber sobre o ambiente antes de iniciar:
•	Mapa do salão e posição de cada tapete ou cadeira.
•	Iluminação suficiente para a câmera e nível de ruído ambiente.
•	Obstáculos e rotas livres (andadores, cadeiras de rodas, móveis).
•	Localização da base de recarga e do funcionário responsável.
•	Horário e duração previstos da aula.

Jornada do usuário
Narrativa: é terça-feira, 8h30. Cláudio liga o ZenBot e confirma a aula das 9h. Dona Maria Cláudia termina o café e segue com as amigas para o salão, onde o robô as espera de braços abertos. A aula transcorre em clima calmo e, ao final, todas saem relaxadas e combinando de voltar no dia seguinte.
1.	Preparação (início). Cláudio seleciona a turma no tablet e posiciona as cadeiras. O robô faz uma autoverificação e se desloca até a frente do salão. Espacial: o robô se posiciona no centro do semicírculo, a cerca de 3 m dos alunos.
2.	Acolhida. Os alunos chegam; o robô vira a cabeça para cada um e cumprimenta pelo nome. Verbal: “Bom dia, dona Maria Cláudia! Que bom te ver.” Não-verbal: aceno com a mão e LEDs do rosto em tom quente.
3.	Aquecimento e respiração. O robô explica a aula e conduz três respirações profundas. Não-verbal: o peito do robô acende e apaga no ritmo da respiração.
4.	Saudação ao Sol (evolução). O robô demonstra cada uma das posturas, devagar, espelhando o movimento para facilitar a imitação, e anuncia a próxima. A câmera compara a pose de cada aluno com a pose de referência.
5.	Correções. Se um aluno está fora da pose, o robô olha para ele e dá uma dica curta e positiva. Verbal: “Maria Cláudia, tente levar os braços um pouco mais para cima. Isso, ótimo!” Se alguém parece cansado, sugere a versão na cadeira.
6.	Situações de exceção. Se a câmera detecta alguém sentado no chão de forma inesperada ou imóvel, o robô pausa a aula, pergunta se está tudo bem e alerta Cláudio pelo tablet.
7.	Relaxamento final (término). O robô diminui o volume, conduz um minuto de relaxamento e agradece a presença de todos. Espacial: afasta-se um passo, sinalizando o fim.
8.	Pós-aula. O robô envia a Cláudio um resumo (presença e ocorrências) e retorna à base de recarga, contornando os alunos que ainda conversam.

Análise de concorrência:

Já existem robôs sociais que conduzem exercícios para idosos, mas nenhum focado em ioga com correção individual de postura em grupo. Também há soluções não robóticas que atendem o mesmo mercado de ioga guiado.
Plataforma	Tipo	Pontos positivos	Pontos negativos
Zora (NAO com software Zorabots)

Similar: humanoide de 57 cm usado em casas de repouso para conduzir exercícios e jogos	Boa aceitação e engajamento dos idosos; demonstra movimentos com o corpo; operado por equipe não técnica	Pequeno demais para ser visto por um grupo; bateria limitada; problemas de reconhecimento de fala; custo alto (até US$ 24 mil)

Pepper (SoftBank) em projetos como PHAROS
Similar: humanoide de 1,20 m que guia e avalia exercícios por câmera	Tamanho adequado para grupos; tela no peito; reconhece emoções; pesquisas mostram boa aceitação	Não tem pernas (base com rodas), então não demonstra posturas de ioga em pé ou no chão; produção interrompida pela SoftBank em 2021
YogiFi Smart Mat
Diferente: tapete de ioga com sensores de pressão e app com IA	Correção de postura em tempo real; sem câmera (mais privacidade); baixo custo por usuário	Uso individual; depende de celular ou TV; não tem presença física nem interação social, pouco atrativo para idosos
Mais interessante para a equipe: o Zora, por já ter sido validado em casas de repouso por dois anos e mostrar que idosos aceitam um humanoide instrutor. O ZenBot combina essa presença física com a correção de postura do YogiFi e um corpo maior, com pernas, capaz de demonstrar a Saudação ao Sol.
Design do robô
Forma, função e affordances
A forma humanoide casa com a função: para ensinar posturas, o robô precisa de braços, pernas e tronco articulados que sirvam de modelo. Cada parte sinaliza uma capacidade:
•	Olhos (câmera e LEDs): indicam que o robô enxerga os alunos.
•	Braços e pernas articulados: indicam que ele demonstra movimentos, não que pega objetos (mãos simplificadas, sem garra).
•	Faixa de LED no peito: indica o ritmo da respiração.
•	Tablet do funcionário: concentra a configuração, para que os idosos não precisem tocar em telas.
Acessibilidade: voz clara, em volume ajustável e com fala pausada para quem tem perda auditiva; legendas e ícones grandes no tablet; todas as posturas com versão adaptada na cadeira; movimentos lentos e previsíveis.
Prometer menos e entregar mais: o robô se apresenta como “instrutor de ioga”, não como fisioterapeuta ou companheiro. Ele não promete conversar sobre qualquer assunto nem diagnosticar dores; assim, quando lembra o nome do aluno ou elogia uma melhora, supera a expectativa.
Grau de antropomorfismo
No espectro máquina ↔ humano, o ZenBot fica no ponto humanoide estilizado (cerca de 60%): tem corpo com proporções humanas, necessário para demonstrar as posturas, mas rosto simplificado (dois olhos de LED e uma tela de expressões), sem pele, cabelo ou boca realista.
Esse padrão (semelhante ao NAO e ao Pepper) é o mais aceito em casas de repouso, pois é simpático sem parecer uma pessoa. Para evitar o vale da estranheza, o grupo evita traços realistas, usa acabamento em plástico branco e cores suaves, mantém o rosto “de desenho” e garante que voz e movimentos sejam coerentes com essa aparência.
Padrões de design
1.	Demonstrar e imitar (instrutor-modelo): o robô executa a postura e o aluno a reproduz, como em uma aula com professor humano.
2.	Feedback corretivo positivo: após observar, o robô dá uma dica curta e termina com um reforço (“isso, ótimo!”).
Os dois se combinam em um ciclo: demonstrar → observar → corrigir com gentileza → elogiar → próxima postura. A demonstração dá o modelo e o feedback fecha o ciclo de aprendizagem sem constranger o aluno.
Valores e ética
Seguindo o Value-Sensitive Design, o ZenBot se adapta aos idosos, e não o contrário. Dois valores guiam o projeto:
•	Segurança física: nenhuma postura deve gerar risco de queda ou lesão. O robô só propõe posturas liberadas pela equipe de saúde para cada aluno, oferece sempre a versão na cadeira, nunca toca nos alunos e pausa a aula ao detectar qualquer situação anormal.
•	Privacidade e dignidade: a câmera é usada apenas para estimar o esqueleto (pontos das articulações), sem gravar nem transmitir vídeo; os dados ficam no robô e só o resumo de presença vai para a equipe. Correções são feitas de forma discreta e positiva, sem expor quem errou.
Risco ético: a instituição usar o robô para substituir o contato humano e reduzir a equipe, aumentando o isolamento dos idosos. Mitigação: o robô só inicia a aula com um funcionário presente e cadastrado na sessão, é apresentado como ferramenta de apoio ao cuidador e incentiva a conversa entre os próprios alunos ao fim da aula.
Protótipo no papel
 
protótipo no papel · 9 partes

O corpo é montado com esfera (cabeça), caixas (tronco, quadril e pés) e cilindros (braços e pernas), com cerca de 1,30 m de altura: alto o bastante para ser visto por toda a turma sentada, sem intimidar. Não há tela no robô; a configuração fica no tablet do funcionário.

Ações do robô

Ação	Descrição	Pré-requisitos	Mudança no ambiente ao final
Iniciar sessão	Sai da base, faz autoverificação e vai até a frente do salão	Aula agendada, bateria acima de 50%, funcionário presente	Robô posicionado e pronto; turma avisada de que a aula vai começar
Cumprimentar alunos	Identifica cada aluno que chega e cumprimenta pelo nome	Lista da turma carregada, aluno dentro do campo de visão	Aluno acolhido e presença registrada
Conduzir respiração	Orienta inspiração e expiração com voz e luz no peito	Alunos posicionados	Turma calma e sincronizada
Demonstrar postura	Executa cada postura da Saudação ao Sol de forma lenta e espelhada	Espaço livre de 1 m ao redor do robô, equilíbrio verificado	Alunos com a referência visual da postura
Avaliar postura	Compara o esqueleto estimado de cada aluno com a pose de referência	Iluminação adequada, aluno visível	Lista de alunos que precisam de ajuste
Corrigir postura	Olha para o aluno e dá uma dica curta e positiva	Desvio detectado acima do limite por mais de 3 s	Aluno ajusta a pose ou passa à versão adaptada
Pausar e alertar	Interrompe a aula e notifica o funcionário	Queda, imobilidade ou pedido de ajuda detectado	Funcionário a caminho; turma em espera segura
Encerrar e recarregar	Faz o relaxamento final, envia o resumo e volta à base	Fim da sequência ou do tempo da aula	Resumo enviado, robô recarregando, salão livre
Interações do robô

Espacial

Durante a aula, o ZenBot fica na zona social de Hall (cerca de 2,5 a 3 m) dos alunos, de frente para a turma, no centro de um semicírculo. Isso forma uma F-formation em “U” (ou semicírculo), em que todos compartilham o mesmo espaço de atenção: o robô. Para uma correção individual, ele apenas gira o tronco e a cabeça em direção ao aluno, sem entrar na zona pessoal (abaixo de 1,2 m).
Início da interação: o robô entra no salão pela frente, nunca por trás dos alunos, em velocidade baixa (cerca de 0,3 m/s). Antes de se mover, olha para o destino e acende uma seta luminosa no peito indicando a direção.
Interação	Descrição	Pré-requisitos	Resposta emocional esperada
Posicionar-se diante da turma	Para no centro do semicírculo, a cerca de 3 m	Mapa do salão e alunos sentados ou em pé	Sensação de aula organizada e de segurança
Orientar-se para um aluno	Gira o tronco e a cabeça para quem recebe a dica	Aluno identificado pela câmera	Sentir-se visto e acompanhado
Afastar-se ao final	Dá um passo atrás e se curva levemente	Fim do relaxamento	Fechamento tranquilo, sem pressa
Pessoas paradas, em conversa ou em grupo: o robô reduz a velocidade, mantém pelo menos 1,2 m de distância e contorna o grupo por fora, nunca passando entre pessoas que conversam (o espaço interno da F-formation). Em corredores, segue pela direita e para se não houver espaço, aguardando a passagem.
Ajuste para outro contexto: em uma aula individual domiciliar, o robô pode ficar a cerca de 1,5 m (início da zona social), lado a lado com o aluno em vez de frente a frente (formação em “L”), para que a pessoa o imite olhando para o mesmo lado.

Verbal

A interação verbal será restrita (máquina de estados com comandos). A aula tem um roteiro fixo e a segurança é prioridade: um chatbot aberto poderia dar conselhos de saúde indevidos ou responder de forma imprevisível. Comandos simples (“pausa”, “repete”, “mais devagar”, “estou cansada”, “ajuda”) cobrem as necessidades da aula.
Interação	Descrição	Pré-requisitos	Resposta emocional esperada
Saudação	“Bom dia, dona Maria Cláudia! Vamos começar?”	Aluno reconhecido	Acolhimento e proximidade
Instrução de postura	Anuncia a postura e conduz a respiração	Turma posicionada	Calma e confiança
Correção	Dica curta, nominal e positiva	Desvio de postura detectado	Motivação, sem constrangimento
Resposta a comando	“Claro, vamos mais devagar” ao ouvir “mais devagar”	Comando reconhecido com confiança	Sensação de controle
Encerramento	Agradece e convida para a próxima aula	Fim da sequência	Satisfação e vontade de voltar
Timing: o robô espera de 1 a 2 s após o aluno parar de falar antes de responder (idosos falam com mais pausas). Usa marcadores curtos como “isso”, “muito bem” e “hum-hum” durante as posturas, e respeita silêncios longos nos momentos de relaxamento.
Voz (TTS): feminina ou neutra, grave-média, lenta (cerca de 20% mais devagar que o padrão) e suave, como a de um professor de ioga. Combina com a aparência amigável e com o propósito de acalmar; evita tons infantis, que soariam condescendentes.
Limitação do reconhecimento de fala: a voz de idosos costuma ser mais baixa e trêmula, e o salão tem música e conversas paralelas. Mitigação: vocabulário pequeno e fixo, microfone direcional, pausar a música ao detectar fala, confirmar comandos importantes (“Você quer pausar?”) e oferecer gestos alternativos, como levantar a mão para pedir pausa.

Não-verbal

Canais escolhidos: olhar e gesto/postura (imitação).
Interação	Descrição	Pré-requisitos	Resposta emocional esperada
Olhar dirigido	Olha para o aluno antes de corrigi-lo e alterna o olhar pela turma durante a aula	Posição dos rostos conhecida pela câmera	Sentir-se incluído e atendido
Demonstração espelhada	Executa a postura como em um espelho (levanta o braço esquerdo quando pede o direito)	Espaço livre e equilíbrio verificado	Facilidade em imitar, menos confusão
Aceno e reverência	Acena ao cumprimentar e faz uma leve reverência ao encerrar	Início ou fim da aula	Cordialidade e respeito
Percepção das pistas da pessoa: a câmera estima a direção do rosto (para saber se o aluno está olhando para o robô) e o esqueleto corporal (para saber a postura, se a mão está levantada ou se a pessoa sentou).
Falha de coordenação: se o robô diz “levante os braços” enquanto ainda os abaixa, ou diz “Maria Cláudia, ótimo!” olhando para outra aluna, a turma se confunde, imita o movimento errado e perde a confiança no instrutor.
Pista exclusiva do robô: uma faixa de LED no peito que acende devagar na inspiração e apaga na expiração, funcionando como um metrônomo visual da respiração. Durante a correção, um ponto de luz no braço do robô indica qual parte do corpo deve ser ajustada.

Emoção

Modelo escolhido: dimensional de Russell (valência × ativação). O objetivo da aula é levar os alunos para o quadrante de valência positiva e baixa ativação (calma, relaxamento). Um modelo contínuo permite medir esse deslocamento ao longo da aula, algo que as categorias discretas de Ekman (alegria, raiva, medo…) não capturam bem.
Percepção do estado emocional:
•	Rosto: expressões de dor, cansaço ou sorriso detectadas pela câmera.
•	Voz: volume, ritmo e tom ao falar com o robô (ex.: voz tensa ou ofegante).
•	Postura: ombros contraídos, movimentos bruscos ou parar no meio da sequência indicam desconforto ou alta ativação.
Quando mimetizar: o robô espelha emoções positivas e de baixa ativação (sorriso, calma, satisfação ao completar uma postura), reforçando o clima da aula.
Quando não mimetizar: diante de frustração, raiva ou ansiedade, o robô não retribui. Ele baixa o tom de voz, desacelera, valida o sentimento (“Tudo bem, vamos no seu ritmo”) e oferece a versão mais leve da postura, puxando a ativação para baixo.
Risco de expectativas: se o robô parece emocionalmente responsivo, os idosos podem esperar que ele converse sobre a vida, perceba tristeza profunda ou seja um amigo. O ZenBot não consegue cumprir isso, pois tem diálogo restrito à aula. Para gerenciar a expectativa, ele deixa claro seu papel (“Sou seu instrutor de ioga”), encaminha assuntos fora da aula ao funcionário e avisa a equipe quando percebe sinais persistentes de tristeza.

Referências
•	Two-Year Use of Care Robot Zora in Dutch Nursing Homes: An Evaluation Study (Healthcare, 2019)
•	Employing Socially Assistive Robots in Elderly Care (arXiv, 2023)
•	Meet Zora, the robot caregiver (Toronto Star, 2018)
•	PHAROS: interactive robot system for physical exercise for the elderly (Sensors, 2018)
•	Robot-Assisted Group Exercise Program for Sarcopenia with Pepper (Univ. de Gênova)
•	YogiFi smart yoga mat — CES 2020 Innovation Award (iMore)
•	HALL, E. T. The Hidden Dimension. 1966 (proxêmica).
•	RUSSELL, J. A. A circumplex model of affect. Journal of Personality and Social Psychology, 1980.
•	FRIEDMAN, B.; KAHN, P.; BORNIN
