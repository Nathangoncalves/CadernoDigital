- Foi desenvolvido com o objetivo de aprimorar as versoes [[HTML]] anteriores e resolver alguns problemas de compatibilidade entre navegadores. 
- Foi feito para ser simples, implicando uma sintexe extremamente mais simples e limpa. A simples declaracao do tipo de documento [[DOCTYPE]] foi apenas mais uma das facilidades incluidas na nova versao. Agora voce precisa apenas um <!DOCTYPE html:> no inicio do seu documento, e tudo estara pronto. 
``` html 
<!DOCTYPE html> 
```
- Sintexe do [[HTML5]] e compativel tambem com [[HTML4]] e [[XHTML1]]. 
- A linguagem apresenta uim novo elemento, o 
``` html 
<canvas>
```
- Responsavel por substituir muitas das implementacoes antes feitas em Flash. Isso faz muitos desenvolvedores considerarem que ja se encontra obsoleto e futuramente morto.
- A extensao de _[[tags]]_ a um tool de novos e interessantes recursos fez uma grande diferenca na linguagem. 
- _Tags_ como: 
  ``` html
- <header> e <footer>
  ```
- Que estendem a funcionalidade de tabelas agora na pagina como um todo, como:
``` html
<section>, <article> e <nav>
```
- Que permitem marcar areas especificas dos _layouts_, como:
``` html
<video> e <audio>
```
- Para uma inclusao melhorada de conteudos multimidas nas paginas, e 
  ``` html
<menu> e <figure>
```
- Para bem arranjar textos, imagens e menus, trazem todo um conjunto de implementacoes e funcionalidades bem-pertinentes para Web de hoje.
- Alem disso tudo, a remocao de outros recursos, como as _[[tags]]_ abaixo:
``` html
<center>, <big> e <font>, etc
``` 
- fazem com que a [[responsabilidade]] do CSS aliada a nova linguagem so aumente, otimizando o desenvolvimento [[front-end]]. 
- Como todas as versoes anteriores do padrao [[HTML]], os navegadores [[HTML5]] sao compativeis com versoes anteriores. 
- As paginas mais antigas continuam sendo exibidas em novos navegadores, e nao sera necessario, reescrever nenhum documento existente.
-  O mais novo recurso do [[HTML5]] e o suporte nativo para producao de audio e video no navegador. 
- Os navegadores atuais contam com [[plug-ins]], como Adoble Flash, Apple Quick Time e Microsoft Silverlight, para reproduzir conteudo multimidia.
- Para usuarios de _desktop_, esse [[plug-ins]] funcionam bem e sao relativamente transparentes de usar; para crescente numero de usuarios que deseja assitir a videos em seus iPhones, IPads ou Blackberries, nao ha [[plug-ins]] disponiveis.
 
 - **Audio e Video**

- O HTML5 resolveu o problema do _plug-in_, exigindo suporte interno para video em navegadores e permitindo que os designers insiram as [[tags]]
``` html
<video> e <audio>
``` 
- em suas paginas.
- Essas _tags_ contem informacoes que o navegador pode usar para interpretar e rendenizar o conteudo multimida.
- Observe o exemplo a seguir, que demonstra o uso do elemento [[audio]] 
``` html
<audio src="som.mp3">
</audio>
```
- somente isso, simples e direto sem a necessidade de _plug-ins_, Flas, Quick Time, Windows Media Player e qualquer outro sistema a ser considerado quando se pretende incorporar som em uma pagina Web. 
- Basta declarar o caminho para o arquivo do som no atributo [[src]] do elemento. O som e reproduzido com as funcionalidades nativas do navegador.
- O elemento [[audio]] admite os seguintes atributos:
	- atributos globais, [[src]], [[controls]] [[crossorign]], [[preload]], [[autoplay]], [[mediagroup]], [[loop]], e [[muted]].

- **Graficos e Efeitos em 3D**