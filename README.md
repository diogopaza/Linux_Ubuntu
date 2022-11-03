<h1>Guia de comandos Linux Ubuntu</h1>

<Scripts com Linux>


<h2>Comandos úteis </h2>
<ul>
  <li><strong>sudo apt update</strong> == atualiza o gerenciador de pacotes</li>
  <li><strong>ls</strong> == lista todos os arquivos diretório</li>
  <li><strong>ls -a</strong> == lista os arquivos ocultos também</li>
  <li><strong>ls -l</strong> == lista todos os aruivos e suas permissões</li>
  <li><strong>chmod</strong> == altera as permissoes dos arquivos. Exe: chmod 777 arquivoX</li>
  <li><strong>gnome-system-monitor</strong> == gerenciador de tarefas do Ubuntu</li>
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
  <li><strong>chmod +x nomePacote</strong> = da permissao para executar o script</li>	
</ul>

<h2>Alterando resolução de vídeo com o comando xrandr</h2>
<p>xrandr == lista saidas de vídeo e suas respectivas resoluções </p>
<p>xrandr --addmode DP-1 1920x1080 == adiciona a 
resolução passada na saída de vídeo DP-1.  </p>

<h2>Arquivo de inicialização</h2>
<p>Muito parecido com o autoexec.bat do ms-dos ou com o msconfig do 
Windows 7.</p>
<p>Editando o arquivo .profile é possível executar um comando
automaticante junto com  a inicialização do Linux</p>
<p>O arquivo .profile está localizado na pasta home do seu usuário</p>

<h2>NMAP</h2>
<p>O Nmap(Network MApper) é um programa de código aberto que realiza o 
trabalho de portscan.</p>
<p>nmap -A  192.168.0.0/24 == verifica todos os hosts desta determinada 
faixa de IP, verificando o sistema operacional. </p>






















