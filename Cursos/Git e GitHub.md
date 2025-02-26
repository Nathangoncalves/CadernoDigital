**Git:** Sistema de Controle de Versão que rastreia qualquer alteração que você fizer ao longo do tempo

**O que é controle de versão?** 
- Permite que você controle as mudanças feitas no código, registra quem fez, o que fez e possibilita que volte para versões anteriores caso seja necessário. 

**Git** README.md
- Funciona por meio de repositórios. 
- Um repositório é uma pasta que controla minhas diffs (mudanças). - *é tipo uma linha do tempo*
- Quando é feito uma alteração no código, o git registra isso como um commit. - *adiciona um ponto na linha do tempo*
- Isso permite que você rastreie as alterações e trabalhe em conjunto com outras pessoas sem que perca seu trabalho. 

**git init:** é como se você tivesse criado um universo e começa a rastrear os arquivos e anotar todos os pontos na história dele.

*"Todo universo precisa de uma galáxia para existir e essa galáxia é o GitHub"*

**GitHub**
- Hospeda seus repositórios git 

	**git add (nome do arquivo.js)** - aqui estamos adicionando esses arquivos as alterações do git 
	**git commit -m "mensagem"** - adiciona uma mensagem a minha *"linha do tempo"*
	**git branch -m (novo nome ao meu universo)** - renomeando o universo 
	**git remote add origin (link do repositório)** - adicionando um repositório remoto *"informando para o git a onde meu código vai ficar"* 
	**git push -u origin (nome do universo)** - subindo meu código para o GitHub

	 *o universo agora existe em dois lugares, na galáxia e na nossa máquina*
	- A galáxia é chamada de remote (demos o apelido de origin para ela). *registra o repositório a onde vai ficar salvo o seu código lá no GitHub*
	
*quando eu decido mudar algo dentro do código e quero que fique salvo aquilo para sempre na minha linha do tempo, o que eu faço?*

**git add (nome do arquivo.js)**
**git commit -m "Mensagem que vai ficar junto ao meu ponto na história da linha do tempo"**
**git push** 

**MERGE (ou git merge)** - Mesclar códigos em diferentes branches (universos) - *isso é algo que grandes times fazem (meio que cria um universo paralelo e faz com que o principal absorva o paralelo)*

teste teste