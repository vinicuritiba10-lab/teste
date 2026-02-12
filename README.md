# teste

#COMANDOS BASICOS

  
  git init - inicializa um novo repositório Git e começa a acompanhar um diretório existente. Ele adiciona uma subpasta oculta dentro do diretório existente que contém a estrutura de dados interna necessária para o controle de versão.
  
  
  git clone - cria uma cópia local de um projeto que já existe remotamente. O clone inclui todos os arquivos, histórico e branches do projeto.
  
  
  git add prepara uma alteração. O Git controla as alterações na base de código de um desenvolvedor, mas é necessário testar e tirar um instantâneo das alterações para incluí-las no histórico do projeto. Este comando executa o teste, a primeira parte do processo de duas etapas. Todas as mudanças que são testadas irão tornar-se parte do próximo instantâneo e parte do histórico do projeto. O teste e o commit separados dão aos desenvolvedores total controle sobre o histórico do seu projeto sem alterar como eles codificam e funcionam


  git commit salva o instantâneo no histórico do projeto e conclui o processo de controle de alterações. Em suma, um commit funciona como tirar uma foto. Qualquer item que tenha sido preparado com git add passará a fazer parte do instantâneo com git commit.


  git status mostra o status das alterações como não controladas, modificadas ou preparadas


  git branch mostra os branches que estão sendo trabalhados localmente.


  git push atualiza o repositório remoto com todos os commits feitos localmente em um branch.


#CRIAÇÃO DE UM NOVO REPOSITORIO


git init my-repo


cd my-repo


touch README.md


git add README.md


git commit -m "add README to initial commit"


git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git


#OQUE SAO BRANCHS


As branches são versões separadas de um projeto.
Para que servem: Você cria uma "branch" (ramo) para testar uma ideia nova sem estragar o código principal que já funciona. Se der certo, você junta as duas no final.





