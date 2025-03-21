#Speedtest RS

##

Sobre o Projeto

Esse projeto é um speedtest web que mede a velocidade de download, upload, ping e jitter direto do navegador. Ele usa HTML, JavaScript e PHP para renderizar a interface e um Web Worker para rodar os testes de conexão sem travar a UI.

##

Como Funciona?

O código principal está no arquivo HTML, onde temos:

Importação de arquivos PHP (head.php, menu.php e footer.php), que provavelmente contêm a estrutura da página.
<br>
Funções de desenho de medidores: Aqui rola um esquema usando canvas para desenhar os gráficos que mostram os resultados do teste.
<br>
Web Worker: O script speedtest_worker.min.js cuida da lógica pesada do teste de velocidade sem travar a interface.
<br>
Função startStop(): Dispara ou para o teste de velocidade.
<br>
Função updateUI(): Atualiza os valores exibidos na tela conforme os testes rodam.

##

Como Rodar?

Clone esse repositório: https://github.com/seuusuario/speedtest-web.git
<br>
Suba o projeto em um servidor web (XAMPP, LAMP, etc.).
<br>
Acesse no navegador e clique no botão para iniciar o teste.

#

O Que Ainda Falta?

Melhorar a interface (deixar mais responsivo e bonito 🏗️).
<br>
Implementar um histórico dos testes feitos.
<br>
Criar um sistema de logs para armazenar os resultados.
<br>
Melhorar a precisão dos cálculos.
<br>
Se tiver sugestões ou quiser contribuir, só mandar um PR ou abrir uma issue! 🚀
