1. Especifique algumas portas importantes pré-definidas para o protocolo TCP/IP.
21: FTP - Transferência de arquivos
25: SMTP - Transferência de e-mail
80: HTTP - web
POP3: e-mail
53: DNS

2. Com relação a endereços IP, responda:

(a) Qual é a diferença entre endereços IP externos e locais?
IP local é o endereço da máquina na rede local, IP externo é o endereço da maquina na internet. 

(b) Como endereços IP externos são definidos? Quem os define?

(c) Como endereços IP locais são definidos? Quem os define?

(d) O que é o DNS? Para que ele serve?
É um serviço que linka o domínio do site a um endereço IP do servidor.

3. Com relação à pilha de protocolos TCP/IP, responda:

(a) O que são suas camadas? Para que servem?
Camadas são niveis de protocolo. Servem para tratamento de dados na rede.

(b) Quais são as camadas existentes? Para que servem?
Camada de acesso a rede, especifica a forma que os dados devem ser encaminhados. Camada de internet, encarregada de fornecer o pacote de dados. Camada de transporte, gerencia o encaminhamento e a transmissão de dados. Camada de aplicação, agrupa os dados aos padrão de rede.

(c) Quais camadas são utilizadas pela biblioteca de sockets?
A camada de aplicação (TCP ou UDP).

(d) As portas usadas por servidores na função bind() se referem a qual camada?
Camada de aplicação

(e) Os endereços usados por clientes na função connect() se referem a qual camada?
Acesso a rede

4. Qual é a diferença entre os métodos `GET` e `POST` no protocolo HTTP?
A grande diferença entre os métodos GET e POST provavelmente é a visibilidade. Uma requisição GET é enviada como string anexada a URL, enquanto que a requisição POST é encapsulada junto ao corpo da requisição HTTP e não pode ser vista.
