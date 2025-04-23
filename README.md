# Atividade Avaliativa de Git e GitHub
Repositório da Atividade Avaliativa

OBJETIVOS
- Criar uma conta e um repositório no GitHub.
- Clonar um repositório do GitHub.
- Usar comandos básicos do Git (clone, add, commit, push, pull).
- Criar branches.
- Resolver conflitos simples.
- Colaborar com colegas via pull request (opcional).

TAREFAS
- Configuração do Ambiente
Cada estudante deve criar uma conta no GitHub.
Instalar o Git (caso ainda não tenham).
Configurar o Git com nome e e-mail (confira o documento com o passo a passo https://docs.google.com/document/d/1uS0v9qxtonRNHNgMVorz8jwO_YQxgH2riGnuM2qsb8Q/edit?usp=drive_link).
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"

- Criação de um Repositório
Estou compartilhando um repositório no GitHub com vocês. Contém apenas um README.md e um arquivo txt.
Link do repositório: 
https://github.com/brunoacre/atividadeiniciallaw.git 
Alunos devem fazer fork do repositório e clonar para a máquina local:
Fazer o fork no GitHub.
git clone https://github.com/seuusuario/repositorio.git

- Atualização do Arquivo
Cada aluno deve criar uma branch com seu nome:
git checkout -b nome-do-aluno
Editar o arquivo alunos.txt, adicionando seu nome. Com o arquivo editado adicionar no git, fazer commit e subir para o repositório. 	
git add alunos.txt
git commit -m "Adicionando nome do aluno"
git push origin nome-do-aluno

ENTREGAS
- Entregar um documento no Sigaa com o seu nome completo e o link do seu repositório (deve ser público). Pode ser um comentário na atividade, se preferir.
- Data limite para entrega: 09/05/2025
- Sugestão: faça o seu resumo de passos do Git e GitHub para usar sempre! 

