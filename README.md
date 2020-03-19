# Segurança da Informação

### Integrantes do Grupo

* Leandro Lopes (Master)
* Murilo Leme
* Matheus Henrique
* Guilherme Rodrigo
* Mônica Torres

### Proposta

Tendo como referência a disponibilidade das informações para um usuário, dentro da nova [LGPD](http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/L13709.htm), a ideia é mapear bancos de dados (Postgresql) disponibilizando a opção de geração de relatórios contendo todas as informações e métricas que o sistema possui relacionadas ao usuário.

### Observações

Requisito da LGPD: O usuário deve ter acesso aos seus dados a qualquer momento.

Proposta: Mapear em busco de todas as informações de um usuário respectivo.

Problema: Os dados podem estar criptografados, qual o impacto nas querys?

### Entregas

1. (18/03) Estrutura genérica do banco de dados com o requisitos necessários,
dentro das normas da LGPD, contendo um algoritmo de conexão.

2. (10/04) Banco de dados estruturado, conexão com o banco através da aplicação para extração de dados.
Definição dos itens que irão compor o relatório.

3. (24/04) Exemplo de relatório inicial, início da implementação do método de criptografia dos dados no banco
dentro da aplicação.

4. (08/05) Exemplo de relatório final implementado.

5. (22/05) Algoritmo de criptografia bidirecional completo e integrado as funcionalidades do sistema.

6. (05/06) Documentação completa e atualizada de acordo com as usabilidades e requisitos da aplicação, testes de software.

7. (15/06) Algoritmo de mapeamento funcionando, capaz de descriptografar dados
sensíveis, desde que seja passado a chave de criptografia do usuário e as credenciais
do banco. Como resultado, ele emitirá um relatório de tudo encontrado.

### Relatórios de Entrega

[Entrega 1](https://github.com/LLBueno/seguranca-informacao/blob/master/docs/1entrega.md)

