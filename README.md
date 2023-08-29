# Projeto de Microfrontends com Module Federation - README

Este é um guia para entender as tecnologias e abordagens utilizadas no projeto de Microfrontends, que emprega o conceito de **Module Federation**. O projeto foi dividido em diferentes "packages" para as funcionalidades de Autenticação (Auth), Contêiner (Container), Dashboard e Marketing. ReactJS foi escolhido para implementar o Container, Auth e Marketing, enquanto o Dashboard foi construído com Vue.js. Além disso, a gestão de rotas foi realizada utilizando tanto o `browserhistory` quanto o `memoryhistory`, garantindo uma experiência de navegação suave.

## Tecnologias Principais

1. **ReactJS**: O ReactJS foi utilizado para construir os módulos de Autenticação, Container e Marketing. Ele permite criar interfaces de usuário reativas e dinâmicas, fundamentais para proporcionar uma experiência de usuário de alta qualidade.

2. **Vue.js**: O Vue.js foi escolhido para desenvolver o módulo de Dashboard. Sua abordagem baseada em componentes e sua curva de aprendizado suave o tornam uma excelente escolha para criar interfaces interativas e eficientes.

3. **Module Federation**: O conceito de Module Federation foi empregado para criar uma arquitetura de Microfrontends altamente modular. Isso permite que cada pacote seja desenvolvido de forma independente e, ao mesmo tempo, seja capaz de compartilhar recursos e componentes entre si.

## Roteamento e Navegação

A gestão de rotas foi tratada com cuidado, empregando tanto o `browserhistory` para URLs amigáveis ao usuário quanto o `memoryhistory` para comunicação interna entre os módulos. Isso resultou em uma experiência de navegação coesa e eficiente.

## Implantação e Integração Contínua

O projeto foi implantado usando as GitHub Actions, aproveitando os serviços da AWS, como o CloudFront e o S3, para hospedar os módulos. Isso permite que os possíveis usuários acessem os módulos de forma rápida e confiável, garantindo uma entrega contínua e eficaz.

## Pacotes Independentes e Desacoplados

Cada módulo (Auth, Container, Dashboard e Marketing) foi desenvolvido como um pacote independente, com suas próprias dependências e responsabilidades claras. Isso resulta em um sistema altamente desacoplado, permitindo o desenvolvimento, manutenção e escalabilidade eficientes de cada módulo.

## Como Executar o Projeto

1. Clone este repositório para sua máquina local.
2. Navegue até o diretório do projeto e, para cada pacote (Auth, Container, Dashboard e Marketing), execute `npm install` ou `yarn` para instalar as dependências.
3. Para iniciar cada módulo, utilize comandos como `npm run start` ou `yarn start`.
4. Abra seu navegador e acesse as URLs correspondentes aos diferentes módulos para visualizá-los em ação.

## Personalização e Expansão

Sinta-se à vontade para explorar, personalizar e expandir este projeto de acordo com suas necessidades específicas. A arquitetura de Microfrontends oferece flexibilidade e escalabilidade, e a busca contínua por melhores práticas de desenvolvimento será fundamental para o sucesso contínuo deste projeto.
