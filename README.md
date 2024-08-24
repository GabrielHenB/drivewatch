# DriveWatch

Desenvolvido para a disciplina de TCC.

Drive Watch é uma solução voltada para a segurança automotiva, utilizando tecnologias de Inteligência Artificial (IA) para monitorar e detectar situações que comprometam a segurança do motorista, como sonolência ao volante. O sistema é ideal para empresas de gestão de frotas, abrangendo desde transportadoras até seguradoras. Ele funciona com base em um Raspberry Pi, equipado com uma webcam que captura imagens do motorista em tempo real, as quais são processadas localmente para identificar sinais de fadiga. Quando detectados, o sistema emite alertas sonoros para chamar a atenção do motorista, ao mesmo tempo em que registra as ocorrências em um banco de dados em nuvem (AWS MySQL), possibilitando o acesso remoto aos gestores por meio de uma aplicação web desenvolvida com Vue JS e Spring Boot. A arquitetura do Drive Watch é composta por quatro blocos principais: hardware, banco de dados, back-end e front-end, todos interligados para garantir o funcionamento do sistema. O hardware é complementado por um buzzer/auto falante de alerta e uma fonte de alimentação que garantem sua operação contínua dentro do veículo.

Grupo: Cristian,      
Dayane,
                        Gabriel B,
                        Guilherme

# How to Clone

1) Clonar repositório em qualquer pasta.
2) Execute 'git submodule init' e 'git submodule update --remote'.
