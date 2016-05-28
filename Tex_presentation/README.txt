font 
Monospace 14


couleur dans lst listing 

listing dans le texte


git log --pretty=format:"%h - %an, %ar : %s"

git config --global pretty.joli "%h%x09%an%x09%ad%x09%s"
git config --global alias.lg ' log --pretty=format:"%h%x09%an%x09%ad%x09%s"'

cadiou@moon: [master] ~/Documents/2016/Tex_cours_GIT_2016/Tex_presentation/TESTS/demo$ git config --global alias.llg 'log --pretty=format:"%h%x09%an%x09%ad%x09%s"'

Workflow

http://git-scm.com/about/distributed

=====================================

git fetch (pas présenté) - différence avec git pull

git remote -t remotes/origin/toto

git remote show origin

=====================================

http://latexcolor.com/
