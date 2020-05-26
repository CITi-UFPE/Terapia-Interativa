# Terapia Interativa
Repositório para agregar todas as provas de conceito (do inglês, POC) necessárias para a documentação técnica. Para mais informações sobre essa documentação, por favor visite a [página no Notion](https://www.notion.so/citiufpe/Documenta-o-T-cnica-e3546b617c4148c6883c48124cbc847a).

## API de vídeo chamadas
Para essa POC, a API utilizada na vídeo chamada foi a da [Vonage](https://www.vonage.com/communications-apis/video/?icmp=l3nav_overview_novalue).

### Como rodar a POC
Rode o arquivo Video_API/index.html. Talvez seja necessário esperar um pouco e ceder permissão para o app ter acesso ao seu microfone e sua câmera. Depois disso, você deve ter uma grande tela cinza e uma pequena tela com a imagem da sua câmera. Mantenha essa aba do navegador aberta e faça o mesmo processo novamente (é recomendado que outra pessoa tenha acesso aos arquivos, para que possa ser comprovado que funciona em duas máquinas diferentes).

É possível adicionar mais do que só duas pessoas, mas a estilização do arquivo ficaria quebrada e as outras pessoas apareceriam embaixo da tela (seria possível visualizá-las dando scroll), não é culpa da API, sim do CSS utilizado na POC.

### Testes realizados durante a concepção
Foi feita uma chamada entre duas pessoas, uma em Recife e outra em Petrolina, cerca de 712 km de distância e não houve problemas de comunicação. Além disso, foram adicionados mais de 20 membros numa única chamada e tambm não houve nenhum problema.

## Solução para jogos embutidos na plataforma
Para essa POC, a solução encontrada foi a utilização da [tag HTML <iframe>](https://www.w3schools.com/html/html_iframe.asp).

### Como rodar a POC
Rode o arquivo Game_iframe/index.html. Logo será possível visualizar uma tela de carregamento do jogo. Após esperar o carregamento, é só começar a jogar e se divertir.

É possível adicionar qualquer jogo disponibilizado via Iframe na internet. Algumas boas opções estão na documentação técnica supracitada. No entanto, para a grande maioria dos títulos, é necessário habilitar o Flash no navegador, visto que os jogos dependem dessa ferramenta.

### Testes realizados durante a concepção
O jogo foi testado por várias horas durante a concepção. Além dele, outros  títulos, os quais requeriam o Flash habilitado, também foram testados. No entanto, foi escolhido deixar esta obra na POC, pois não necessita de nada para funcionar, portanto qualquer um poderia jogar e testar livremente.
