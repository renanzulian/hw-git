# Hello World GIT

## Content

Hi folks!    
Here you can access and to download a apresentation explaing how Git works. You will see:

- System control version GIT

- Plataforms that use GIT

- Difference between Git and GitHub/GitLab

- How commit works

- What is branches and how you can use branches

- Best practices to use git

## How to install and configure git

- Instalar o git    
	sudo apt install git

- Configurando usuário e e-mail do git local      
	git config --global user.name "Seu Nome"      
	git config --global user.email "seu_email@email.com"        

- Gerar a chave SSH     
	ssh-keygen -t rsa -C "seu_email@email.com"      

- Insira sua chave na plataforma desejada (GitLab para esse tutorial)      
	gedit ~/.ssh/id_rsa.pub 	(Abre um txt com sua SSH)      
	ssh -T git@gitlab.com 	(Teste para verificar se esta funcionando)      