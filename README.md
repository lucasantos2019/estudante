README.md#
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


