# O que é o Cypress e para que serve?
O Cypress é uma ferramenta de automação de testes para aplicações web, tornando mais fácil configurar, escrever, executar e depurar testes. Muitas vezes é comparado ao Selenium, mas difere fundamentalmente e arquitetonicamente, oferecendo testes mais rápidos, fáceis e confiáveis. 
Cypress suporta testes ponta a ponta, de componentes, de integração e de unidade, rodando diretamente no navegador. Inclui recursos como espera automática, auxílio à depuração e a capacidade de controlar o tráfego de rede para testar casos extremos sem um servidor. Ou seja, ele oferece uma experiência de desenvolvimento intuitiva e rápida, permitindo que você escreva testes em JavaScript de forma simples e eficaz.

#### Alguns exemplos de uso:
- Validar a interação do usuário, testando se os elementos da interface estão funcionando como esperado, como botões, links, formulários e outros componentes.
- Verificar o comportamento da aplicação, testando se a aplicação está respondendo corretamente às ações do usuário, como navegação, envio de dados e APIs.
- Depurar testes visualmente, visto que oferece ferramentas de depuração visual que facilitam a identificação de problemas nos seus testes.
- Executar testes automaticamente pois pode ser integrado ao seu pipeline de integração contínua para garantir que sua aplicação esteja sempre funcionando como esperado.

<br>

# Vantagens e desvantagens do Cypress em relação a outras ferramentas de teste.
#### Vantagens:
- Ferramenta intuitiva que pode ser utilizada por desenvolvedores com diferentes níveis de experiência em testes.
- É executado diretamente no navegador, o que torna os testes muito mais rápidos do que outras ferramentas.
- Oferece uma experiência de teste estável e confiável.
- Pode ser usado para testar aplicações web complexas com diferentes frameworks e tecnologias.
- É uma ferramenta de código aberto, ou seja, você pode contribuir para o seu desenvolvimento e usá-la gratuitamente.

#### Desvantagens do Cypress:
- Ferramenta relativamente nova, o que significa que ainda não possui todos os recursos de outras ferramentas de teste mais maduras.
- A comunidade do Cypress ainda é menor do que a de outras ferramentas de teste, o que significa que pode ser mais difícil encontrar ajuda e suporte.
- Suporte a um número limitado de navegadores, como Chrome, Firefox e Edge.

### Principais diferenças entre o Selenium e o Cypress
![image](assets/6.Selenium%20vs%20Cypress.png)

<br>

# Arquitetura do Cypress.
Diferente de ferramentas como Selenium, que opera externamente ao navegador, o Cypress executa diretamente dentro do navegador. Isso permite que o Cypress manipule o comportamento do navegador em tempo real, alterando o DOM e as requisições e respostas de rede à medida que ocorrem, oferecendo controle completo sobre a aplicação tanto na frente quanto nos bastidores.

<br>

# Seletores de elementos no Cypress.
O Cypress utiliza jQuery para facilitar a seleção de elementos, permitindo aos usuários identificar facilmente elementos do DOM para interações de teste. Isso simplifica a navegação na árvore do DOM e a manipulação de elementos para realizar testes eficientes.

<br>

# Comandos e asserções no Cypress.
Cypress oferece uma vasta gama de comandos e asserções inbuilt que permitem interagir com a aplicação, como clicar em elementos, digitar em campos de entrada, verificar a presença de elementos, e muito mais. Estes comandos são projetados para serem intuitivos e fáceis de usar, reduzindo a necessidade de escrever código complexo.

<br>

# Descrição das etapas de preparação de um testes de interface, execução e verificação no Cypress.
- Preparação: inicie configurando o ambiente de teste, o que inclui a instalação do Cypress e a configuração dos testes a serem executados.
- Execução: utilize os comandos do Cypress para interagir com a aplicação, como visitar uma página, clicar em botões, digitar em campos de texto, etc.
- Verificação: aplique asserções para verificar se o estado da aplicação está conforme esperado após a execução dos comandos. Isso pode incluir verificar textos, estados de elementos, entre outros.

<br>

# Como estruturar testes de forma eficiente no Cypress?
- Organize os testes em suítes de teste por funcionalidade ou área da aplicação;
- Utilize 'describe' e 'it' para criar uma estrutura legível e organizada;
- Aplique asserções claras e concisas para validar a lógica de negócios;
- Reaproveite o código através de comandos personalizados ou funções de ajuda para evitar repetições;
- Mantenha os testes isolados, garantindo que cada teste possa ser executado de forma independente;
- Utilize dados de teste dinâmicos e configuráveis para cobrir diferentes cenários de teste;