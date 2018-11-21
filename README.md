README.md# estudante
<p align = "center">
  <a href="https://cakephp.org/" target="_blank">
    <img alt = "CakePHP" src = "https://cakephp.org/v2/img/logos/CakePHP_Logo.svg" width = "400" />
  </a>
</ p>
<p align = "center">
    <a href="LICENSE" target="_blank">
        <img alt = "Licença de software" src = "https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square">
    </a>
    <a href="https://travis-ci.org/cakephp/cakephp" target="_blank">
        <img alt = "Status da compilação" src = "https://img.shields.io/travis/cakephp/cakephp/master.svg?style=flat-square">
    </a>
    <a href="https://codecov.io/github/cakephp/cakephp" target="_blank">
        <img alt = "Status da cobertura" src = "https://img.shields.io/codecov/c/github/cakephp/cakephp.svg?style=flat-square">
    </a>
    <a href="https://squizlabs.github.io/PHP_CodeSniffer/analysis/cakephp/cakephp/" target="_blank">
        <img alt = "Consistência de código" src = "https://squizlabs.github.io/PHP_CodeSniffer/analysis/cakephp/cakephp/grade.svg">
    </a>
    <a href="https://packagist.org/packages/cakephp/cakephp" target="_blank">
        <img alt = "Total de downloads" src = "https://img.shields.io/packagist/dt/cakephp/cakephp.svg?style=flat-square">
    </a>
    <a href="https://packagist.org/packages/cakephp/cakephp" target="_blank">
        <img alt = "Última versão estável" src = "https://img.shields.io/packagist/v/cakephp/cakephp.svg?style=flat-square&label=stable">
    </a>
</ p>

[CakePHP] (https://cakephp.org) é um framework de desenvolvimento rápido para PHP que
usa padrões de design comumente conhecidos, como Dados Associativos
Mapeamento, Front Controller e MVC. Nosso principal objetivo é fornecer uma estrutura
framework que permite que usuários PHP em todos os níveis desenvolvam rapidamente
aplicações, sem qualquer perda de flexibilidade.

## Instalando o CakePHP via Composer

Você pode instalar o CakePHP no seu projeto usando
[Composer] (https://getcomposer.org). Se você está começando um novo projeto, nós
recomendo usar o [esqueleto de aplicativo] (https://github.com/cakephp/app) como
um ponto de partida. Para aplicativos existentes, você pode executar o seguinte:

`` `bash
$ composer requer cakephp / cakephp: "~ 3.6"
`` `

## executando testes

Supondo que você tenha PHPUnit instalado em todo o sistema usando um dos métodos indicados
[aqui] (https://phpunit.de/manual/current/en/installation.html), você pode executar o
testes para o CakePHP, fazendo o seguinte:

1. Copie `phpunit.xml.dist` para` phpunit.xml`.
2. Adicione as credenciais relevantes do banco de dados ao seu `phpunit.xml` se quiser executar testes
   uma fonte de dados não-SQLite.
3. Execute o `phpunit`.

## Alguns links úteis

* [CakePHP] (https://cakephp.org) - O framework PHP de desenvolvimento rápido.
* [CookBook] (https://book.cakephp.org) - A documentação do usuário do CakePHP; comece a aprender aqui!
* [API] (https://api.cakephp.org) - Uma referência às aulas do CakePHP.
* [Awesome CakePHP] (https://github.com/FriendsOfCake/awesome-cakephp) - Uma lista de recursos em destaque ao redor do framework.
* [Plugins] (https://plugins.cakephp.org) - Um repositório de extensões para o framework.
* [The Bakery] (https://bakery.cakephp.org) - Dicas, tutoriais e artigos.
* [Centro Comunitário] (https://community.cakephp.org) - Uma fonte para tudo relacionado à comunidade.
* [Treinamento] (https://training.cakephp.org) - Participe de uma sessão ao vivo e seja qualificado com a estrutura.
* [CakeFest] (https://cakefest.org) - Não perca a nossa conferência anual CakePHP.
* [Cake Software Foundation] (https://cakefoundation.org) - Promovendo o desenvolvimento relacionado ao CakePHP.

## Obtenha suporte!

* [Slack] (https://cakesf.herokuapp.com/) - Junte-se a nós no Slack.
* [#cakephp] (https://webchat.freenode.net/?channels=#cakephp) em irc.freenode.net - Venha conversar conosco, temos bolo.
* [Fórum] (https://discourse.cakephp.org/) - Fórum oficial do CakePHP.
* [Problemas do GitHub] (https://github.com/cakephp/cakephp/issues) - Tem problemas? Por favor nos conte!
* [Roadmaps] (https://github.com/cakephp/cakephp/wiki#roadmaps) - Quer contribuir? Se envolver!

## Contribuindo

* [CONTRIBUTING.md] (. Github / CONTRIBUTING.md) - Dicas rápidas para contribuir com o projeto CakePHP.
* [Seção "Contribuindo" do "CookBook"] (https://book.cakephp.org/3.0/en/contributing.html) - Detalhes sobre como contribuir com o projeto.

# Segurança

Se você encontrou um problema de segurança no CakePHP, por favor use o seguinte procedimento ao invés do sistema normal de relatório de erros. Em vez de usar o bug tracker, lista de discussão ou IRC, por favor envie um email para security [at] cakephp.org. E-mails enviados para este endereço vão para a equipe principal do CakePHP em uma lista de discussão privada.

Para cada relatório, tentamos primeiro confirmar a vulnerabilidade. Uma vez confirmada, a equipe do CakePHP executará as seguintes ações:

- Confirme ao repórter que recebemos o problema e estamos trabalhando em uma correção. Pedimos que o repórter mantenha o assunto confidencial até que o anunciemos.
- Consiga uma correção / patch preparado.
- Prepare uma postagem descrevendo a vulnerabilidade e as possíveis explorações.
- Libere novas versões de todas as versões afetadas.
- Destaque o problema no anúncio de lançamento.
