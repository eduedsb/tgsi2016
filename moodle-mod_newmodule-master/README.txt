The following steps should get you up and running with
this module template code.

* DO NOT PANIC!

* 
Unzip the archive and read this file

* Rename the newmodule/ folder to the name of your module (eg "widget").
  
The module folder MUST be lower case and can't contain underscores. You should check the CVS contrib
  area at
 http://cvs.moodle.org/contrib/plugins/mod/ to make sure that
  your name is not already used by an other module. 
Registering the plugin
  name @ http://moodle.org/plugins will secure it for you.

* Edit all the files in this 
directory and its subdirectories and change
  all the instances of the string "newmodule" to your module name
  (eg "widget").
 If you are using Linux, you can use the following 
command
  $ find . -type f -exec sed -i 's/newmodule/widget/g' {} \;
  $ find . -type f -exec sed -i 's/NEWMODULE/WIDGET/g' {} \;

  
On a mac, use:
  $ find . -type f -exec sed -i '' 's/newmodule/widget/g' {} \;
  $ find . -type f -exec sed -i '' 's/NEWMODULE/WIDGET/g' {} \;

* 
Rename the file lang/en/newmodule.php to lang/en/widget.php
  where "widget" is the name of your module

* Rename all files in backup/moodle2/ folder by 
replacing "newmodule" with
  the name of your module

  On Linux you can perform this and previous 
steps by calling:
  $ find . -depth -name '*newmodule*' -execdir bash -c 'mv -i "$1" "${1//newmodule/widget}"' bash {} \;

* Place the widget 
folder into the /mod folder of the moodle
  directory.

* Modify version.php and set the initial version of you module.

* 
Visit Settings > Site Administration > Notifications, you should find
  the module's tables successfully created

* 
Go to Site Administration > Plugins > Activity modules > Manage activities
  and you should find that this newmodule has been added to the list
 of
  installed modules.

* You may now proceed to run your own code in an attempt to develop
  your module. You will probably want to modify 
mod_form.php and view.php
  as a first step. Check db/access.php to add capabilities.
  
Go to Settings > Site Administration > Development > XMLDB editor
  and modify the module's tables.

We encourage you to share your code and experience
 - visit http://moodle.org

Good luck!

---
Os seguintes passos devem chegar at� voc� e correr com este c�digo do modelo m�dulo.
* N�O ENTRE EM P�NICO!*
Descompacte o arquivo e ler este arquivo

* Mudar o nome da pasta / newmodule ao nome de seu m�dulo (por exemplo, "Widget").
  
A pasta m�dulo deve estar em min�sculas e n�o pode conter sublinhados. Voc� deve verificar o contrib CVS  na �rea
 http://cvs.moodle.org/contrib/plugins/mod/ ter certeza de que seu nome n�o seja utilizado por um outro m�dulo.

Registrar o plugin nomear @ http://moodle.org/plugins vai prend�-lo para voc�.

* editar todos os arquivos nesta diret�rio e seus subdiret�rios e mudan�a todas as inst�ncias da string "newmodule" 
para o seu nome do m�dulo  (Por exemplo, "widget").
 Se voc� estiver usando Linux, voc� pode usar o seguinte comando
  $ Find. -type f -exec sed -i 's / newmodule / widget / g' {} \;
  $ Find. -type f -exec sed -i 's / NEWMODULE / widget / g' {} \;

  
Em um Mac, use:
  $ Find. -type f -exec sed -i '' 's / newmodule / widget / g' {} \;
  $ Find. -type f -exec sed -i '' 's / NEWMODULE / widget / g' {} \;

*Renomeie o arquivo lang / en / newmodule.php para lang / en / widget.php   onde "widget" � o nome do seu m�dulo

* Renomeie todos os arquivos na pasta / backup / moodle2 por substituindo "newmodule" com o nome do seu m�dulo

  No Linux, voc� pode executar este e anteriores passos chamando:
  $ Find. -nome -depth '* newmodule *' -execdir festan�a -c 'mv -i "$ 1" "$ {1 // newmodule / widget}"' festan�a {} \;

* Coloque o widget pasta para a pasta mod / do moodle diret�rio.

* Modificar version.php e definir a vers�o inicial de voc�s m�dulo.

* Visita Configura��es> Administra��o do Site> Notifica��es, voc� deve encontrar tabelas do m�dulo criado com sucesso

* Ir para a Administra��o do Site> Plug-ins> m�dulos de atividades> Gerenciar atividades e voc� deve achar que este
 newmodule foi adicionado � lista do m�dulos instalados.

* Voc� pode agora avan�ar para executar o seu pr�prio c�digo, em uma tentativa de desenvolver seu m�dulo. 
Voc� provavelmente vai querer modificar mod_form.php e view.php como um primeiro passo. 
Verifique db / access.php para adicionar capacidades.
  
V� para Configura��es> Administra��o do Site> Desenvolvimento> editor XMLDB  e modificar tabelas do m�dulo.

N�s encorajamos voc� a compartilhar seu c�digo e experi�ncia - Visitar http://moodle.org

Boa sorte!