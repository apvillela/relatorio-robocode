## 1. INTRODUÇÃO

O Robocode é uma plataforma de programação educativa que tem como objetivo principal ensinar conceitos de programação e desenvolvimento de software por meio da criação de robôs que competem em batalhas virtuais. Utilizando a linguagem Java (ou .NET), os alunos desenvolvem robôs que devem se movimentar e atacar outros robôs em um ambiente de simulação. O intuito acadêmico de utilizar o Robocode em cursos de Análise e Desenvolvimento de Sistemas é proporcionar uma experiência prática e divertida que vai além da teoria. Ao trabalhar com Robocode, os alunos têm a oportunidade de aplicar conceitos de programação orientada a objetos, algoritmos, e estruturas de dados em um contexto prático.

Outra parte crucial da prática de desenvolvimento deste projeto é o versionamento, e é aí que o GitHub se torna relevante. O versionamento de projetos é um processo que permite controlar as mudanças feitas no código ao longo do tempo. O GitHub é uma ferramenta amplamente utilizada para esse propósito, oferecendo um ambiente para armazenar e gerenciar versões do código-fonte de um projeto.

Aprender a usar o GitHub e entender os fundamentos do versionamento é fundamental para qualquer desenvolvedor. O versionamento facilita a colaboração entre equipes, permite o rastreamento de alterações e ajuda a evitar conflitos no código. Além disso, com o GitHub, os alunos podem explorar práticas de integração contínua e de desenvolvimento colaborativo, que são essenciais em projetos de software modernos.

Portanto, ao integrar o uso do Robocode com ferramentas de versionamento como o GitHub, os alunos não só aprimoram suas habilidades de programação, mas também aprendem a gerenciar e colaborar em projetos de software. Esse conhecimento é indispensável para a formação de profissionais capacitados para o mercado de trabalho, onde a colaboração e o controle de versões são práticas comuns e essenciais para o sucesso de qualquer projeto de desenvolvimento.

## 2. OBJETIVOS DA ATIVIDADE

- Melhorar a Programação: Aprender a programar criando e ajustando robôs no Robocode, aplicando conceitos como orientação a objetos e algoritmos.

- Resolver Problemas: Praticar a resolução de desafios e otimizar o código para que os robôs performem melhor nas batalhas.

- Aprender Versionamento: Conhecer e usar o GitHub para controlar mudanças no código, colaborar com outros e gerenciar diferentes versões do projeto.

- Trabalhar em Equipe: Entender como usar o GitHub para colaborar em projetos com outras pessoas e resolver conflitos no código.

- Aplicar Boas Práticas: Aprender práticas de desenvolvimento que são usadas em projetos reais.

- Unir Teoria e Prática: Aplicar o que foi aprendido em teoria em um projeto prático e divertido, fixando o conhecimento.

## 3. DESCRIÇÃO DA ATIVIDADE

### Dia 1: Instalação e Exploração do Robocode

No primeiro dia da atividade, a equipe se concentrou na instalação do Robocode no sistema operacional Linux, utilizando o terminal bash. Inicialmente, realizamos o download e configuramos o ambiente necessário para rodar o Robocode.

Após a instalação, exploramos o funcionamento geral do Robocode. Rodamos e analisamos algumas batalhas de exemplo fornecidas pelo programa, o que nos ajudou a entender a mecânica do jogo e como os robôs interagem no ambiente de simulação. Essa prática inicial foi essencial para familiarizar a equipe com a ferramenta e preparar o terreno para as próximas fases da atividade.

### Dia 2: Configuração do Projeto e Modificação do Código

No segundo dia da atividade, a equipe começou lendo e analisando a documentação do Robocode. Isso foi crucial para entender como funcionam as classes de robôs e quais métodos podemos implementar para melhorar o desempenho dos robôs nas batalhas.

