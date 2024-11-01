Câmera de Monitoramento
Este projeto é uma aplicação web simples que utiliza a câmera do computador para capturar imagens. Ele permite ao usuário alternar entre a câmera frontal e traseira, tirar fotos e baixar essas imagens. É uma ótima maneira de entender como usar a API de MediaDevices do navegador.

Funcionalidades
Acesso à câmera do dispositivo (frontal ou traseira).
Captura de imagens em tempo real.
Download das imagens capturadas.
Interface simples e responsiva.
Tecnologias Utilizadas
HTML
CSS
JavaScript
API MediaDevices
Como Usar
Clone o repositório ou baixe o arquivo HTML diretamente.

bash
Copiar código
git clone <URL_DO_REPOSITÓRIO>
Abra o arquivo index.html em um navegador moderno (Chrome, Firefox, Edge, etc.).

Permita o acesso à câmera quando solicitado.

Use os botões:

Clique em "Tirar Foto" para capturar uma imagem.
Clique em "Trocar Câmera" para alternar entre a câmera frontal e traseira.
As fotos tiradas aparecerão na seção "Fototeca" abaixo, com a opção de download para cada imagem.

Requisitos
Um navegador que suporte a API MediaDevices.
Acesso a uma câmera conectada ao dispositivo.
Nota
Para garantir o funcionamento correto, é recomendável servir o arquivo HTML através de um servidor HTTP/HTTPS, pois muitos navegadores bloqueiam o acesso à câmera em arquivos locais.

Exemplos de Servidores Locais
Live Server: Uma extensão do VSCode que permite iniciar um servidor local facilmente.
http-server: Um pacote Node.js que pode ser instalado globalmente.
bash
Copiar código
npm install -g http-server
Depois, navegue até a pasta do projeto e execute:

bash
Copiar código
http-server
Licença
Este projeto é de código aberto e pode ser utilizado e modificado conforme desejado.

Sinta-se à vontade para personalizar este README de acordo com suas necessidades!
