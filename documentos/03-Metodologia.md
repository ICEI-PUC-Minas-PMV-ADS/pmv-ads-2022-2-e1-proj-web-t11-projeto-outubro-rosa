
# Metodologia

A metodologia contempla as definições de ferramental utilizado pela equipe tanto para a manutenção dos códigos e demais artefatos quanto para a organização do time na execução das tarefas do projeto.

## Controle de Versão

Os artefatos do projeto são desenvolvidos a partir de diversas plataformas e a relação dos ambientes com seu respectivo propósito é apresentada na tabela que se segue. 

![Captura de Tela (359)](https://user-images.githubusercontent.com/117127986/204016239-0a142d15-9ef1-4fab-9491-3af836bd4a76.png)

## Gerenciamento de Projeto

A equipe utiliza metodologias ágeis, tendo escolhido o Scrum como base para definição do processo de desenvolvimento.

Para organização e distribuição das tarefas do projeto, a equipe está utilizando o GitHub Project  estruturado com as seguintes listas: 

    • Backlog: recebe as tarefas a serem trabalhadas e representa o Product Backlog. Todas as atividades identificadas no decorrer do projeto também devem ser incorporadas a esta lista.
        
    • To Do: Esta lista representa o Sprint Backlog. Este é o Sprint atual que estamos trabalhando.
    
    • Doing: Quando uma tarefa tiver sido iniciada, ela é movida para cá.
    
    • Done: nesta lista são colocadas as tarefas que passaram pelos testes e controle de qualidade e estão prontos para ser entregues ao usuário. Não há mais edições ou revisões necessárias, ele está agendado e pronto para a ação.
    
O quadro kanban do grupo desenvolvido na ferramenta de gerenciamento de projetos está disponível através da URL https://github.com/orgs/ICEI-PUC-Minas-PMV-ADS/projects/211/views/1 e é apresentado, no estado atual, na Figura 2.



![image](https://user-images.githubusercontent.com/117127986/204019362-fbfa5b1e-2235-4db6-ae6c-3c2b2d39fd76.png)

Figura  2    

### Divisão de Papéis

A equipe está organizada da seguinte maneira:

    • Scrum Master:
    
       Livia Rosa Castanheira
       
    • Product Owner: 
    
      Paloma Borges de Souza Pereira 
      
    • Equipe de Desenvolvimento
    
      Rafael dos Santos Rodrigues
      
    • Equipe de Design
    
      Kenio Portes Nascimento
      

### Processo

Projeto de interface


No projeto de interface focamos para que o site tenha funcionalidade, usabilidade e acessibilidade. O projeto busca facilitar a interação do usuário bem como acesso às informações e compartilhamento

FLUXO DO USUÁRIO

O fluxograma a seguir mostra a interação do usuário no site conforme a figura 3: 

![image](https://user-images.githubusercontent.com/117127986/204020821-c8612135-a7bd-4b03-bcbd-8300f00efffd.png)
                                     Figura 3
                                     
WIREFLAME 

Conforme o fluxo do projeto de interface, o design das páginas seguirá uma estrutura comum com 3 blocos descritos a segu:

° Cabeçalho: local onde estão dispostos o menu de navegação, logo do site.

° Conteúdo: mostra o conteúdo da página, bem como os temas mais relevantes.

° Barra lateral: apresentação de conteúdos extras, links, fontes, etc. 

![image](https://user-images.githubusercontent.com/117127986/204021474-ce2289d2-0a8f-4caa-b77d-ef660b66f731.png)
                                            Figura 4
 
 TELA HOME-PAGE

A tela de  Home-Page  mostra noticias em destaque, sobre os temas principais.
Com base na estrutura padrão, o bloco de conteúdo  traz  os informativos em destaque , o bloco da barra lateral tras  dois elementos distintos:

° Componentes de pesquisa que permite substituir o conteúdo da pagina com o resultado da busca  solicita pelo usuár;

° Componentes de lista de categorias  que da  acess as paginas  de cada uma das sessoes  disponibilizadas.

![Captura de Tela (361)](https://user-images.githubusercontent.com/117127986/204024099-2ccb9c7f-58a5-4de5-9ef5-7047b2624902.png)


TELA – NOTÍCIAS DE CATEGORIAS 

A tela de notícias de categorias apresenta, no Bloco de Conteúdo, as notícias referentes a uma categoria específica, escolhida pelo usuário. 

    • Componentes de Link’s no canto inferior direito da página, permite substituir o conteúdo da página, navegando por todas as categorias disponíveis. 
    • Componentes de compartilhamento permite o compartilhamento de conteúdo em redes sociais.  
    • Componentes de Link’s permite que o usuário seja direcionado aos sites oficiais, podendo checar a fonte dos informe. 


![image](https://user-images.githubusercontent.com/117127986/204029818-35b39137-b96a-46cc-97b0-d24f1bd5ccad.png)

![image](https://user-images.githubusercontent.com/117127986/204029922-9ba5224b-446d-4fb1-bbe1-06e2a5758f7c.png)

![image](https://user-images.githubusercontent.com/117127986/204030037-dbc56934-7ce1-4919-aa86-67043836150c.png)

![image](https://user-images.githubusercontent.com/117127986/204030312-5fe591f2-97f7-459b-8936-f43201a16aac.png)

![image](https://user-images.githubusercontent.com/117127986/204030361-8514280e-f33b-4441-a4e5-855395b18fff.png)

![image](https://user-images.githubusercontent.com/117127986/204030445-6bd159a4-608d-4654-ad3c-35fe34ea858f.png)

![image](https://user-images.githubusercontent.com/117127986/204030466-21b7caf2-8e19-46f5-92f0-460a4a7e7213.png)

![image](https://user-images.githubusercontent.com/117127986/204030511-b24d53c6-a19f-4127-8514-d0d8011c32da.png)

TELA – Resultado de Pesquisa 

Assim que o usuário informa um tópico de pesquisa, ao clicar no botão OK, ele é direcionado para uma tela que traz a relação de notícias associadas ao tópico informado. 
Este resultado é apresentado na figura a seguir: 

![image](https://user-images.githubusercontent.com/117127986/204030577-a94ff46c-d60a-47d8-886e-ca40df8d514a.png)






### Ferramentas

Arquitetura de solução 

Nesta seção são apresentados os detalhes técnicos da solução criada pela equipe, tratando dos componentes que fazem parte da solução e do ambiente de hospedagem da solução.

Diagrama de Componentes

Os componentes que fazem parte da solução são apresentados na Figura que se segue.


![image](https://user-images.githubusercontent.com/117127986/204031021-ba102b5b-0922-493a-97dc-f56b5486883e.png)
                               fIGURA  5


A solução implementada conta com os seguintes módulos:

    • Navegador - Interface básica do sistema
    
    • Páginas Web - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
    
    • Local Storage - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
   
        • Canais - seções de notícias apresentada
        
        •  NORI Comentários - registro de opiniões dos usuários sobre as  noticias.
        
    • Preferidas - lista de notícias mantidas para leitura e acesso posterior 
    
        • News API - plataforma que permite o acesso às notícias exibidas no site.
       
    • Hospedagem - local na Internet onde as páginas são mantidas e acessadas pelo navegador.  
    
    Hospedagem
    
    O site utiliza a plataforma GitHub como ambiente de hospedagem do site do projeto. O site é mantido no ambiente da URL: 

https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t11-projeto-outubro-rosa
A publicação do site no GitHub é feita por meio de uma submissão do projeto (push) via git para o repositório remoto que se encontra no endereço:

https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t11-projeto-outubro-rosa


