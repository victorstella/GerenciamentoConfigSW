Victor Daniel Stella - Paiva GRR20200234  
Vinicius Yoshida - GRR20190475  

# GerenciamentoConfigSW

Observação: nossos ambientes locais ja estavam com o git configurado  

Comandos realizados:  

### Victor

echo "# GerenciamentoConfigSW" >> README.md  
git init  
git add README.md  
git status  
git commit -m "first commit"  
git branch -M main  
git remote add origin git@github.com:victorstella/GerenciamentoConfigSW.git  
git push -u origin main  

### Vinicius

git clone https://github.com/victorstella/GerenciamentoConfigSW.git  
git branch local  
git checkout local  
git add .  
git commit -m "..."  
git push  
git checkout main  
git merge local  

### Victor

git checkout -b new-feature  
mkdir node_modules  
cd node_modules  
touch file.txt  
cd ..  
git add .  
git commit -m "new feature added"  
git pull  
git push --set-upstream origin new-feature  
git checkout main  

Pull request criado manualmente através da interface web, da branch new-feature para a main, feito o merge e a branch new-feature foi deletada.  

touch .gitignore  
echo "node_modules" >> .gitignore  
git add .  
git commit -m ".gitignore criado"  
git pull  
git push  
