**Arquitetura Web - Unidade 1**

**Amazon:** A AWS é o serviço Web da Amazon. A empresa oferece opções de uso de seus servidores para usuários comuns utilizarem como repositório de arquivos, mas o forte é o serviço prestado às empresas e às intituições públicas e privadas.

**Microsoft:** A empresa fundada por Bill Gates nos anos de 1980, também expandiu seus serviços para a nuvem. Azure é a plataforma da Microsoft para a prestação desse mesmo tipo de serviço . Com ela, sistemas e dados podem ficar armazenados e acessíveis 24h por dia, todos os dias.

**IBM:** Não é apenas uma empresa de smartphones e equipamentos. Ela oferece serviços de cloud computing para usuários comuns (para armazenamento de arquivos como fotografias, vídeos, etc), mas também de serviços. - HUAWEI

**Serviços Oferecidos:** 
- Aplicativo em Nuvem. A Microsoft e a Google também oferecem seus aplicativos de e-mail e do tipo office (editor de texto, planilhas) como serviço online.
- **Serviços Inteligentes:**
	- Chatbots;
	- Assistentes Virtuais;
	- Inteligência Artificial;
	- Aprendizagem Máquina.
- **Alta Disponibilidade:**
	- Profissionais Capacitados sempre disponíveis.
	- DevOps
	- Automatização

**Ferramentas de Desenvolvimento Web**

*Características e Componentes da Arquitetura Web*

- Um Sistema baseado na web estará baseado na estrutura **cliente-servidor**, na qual a aplicação do lado cliente é a interface de comunicação com os dados, que, por sua vez, estarão "hospedados" ao lado do servidor.

![[Pasted image 20250227181325.png]]

- Pela internet, a comunicação acontece com o lado servidor, que é a hospedagem dos sistemas web e local onde os dados de um sistema são armazenados. Por meio de protocolos como o [[HTTP]]

*Ambiente Web*

- Em meados de 1990, Tim Berners-Lee era pesquisador nos laboratórios do CERN, a Organização Europeia para a Pesquisa Nuclear, com sede na Suíça. Foi por conta desse projeto que a comunicação de dados pela internet se tornou uma realidade e então:
	-  A partir das ideias de Tim Berners-Lee surgiu o conceito de hipertexto, que introduziu uma nova forma de organização da informação. Ele possibilita percorrer partes do documento (e outros documentos) por meio de ligações ou palavras que aparecem em destaque no texto, chamadas de hiperlinks ou links (MILLETO; BERTAGNOLLI, 2014, p. 6).
- Assim surgiu o conceito de hipermídia, o que tornou possível a criação de páginas web com outros elementos além de textos, como imagens, áudios e vídeos. Por meio então deste mecanismo, a troca de informações entre sistemas e dispositivos foi avançando. No princípio surgiram padrões de acesso, como os navegadores. Com os navegadores vieram outra necessidades, como linguagens e padronizações na criação de páginas web. 
- A linguagem de marcação de hipertexto simplesmente chamada de [[HTML]]

*Padrões de Arquitetura Web* 

- Existem diversas formas de estruturar servidores de aplicações web, mas todas elas se baseam na arquitetura cliente-servidor, na qual uma aplicação tem seus arquivos e dados armazenados em uma estrutura maior e mais robusta (lado servidor) e é acessada por interfaces web (lado cliente).

- **Arquitetura cliente-servidor**
	- O modelo da web é baseado no modelo utilizado desde os primórdios da web que é o **cliente servidor**. Com a expansão da capacidade dos computadores, diversas empresas passaram a disponibilizar servidores para terceiros, iniciando os chamados **servidores de hospedagem**
- **Arquitetura em três camadas**
	- Um sistema web tradicional é dividio em camadas (cada camada é uma separação de níveis, em que vão de usuário até o servidor web). Este modelo, divide cada uma dessas camadas como responsável por parte de uma aplicação web.
	- Essas três camadas são:
		- **Apresentação:** Trata-se da parte visual, a interface dos sistemas. Nesta camada, o usuário pode “navegar” e utilizar o sistema, interagindo, inserindo e requisitando dados por meio de formulários, botões e hiperlinks. Em geral, não processa muita informação, ou seja, não contém elementos mais profundos de regras de negócios do sistema. É responsável por requisitar dados dos servidores de dados e web.
		- **Lógica:** Camada onde se localizam as regras de negócio. Na prática são servidores de arquivos que hospedam as linguagens de programação chamadas de back-end. É a camada que requer maior poder computacional para permitir acesso de vários usuários ao mesmo tempo com distintas requisições.
		- **Dados:** A camada de gerenciamento de dados é onde ficam os bancos de dados. Requer uma maior segurança, visto que todos os dados do sistema e de seus usuários estão ali. Também são servidores com poder computacional de maior porte, principalmente, quanto à capacidade de armazenamento (storage), pois os dados aumentam em uma escala cada dia mais gigantesca.
		- Com a divisão de uma aplicação nas três camadas, a manutenção e possíveis melhorias em um sistema podem ser dividas dentro de uma equipe, com um ou mais membros responsáveis por uma parte delas, apenas. Já o usuário vê uma aplicação como um todo, sem a distinção entre as partes. Na prática o usuário so acessa um sistema web como se toda a estrutura fosse uma coisa só 
- **Arquitetura Monolítica**
	- Essa arquitetura também utiliza a arquitetura de camadas como forma de disponibilizar dados de uma aplicação desenvolvida.
	- Tem por característica dividir funcionalidades de um sistema em partes, porém, com um mesmo núcleo. 
	- A proposta da arquitetura monolítica é usar modelos como containers, cada um com a estrutura necessária para suportar uma aplicação por inteiro.
		- Sistemas do tipo ERP(enterprise resourse planning) são aplicações de grande porte. Esse tipo de sistema tem por caracteróstica ser modular, ou seja, cada parte do sistema é, ao mesmo tempo, independente, porém, integrada aos demais.