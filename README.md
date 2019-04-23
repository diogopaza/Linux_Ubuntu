<h1>Guia de comandos Linux Ubuntu</h1>

<p>Iniciando minhas expêrencias e testes pelo mundo Linux, instalei o Ubuntu sem maiores problemas dando boot via pendrive.</p>
<p>Aqui estarei montando o meu guia com comandos, dificuldades e resoluções de problemas que encontrarei nessa mudança de hábito, ao tentar usar o Linux como
meu sistema operacional de uso no dia a dia.</p>
<p>Por eu ser um estudante de tecnologia, precisarei instalar e baixar vários programas com certeza muitos problemas ocorrerão e pretendo relatar aqui 
alguns desses tópicos.</p>
<p>Aprendi logo de início a importância do uso do gerenciador de pacote <strong>apt</strong> que vem junto com o Ubuntu, acredito que seja padrão em todas as distribuições Debian.</p>
<p>Por padrão sempre devemos manter nosso gerenciador de pacotes atualizado, com o comando abaixo</p>
<p>Ex: <strong>sudo apt update</strong> </p>
<h2>Instalando arquivos .DEB no Linux</h2>
<p>O Linux Debian desenvolveu um sistema de empacotamento de software para facilitar a instalação de programas no Linux, esse empacotamento ganhou o nome de DEB.</p>
<p>O Ubuntu é uma distribuição derivada do Debian e por isso tem suporte a esse tipo de empacotamento.O Linux Mint é o mesmo caso.</p>
<p>Pode ser instalado via interface gráfica ou através do terminal:</p>
<p><strong>sudo dpkg -i nome_arquibo.deb == comando para instalr via terminal os pacotes .deb</strong></p>
<p><strong>sudo apt-get install -f == resolve as depências que estão faltando, após esse comando executa o comando acima novamente</strong></p>
<p></p>

<h2>Comandos úteis logo no início da utilização do sistema</h2>
<ul>
  <li><strong>ls</strong> = lista todos os arquivos diretório</li>
  <li><strong>ls -a</strong>= lista os arquivos ocultos também</li>
<li><strong>ls -l</strong>= lista todos os aruivos e suas permissões</li>
  <li><strong>chmod</strong>= altera as permissoes dos arquivos. Exe: chmod 777 arquivoX</li>
  <li><strong>gnome-system-monitor</strong>= gerenciador de tarefas do Ubuntu</li>
  <li><strong>sudo dpkg -i nome.pacote</strong>= instala pacotes no Debian( Ubuntu )</li>
  <li><strong>sudo dpkg -r nome.pacote</strong>= remove pacotes no Debian( Ubuntu ) mas não remove as configurações </li>
 <li><strong>sudo dpkg -P nome.pacote</strong>= remove pacotes no Debian( Ubuntu ) remove as configurações também</li>
 <li><strong>mv nome_arquivo nome_novo_arquivo</strong> = modifica o nome de um arquivo pode modificar a extensão também</li>
 <li><strong>sudo -s</strong> = login como root no terminal</li>
  <li><strong>rm -r nome_pasta</strong> = apaga pasta, logado como root apaga sem pedir para confirmar</li>
  <li><strong>free -m</strong> = informações sobre a memória </li>
  <li><strong>df -h</strong> = relátorios sobre o espaço disponivel no disco</li>	
  <li><strong>id</strong> = exibe a identidade do usuário </li>
  <li><strong>lscpu</strong> = exibi a estrutura da cpu do sistema</li>
</ul>

<h2>NMAP</h2>
<p>O Nmap(Network MApper) é um programa de código aberto que realiza o 
trabalho de portscan.</p>
<p>nmap -A  192.168.0.0/24 == verifica todos os hosts desta determinada 
faixa de IP, verificando o sistema operacional. </p>






















