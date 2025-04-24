# O que a IA pode fazer hoje?
A Inteligência Artificial evoluiu para uma ferramenta multifacetada, com aplicações que abrangem desde tarefas cotidianas até desafios científicos complexos. 

## 5.1 Auxílio à professores na correção de provas
A aplicação da inteligência artificial no ambiente educacional tem promovido avanços significativos na automatização de tarefas rotineiras, permitindo que professores concentrem seus esforços em atividades pedagógicas mais estratégicas. Um dos campos que mais tem se beneficiado dessa evolução é a correção de provas e exercícios com questões de múltipla escolha.

A seguir, é apresentado um vídeo no qual uma professora utiliza seu celular para corrigir provas com o auxílio de IA, apenas apontando a câmera para os gabaritos preenchidos pelos alunos. A tecnologia empregada interpreta as respostas, compara com o gabarito oficial e retorna o resultado instantaneamente.

<div style="text-align: center;">
  <iframe width="315" height="560"
    src="https://www.youtube.com/embed/RIBoQSm2h7c"
    title="VIDEO IA CORREÇÃO DE PROVAS"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen>
  </iframe>
</div>

	

## 5.2 Locomoção e robótica avançada
A IA revolucionou a robótica com sistemas capazes de navegar em ambientes complexos e executar tarefas físicas. Robôs como o BigDog e Atlas, desenvolvidos pela Boston Dynamics, demonstram habilidades impressionantes, podem caminham em terrenos irregulares, carregando cargas pesadas e recuperam o equilíbrio após quedas, sendo aplicados em missões de resgate e operações logísticas.

## 5.3 Tradução e interação humano-máquina
A IA domina a tradução automática de 99% das línguas humanas, com desempenho próximo ao humano em idiomas como inglês e francês, mesmo quando a tradução não é perfeita ela consegue transmitir a compreensão. Plataformas como o Skype Translator convertem conversas em tempo real para 10 idiomas, enquanto assistentes virtuais como Alexa e Google Assistant respondem a comandos de voz, integrando-se a dispositivos inteligentes.

## 5.4 Recomendações personalizadas
Empresas como Netflix, Spotify e Amazon utilizam algoritmos de aprendizado de máquina para prever preferências com base em histórico de uso. Esses sistemas analisam desde textos e músicas até padrões de compra, refinando recomendações continuamente.

## 5.5 Jogos e Entretenimento
A IA superou campeões humanos em jogos que exigem estratégia, como Go, poker e Dota 2. Em 2022, uma obra de arte gerada por IA venceu uma competição de belas artes, desafiando noções tradicionais de criatividade. Esses feitos não apenas comprovam a capacidade de resolução de problemas, mas também expandem o papel da IA no entretenimento e na cultura, além de levantar questionamentos éticos.

## 5.6 Geração de vídeos a partir de prompts
A geração de vídeos por meio de Inteligência Artificial tem se consolidado como uma das áreas de maior avanço nos últimos anos, refletindo o rápido progresso dos modelos generativos multimodais. A partir de descrições textuais simples, sistemas baseados em IA são capazes de sintetizar vídeos realistas, com movimentos, expressões faciais e até sincronização labial relativamente coerente com falas geradas artificialmente.

A seguir, é apresentado um vídeo comparativo entre dois clipes gerados com o mesmo prompt “Will Smith comendo macarrão”, sendo um criado em março de 2023 e outro em abril de 2025. A comparação evidencia não apenas o salto técnico em fidelidade visual, mas também o avanço na coerência narrativa e na integração de elementos como iluminação, textura e expressividade facial.

<div style= "text-align: center"><iframe width="1351" height="480" src="https://www.youtube.com/embed/DgiHGof2Q7o" title="VÍDEO EVOLUÇÃO DA IA WILL SMITH" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> </div>


## 5.7 Gerenciamento de Múltiplas Contas em Redes Sociais com IA
O gerenciamento automatizado de perfis em redes sociais por meio de Inteligência Artificial tem se mostrado uma prática crescente, especialmente em países como a China, onde a presença digital desempenha um papel central tanto em estratégias de marketing quanto em políticas de comunicação pública e privada.
A seguir, é apresentado um vídeo que documenta essa prática, com a inteligência  artificial gerenciando 50 contas ao mesmo tempo na rede social X.

<div style= "text-align: center"><iframe width="1351" height="480" src="https://www.youtube.com/embed/eFKkgYOX5s4" title="VIDEO IA GERENCIANDO CONTAS NA CHINA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></div>

## 5.8 Planejamento com PDDL em jogos de lógica (Light Up / Akari)
O Planejamento baseado em IA, particularmente com uso de PDDL (Planning Domain Definition Language), tem ganhado destaque por sua capacidade de resolver problemas complexos em ambientes com regras bem definidas. Uma aplicação interessante dessa abordagem é em jogos de lógica, como o Light Up, um puzzle no qual o jogador deve posicionar lâmpadas de forma a iluminar todas as células de um grid, respeitando restrições específicas.

Nesse contexto, a IA atua modelando o problema do jogo como um domínio de planejamento: as regras do jogo são traduzidas para ações, estados e restrições em PDDL. A partir dessa modelagem, um planejador automático é capaz de explorar diferentes sequências de ações até encontrar uma solução válida ou comprovar sua inexistência. Essa abordagem é especialmente eficiente para puzzles de média e alta complexidade, nos quais a resolução por tentativa e erro seria inviável.

Desenvolvi um código em Python para um competição no curso de Fundamentos Lógicos de Inteligência Artificial, lecionada pelo professor Bruno Ribas. O código recebe como entrada um mapa do jogo Light Up e converte automaticamente a estrutura do puzzle para o formato PDDL. Em seguida, o código executa um planejador compatível, como o Madagascar ou Fast Downward (dependendo da categoria da competição), e retorna a sequência de posicionamentos das lâmpadas que resolvem o desafio.

A seguir está o link do repositório do GitHub, nele é possível encontrar mais informações sobre o problema, a competição, exemplos de mapas dos mais fáceis aos mais complexos (que uma pessoa demoraria horas e até dias para resolver), além de encontrar um vídeo explicando detalhadamente como o código funciona tanto por mim quanto pelo professor Bruno Ribas.

[Clique aqui para acessar o repositório.](https://github.com/leohssjr/LightUp-PDDLSolver)