Depois de entender a documentação (partes dela, na verdade), o próximo passo foi trabalhar com um código exemplo. Esse código serviu como ponto de partida para ajustar e otimizar o robô. Discutimos estratégias sobre como melhorar o robô para que ele se saísse melhor nas batalhas.

Para organizar o trabalho em equipe, o Guilherme criou um repositório no GitHub chamado "agora-vai". Ele compartilhou esse repositório com Gabriela e Alexandre. Cada um de nós fez um fork do repositório do Guilherme, criando uma cópia independente em nossas contas do GitHub.

Em seguida, clonamos nossas cópias locais do repositório para os computadores do laboratório. Usamos o terminal bash para controle de versionamento local e a IDE do Robocode para começar a modificar o código do robô conforme discutido. Isso nos permitiu trabalhar simultaneamente em diferentes partes do código e preparar o robô para a próxima etapa.

Esse primeiro dia foi importante para estabelecer as bases do nosso trabalho em equipe e aplicar os conceitos que aprendemos sobre programação e versionamento.

### Dia 3: Refinamento do Código e Melhoria da Estratégia de Batalha

No terceiro dia, com a equipe já familiarizada com o GitHub e o Robocode, focamos no refinamento do código e na otimização das estratégias de batalha do robô. Revisamos e ajustamos o código com base em simulações anteriores, buscando melhorar o desempenho do robô em diferentes cenários de combate. Realizamos novas simulações para testar essas alterações e ajustar estratégias conforme necessário.

Continuamos a usar o GitHub para gerenciar as mudanças no código e resolver conflitos, garantindo uma colaboração eficiente entre os membros da equipe.

### Dia 4: Batalha Final e Avaliação de Desempenho

No quarto dia, a atividade culminou com uma batalha entre todos os robôs desenvolvidos pela turma. Nosso robô se destacou nas fases iniciais da competição, demonstrando um desempenho sólido ao adotar uma estratégia de movimentos circulares e desviar eficientemente dos projéteis inimigos. Essa abordagem garantiu que nosso robô chegasse à "batalha final" entre os três melhores colocados.

Na fase final, tivemos um desempenho abaixo do esperado. Apesar de eliminar um robô em cada confronto, fomos eliminados logo em seguida em todas as batalhas subsequentes, resultando em um terceiro lugar entre os três finalistas. Essa experiência proporcionou uma visão valiosa sobre a necessidade de refinar ainda mais as estratégias de combate e as técnicas de programação para melhorar o desempenho em cenários de destruição do inimigo (MOHG, I'LL FIND YOU AND I'LL KILL YOU).

## ESTRUTURA DO GIT UTILIZADA

Durante a atividade, utilizamos uma estrutura Git para gerenciar o desenvolvimento colaborativo do projeto. Cada membro da equipe executou pelo menos uma das seguintes ações: fez um fork do repositório original, clonou o repositório para uma cópia local, criou uma branch, fez uma modificação no código, commitou as alterações, abriu um pull request e resolveu um problema de mesclagem (elaborado propositalmente ou não).

Repositório: O repositório principal foi criado por Guilherme no GitHub, nomeado "agora-vai". Cada membro fez um fork desse repositório para criar sua própria cópia pessoal. Após a criação do fork, realizamos a clonagem das cópias para nossos computadores locais, permitindo que cada um trabalhasse em suas próprias modificações de forma independente.

Branches: Utilizamos uma estratégia de branching para organizar o trabalho. Tínhamos uma branch principal chamada main, criada automaticamente pelo Github, que representava o estado estável do projeto. Cada membro criou branches (seriam de feature) para trabalhar em suas respectivas alterações. Essas branches permitiram que os desenvolvedores trabalhassem em novos recursos ou melhorias sem interferir diretamente no código principal.

Commits: Os commits foram fundamentais para documentar o progresso e as alterações realizadas no código. Cada membro fez pelo menos um commit, sempre escrevendo mensagens claras e descritivas sobre as modificações feitas. Essas mensagens ajudaram a manter um histórico compreensível das alterações e facilitou a revisão e a integração das mudanças. Material que sugeri para os colegas da equipe: https://wiki.openstack.org/wiki/GitCommitMessages#Information_in_commit_messages.

