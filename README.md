Projeto de Escolha de Personagem
Este projeto tem como objetivo desenvolver uma interface gráfica para a seleção, criação e visualização de personagens, integrando a persistência de dados através de um banco de dados MySQL. O projeto é estruturado com princípios de orientação a objetos e boas práticas de organização de código, visando facilidade de uso e extensibilidade.

Objetivos do Projeto
1. Desenvolvimento de Interface para Seleção de Personagem
Criar uma interface gráfica intuitiva para permitir que os usuários possam criar, selecionar e visualizar personagens.
Utilizar Java Swing ou JavaFX para implementar elementos visuais que facilitem a navegação e a experiência do usuário ao interagir com os personagens.
2. Persistência de Dados com MySQL
Conectar o projeto a um banco de dados MySQL para armazenamento e recuperação dos personagens criados.
Permitir que os usuários salvem seus personagens para que possam acessá-los posteriormente, mantendo seus dados de forma segura e organizada.
3. Estrutura de Classes com Herança e Polimorfismo
Desenvolver uma estrutura de classes que represente diferentes tipos de personagens, utilizando uma classe base chamada Personagem e subclasses específicas (como Guerreiro e Mago).
Aplicar conceitos de herança, encapsulamento e polimorfismo para garantir uma organização de código modular e flexível.
4. Implementação de Persistência e Gestão de Exceções
Criar uma classe de exceção personalizada para tratar erros específicos, como o caso de personagens não encontrados.
Implementar funcionalidades de serialização e desserialização para salvar o estado de personagens localmente e permitir seu carregamento em outras sessões.
5. Leitura de Arquivo e Importação de Personagens
Adicionar funcionalidade para importar personagens de arquivos CSV ou TXT, permitindo a criação em massa de personagens e facilitando a administração dos dados.
6. Organização e Gestão do Projeto
Utilizar o Trello para documentar e gerenciar as tarefas do projeto, com listas como "Tarefas a Fazer", "Em Progresso" e "Concluído".
Acompanhar o progresso do desenvolvimento da interface, conexão com o banco de dados e implementação de funcionalidades avançadas, garantindo uma visão clara do status e dos próximos passos do projeto.
Requisitos
Java (Java Swing ou JavaFX para a interface gráfica)
MySQL (para persistência de dados)
Trello (para organização e acompanhamento de tarefas)

Dificuldades Enfrentadas
Durante o desenvolvimento deste projeto, enfrentamos diversos desafios, especialmente ao corrigir erros que surgiam em diferentes partes do código. Um dos maiores obstáculos foi a necessidade de refatorar grandes trechos do código sempre que encontrávamos problemas que afetavam a estrutura ou a lógica do programa. Isso acontecia principalmente devido à complexidade do sistema de herança e polimorfismo e à integração com o banco de dados MySQL. Cada erro que surgia exigia que reexaminássemos toda a estrutura e, muitas vezes, realizássemos mudanças significativas no código, o que demandou um esforço considerável da equipe.

Além disso, tivemos dificuldades com a manipulação e recuperação dos dados no MySQL, pois pequenos ajustes na modelagem dos dados exigiam alterações em vários pontos do código, aumentando a complexidade da manutenção.

Aprendizados
Apesar das dificuldades, este projeto nos ensinou muito sobre boas práticas de desenvolvimento e sobre a importância da organização e modularidade do código. Aprendemos que um código bem estruturado, com classes e métodos bem definidos, facilita muito a manutenção e a implementação de novas funcionalidades. Além disso, esse projeto nos mostrou a importância de planejar e documentar bem o sistema desde o início, de forma a reduzir a quantidade de alterações estruturais que são necessárias ao longo do desenvolvimento.

Compreendemos também o valor de testar o código continuamente, identificando e corrigindo erros nas fases iniciais para evitar retrabalhos maiores depois. Esses aprendizados serão fundamentais para futuros projetos, onde pretendemos adotar uma abordagem ainda mais cuidadosa em relação à arquitetura e modularização do código.


