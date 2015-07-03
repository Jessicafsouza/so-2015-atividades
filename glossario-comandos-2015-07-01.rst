======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Jéssica Franciele Rodrigues de Souza
:Matrícula: 20121144010222
:Data: 01/07/2015

cat
  Concatena arquivos exibindo o resultado na tela, sendo também utilizado para exibir o conteúdo de arquivos, Ex.: cat mytext.txt mytext2.txt (Irá imprimir o conteúdo desses dois arquivos de texto como se fossem um único arquivo.);


cd
  Alterar o diretório atual. Trocar de diretório,  Ex.: cd /tmp ,  cd .. , cd -;


cowsay
  Mostra uma imagem com uma mensagem, Ex.: cowsay -f  formatodavaca "Escreva aq a mensagem";


echo
  Permite exibir textos na tela, Ex.: x=10 echo O valor de x é $x.;


env
  Ele pode ser usado para imprimir uma lista das variáveis de ambiente atuais, ou para executar outro programa em um ambiente   personalizado, sem modificar o atual;


exit
  Sair do shell, termina uma sessão;


help
  Exibe informações sobre comandos internos, Ex.: help help;


HISTTIMEFORMAT="%d/%m/%y
  Lista os comandos feitos anteriormente com data e horário;


hostname
  Imprime o nome do host (máquina) atual sistema;


ifconfig
  Configura uma interface de rede;


last
  Mostra todas informações referente as entradas (login) e saídas (logout) de usuários do sistema;


lastb
  mostra quem tentou logar na meu sistema de forma mais detalhada, Ex.: lastb jessica;


ls
  lista os arquivos que estão dentro do diretório, ex.: ls /bin/ = os arquivos dentro do diretorio bin (ls -l : Lista os   arquivos em formato detalhado, ls - a: lista os arquivos ocultos, ls - R: lista os subdiretórios encontrados);


mkdir
  Serve para criar um diretório, Ex.: mkdir $pasta;


nome="fulano
  Declarando uma variável;


passwd
  Alteração de senha;


pwd
  Imprime o nome do diretório atual (print working directory);


set
  Define e determina os valores de ambiente do sistema, Ex.: bash;


tree
  árvore é uma estrutura de dados hierárquica que organiza elementos de dados, chamados de nós, ligando-os com links, Essa     estrutura é usada para ajudar a exibir grandes quantidades de informações em um formato fácil de ler;


tty
  Imprime o nome do terminal ligado ao seu padrão entrada. Ela imprime `no a tty 'se a entrada padrão não é um terminal;


vim
  É como um editor de texto;


wait
  Aguarda até a conclusão do trabalho e retorna status de saída. Faz com que um comando espere até que outro termine;


wall
  Escreve uma mensagem a outros usuários, Ex.: sudo wall message.txt (Usando o comando sudo para executar wall como super usuário, envia o conteúdo do message.txt a todos os usuários);


which
  Exibe o caminho completo na hierarquia de diretórios para os comandos do sistema, Ex.: which sh , which firefox;


while
  Um laço, executa comandos enquanto o teste seja bem-sucedido; 


who
  Mostra quem e dá informações sobre os usuários que estão conectados no momento no sistema;


whoami
  Nome do usuário associado com o atual efetivo ID do usuário; 


write
  Envia mensagens para outros usuários, |Ex.: cowsay -f  formatodavaca "Escreva aq a mensagem" | write nomedealguem ;


cp
Copia arquivos e diretórios, cp [opções] <arquivo_origem> <arquivo_destino>;


mv
Este comando move arquivos e diretórios,  usado também para renomear um determinado arquivo, Ex.: mv arquivo1 arquivo2, mv foo ~/Desktop, $mv <arquivo_origem> <arquivo_destino>;


rmdir
remove um diretório vazio;


rm 
Remove arquivos e diretórios, Ex.: rm [opções] <arquivo>, Para apagar um diretório com todo seu conteúdo: rm -r /tmp/lixo;


find
Procura por arquivos no diretório especificado, Ex.: procurar o arquivo nota.txt dentro do diretório /home/eitch: find /home/eitch -name nota.txt -print