Pull Requests: Abrimos pull requests para integrar as alterações feitas nas branches (de feature) para a branch main. Pull requests serviram para revisar e discutir as mudanças antes da integração, garantindo que todas as alterações fossem revisadas por outros membros da equipe e estivessem alinhadas com o código principal. Durante esse processo, resolvemos pelo menos um problema de mesclagem, que foi feito propositalmente para praticar a resolução de conflitos e garantir uma integração suave das alterações.

Além disso, para garantir que todos os membros compreendessem o uso do GitHub, elaboramos este relatório de forma versionada utilizando a mesma ferramenta. Isso possibilitou que os integrantes com menos familiaridade com o GitHub se familiarizassem melhor com suas funcionalidades e a importância do controle de versão.

## RESULTADOS E APRENDIZADOS

### Resultados Obtidos:

A atividade proporcionou uma experiência rica e prática tanto em termos de programação quanto de colaboração. Nosso robô se destacou nas fases iniciais das batalhas, demonstrando eficácia em estratégias de movimento e evasão. No entanto, enfrentamos dificuldades na fase final, onde nosso desempenho foi prejudicado por uma estratégia que não conseguiu se adaptar rapidamente às condições da batalha. Isso revelou a necessidade de ajustes mais refinados e uma análise mais profunda das táticas de combate.

### Desafios e Superações:

Durante a atividade, enfrentamos vários desafios. Um dos principais foi a integração das modificações feitas por diferentes membros da equipe, que envolveu a resolução de conflitos de mesclagem no GitHub. Para superar esse desafio, praticamos a resolução de conflitos e a colaboração constante, discutindo as melhores práticas e mantendo uma comunicação clara.

### Habilidades Desenvolvidas:

A atividade foi uma oportunidade valiosa para desenvolver e aprimorar várias habilidades. Em programação, aprofundamos nossos conhecimentos em orientação a objetos e técnicas de otimização de código, aprendendo a criar robôs mais eficientes e estratégicos. Em termos de colaboração, aprimoramos nossas habilidades no uso do GitHub, desde a criação de branches até a resolução de conflitos de mesclagem. Também fortalecemos nossa capacidade de trabalhar em equipe, coordenar esforços e revisar o trabalho dos colegas de forma construtiva.

Além disso, a atividade nos ensinou a importância de uma documentação clara e de manter o controle de versão de maneira eficaz, facilitando a gestão de mudanças e a comunicação entre os membros da equipe. Esses aprendizados foram fundamentais para o desenvolvimento de projetos colaborativos e nos prepararam melhor para futuros desafios na área de análise e desenvolvimento de sistemas.

## CONCLUSAO

A atividade proporcionou uma visão prática e abrangente de aspectos fundamentais da programação e colaboração em equipe. Trabalhar com o Robocode e utilizar o GitHub para versionamento e controle de código nos permitiu aplicar conceitos teóricos em um ambiente prático e dinâmico.

A principal conclusão é que a integração efetiva de técnicas de programação, como orientação a objetos e algoritmos, com ferramentas de controle de versão, é crucial para o desenvolvimento de projetos de software. A experiência de criar, testar e otimizar robôs, juntamente com a resolução de conflitos e a colaboração no GitHub, ressaltou a importância de uma abordagem estruturada e colaborativa no desenvolvimento de software.

Esses aprendizados são diretamente aplicáveis em futuros projetos de programação e trabalho em equipe. A capacidade de adaptar estratégias rapidamente, resolver conflitos de código e colaborar eficientemente são habilidades valiosas que contribuirão para o sucesso em qualquer ambiente de desenvolvimento. Em suma, a atividade reforçou a importância de integrar teoria e prática, e a experiência adquirida será fundamental para enfrentar desafios futuros com mais confiança e competência.