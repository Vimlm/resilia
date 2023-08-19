# Projeto de Banco de Dados para Gerenciamento da Estrutura de Ensino

Este é um projeto de banco de dados desenvolvido para modernizar o processo de armazenamento de dados da área de ensino da Resilia. O projeto visa criar uma solução eficaz para gerenciar informações sobre estudantes, facilitadores, turmas, módulos e cursos. A estrutura do banco de dados foi elaborada para permitir o armazenamento, recuperação e análise de informações relevantes para a tomada de decisões estratégicas.

## Contexto

Os dados da área de ensino da Resilia estão atualmente dispersos em diferentes planilhas, dificultando a extração de informações estratégicas. Este projeto visa centralizar esses dados em um banco de dados relacional, proporcionando uma visão holística da estrutura de ensino da empresa.

## Estrutura do Banco de Dados

O banco de dados foi projetado com as seguintes entidades principais:

- endereços              	
- disciplina
- estados 			
- curso
- pessoas			
- status_estudante
- estudantes			
- modulo
- facilitador 			
- disciplina_modulo	
- turma				
- facilitador_turma
- estudante_turma

As tabelas foram estruturadas de maneira a refletir as relações entre essas entidades, utilizando chaves primárias e estrangeiras para manter a integridade dos dados.

## Etapas do Projeto

1. **Modelagem do Banco de Dados:** Foram definidas as entidades, atributos e relacionamentos com base nos requisitos do projeto.

2. **Scripts SQL:** Foram criados scripts SQL para criar as tabelas, definir as chaves e inserir dados de exemplo.

3. **Consultas Estratégicas:** Foram elaboradas consultas SQL para responder às perguntas estratégicas do projeto, como a quantidade de estudantes, facilitadores por turma e porcentagem de estudantes com status de evasão.

4. **View de Evasão por Turma:** Uma view foi criada para facilitar o cálculo da porcentagem de estudantes com status de evasão por turma.

5. **Trigger para Atualização de Status:** Foi implementado um trigger que registra em uma tabela de log sempre que o status de um estudante é atualizado.

## Como Iniciar o Projeto

Siga as etapas abaixo para configurar e executar o projeto:

### Configuração e Execução do MySQL

1. Certifique-se de ter um servidor MySQL instalado e configurado.

2. Crie um novo banco de dados chamado `resilia`.

3. Execute os scripts SQL fornecidos no arquivo `scripts.sql` para criar as tabelas e inserir os dados de exemplo.

4. Utilize as consultas SQL para obter insights estratégicos do banco de dados.

### Execução do MySQL via Docker

Para simplificar o processo de configuração do ambiente, você também pode executar o MySQL via Docker. Siga os passos abaixo:

	1. Certifique-se de ter o Docker instalado em seu sistema.

	2. Abra um terminal e navegue até o diretório raiz do projeto.

	3. Construa a imagem Docker do banco de dados executando o seguinte comando:

4. Inicie o contêiner MySQL com Docker Compose:

5. Verifique o status dos contêineres em execução:

6. Copie o ID do contêiner associado ao nome "bd_resilia".

7. Execute o contêiner utilizando o ID copiado no passo anterior:

8. Dentro do contêiner, crie uma nova conexão no MySQL com a porta 3309 e a senha "root".

9. Inicie o MySQL nessa nova conexão.

10. Agora você pode usar os scripts SQL fornecidos no arquivo `scripts.sql` para criar as tabelas e inserir os dados de exemplo.

---

## Contribuições

Este projeto foi desenvolvido com base nos requisitos do cliente e pode ser modificado e aprimorado. Se você desejar contribuir com melhorias, correções ou novas funcionalidades, sinta-se à vontade para fazer um fork deste repositório, fazer suas alterações e enviar um pull request.

## Contato

Para mais informações sobre este projeto ou para qualquer dúvida relacionada, entre em contato com:

Rafael Fantin
E-mail:rffantin@gmail.com
GitHub:https://github.com/rffantin 

Lucio Martins
E-mail:luciomartinsdw@gmail.com
GitHub:https://github.com/LucioMartinsDw

Felipe Gomes:
E-mail:felipesg03@gmail.com
GitHub:https://github.com/hellraiser997

Julyana K.
E-mail:
GitHub:

Victor Matheus 
E-mail:
GitHub:



---


