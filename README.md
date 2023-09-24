# GerenciamentoConfigSW

Observação: nossos ambientes locais ja estavam com o git configurado  

Comandos realizados:  

Victor

echo "# GerenciamentoConfigSW" >> README.md  
git init  
git add README.md  
git status  
git commit -m "first commit"  
git branch -M main  
git remote add origin git@github.com:victorstella/GerenciamentoConfigSW.git  
git push -u origin main  

Vinicius

git clone https://github.com/victorstella/GerenciamentoConfigSW.git  
git branch local  
git checkout local  
git add .  
git commit -m "..."  
git push  
git checkout main  
git merge local  
