<h1>Guia de comandos Linux Ubuntu</h1>

<Scripts com Linux>

<h4>Aplicacao rodando em segundo plano no Linux Ubuntu - <strong>API-com-Django-Validacoes-buscas-filtros-e-deploy - repositorio original )</strong></h4>
<ul>
  <li><strong>screen -list</strong> === lista as sessoes executadas em segundo plano;</li>
   <li><strong>screen -S nomeDoApp</strong> === prepara o ambiente para ficar sendo executado em segundo plano, após esse comando dentro da pasta onde esta o app, coloca-se o serviço para rodar, neste exemplo python3 manage 0.0.0.0:8000 - <strong>notar ao final do comando 0.0.0.0:8000 definindo que a porta 8000 estara liberada para todas as interfaces de rede e nao apenas a 127.0.0.1 como o padrao usado na maquina local</strong>;</li>
</ul>


<h2>Comandos úteis </h2>
<ul>
    <li><strong>hostname</strong> == exibe o nome do computador.</li>
     <li><strong>sudo hostnamectl set-hostname novoNome</strong> == altera o nome do computador.</li>
    <li><strong>uname -a</strong> == exibe detalhes do sistema Ubuntu.</li>
   <li><strong>whoami</strong> == mostra o usuario atual.</li>
   <li><strong>curl -i endereco</strong> == realiza uma solicitacao HTTP.</li>
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
    <li><strong>chmod 400 nomePacote</strong> = permissao de apenas leitura para o arquivo</li>	
</ul>

<h2>Montar automaticamente uma unidade de disco após a reinicialização do sistema.</h2>
<p>O comando <strong>mount nomeDaUnidade localDeMontagem</strong> monta uma unidade de disco, porém isso não fica gravado, dessa forma ao reiniciar ou desligar o Ubuntu o ponto de montagem é perdido.</p>
<p></p><strong>sudo df -h </strong>este comando exibe detalhes sobre as partições existentes no linux. com esse com comando é possível ver os pontos de montagem existentes.</p>
<p></p><strong>sudo fdisk -l </strong>este comando exibe detalhes das unidades de disco, todos os dispositivos reconhecidos pelo Ubuntu.</p>
<p></p><strong>Editar o arquivo /etc/fstab</strong> arquivo crítico e contém os pontos de montagem a serrem inicializados automaticamente. Adicionar o nome da uniddade e o tipo de partição e o tipo defaults neste arquivo, desta forma a partição irá montar automaticamente no ponto definido.</p>
<strong>sudo mount -a </strong> comando para testar os pontos de montagem sem precisar reiniciar a máquina, dessa forma se houver um erro ao editar o arquivo fstab, será possível resolver. 

<h2>Processo de formatação ou instalacao do filesystem em um disco no Ubuntu</h2>
<ul>
   <li><strong>sudo fdisk nomeDaUnidade</strong> comando particionar o disco, opção p lista as particoes; a opcao m mostra o help do comando; para finalizar usar o w para gravar o particionamento do disco.</li>
   <li><strong>sudo mkfs.ext4 nomeDaUnidade</strong> define a particao ext4.</li>
   <li><p>O comando <strong>mount nomeDaUnidade localDeMontagem</strong> monta uma unidade de disco, porém isso não fica gravado, dessa forma ao reiniciar ou desligar o Ubuntu o ponto de montagem é perdido.</p></li>
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






















