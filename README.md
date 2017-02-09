**Passo 1**
 - Crie uma Página no Facebook
 - Copie o id da Página do Facebook (Navega até Página>Sobre), (Número de identificação da Página)

**Passo 2**
 - Crie um App do Facebook no https://developers.facebook.com/apps
Copie o id do App
 - Em configurações>Básico adicione um plataforma site e insira a url (pode ser local, https://localhost)

**Passo 3**
 - Vá ate a ferramenta de suporte do Facebook o Explorer Graphic API (https://developers.facebook.com/tools/explorer/)
 - Copie o Token de Acesso

**Passo 4**
 - Vá até a sua Página no Facebook, depois em Ferramenta de Publicação>Videos>Biblioteca de Videos, + Ao Vivo
 - Copie a chave do Stream
 - Avançar e insira um Título

**Passo 5**
 - Baixe o Programa OBS (https://obsproject.com/download)
 - Inicie o programa, Settings>Stream
 - Selecione:
> Stream Type: Streaming Services <br>
> Service: Facebook Live <br>
> Stream Key: Insira a Chave do Stream copiada do Facebook <br>
> De um Ok

 - Selection no Sources> Window Capture, clique na engrenagem
 - Seleccione o navegador que vai rodar o site que contem o código do projeto
 - De um Ok
 - Clique em Start Streaming

**Passo 6**
 - Volte para o Facebook e clique na engrenagem e clique em incorporar
 - Copie o id do post (Fica entre “videos%2F <ID FICA POR AQUI> %2F” do código do iframe
 - De um ok 
 - Clique em Transmitir ao vivo

**Passo 7**
 - Vá ao código e coloque todas as infos que coletou acima
 
> var id_post = //ID DO POST DO STREAM; <br>
> var id_page = //ID DA PAGE DO FACEBOOK; <br>
> var id_app = //ID DO APP DO FACEBOOK; <br>
> var token = //ACCESS TOKEN;

**Passo 8**
 - Rode a página e bingo

