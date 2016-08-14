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
Os seguintes passos devem chegar até você e correr com este código do modelo módulo.
* NÃO ENTRE EM PÂNICO!*
Descompacte o arquivo e ler este arquivo

* Mudar o nome da pasta / newmodule ao nome de seu módulo (por exemplo, "Widget").
  
A pasta módulo deve estar em minúsculas e não pode conter sublinhados. Você deve verificar o contrib CVS  na área
 http://cvs.moodle.org/contrib/plugins/mod/ ter certeza de que seu nome não seja utilizado por um outro módulo.

Registrar o plugin nomear @ http://moodle.org/plugins vai prendê-lo para você.

* editar todos os arquivos nesta diretório e seus subdiretórios e mudança todas as instâncias da string "newmodule" 
para o seu nome do módulo  (Por exemplo, "widget").
 Se você estiver usando Linux, você pode usar o seguinte comando
  $ Find. -type f -exec sed -i 's / newmodule / widget / g' {} \;
  $ Find. -type f -exec sed -i 's / NEWMODULE / widget / g' {} \;

  
Em um Mac, use:
  $ Find. -type f -exec sed -i '' 's / newmodule / widget / g' {} \;
  $ Find. -type f -exec sed -i '' 's / NEWMODULE / widget / g' {} \;

*Renomeie o arquivo lang / en / newmodule.php para lang / en / widget.php   onde "widget" é o nome do seu módulo

* Renomeie todos os arquivos na pasta / backup / moodle2 por substituindo "newmodule" com o nome do seu módulo

  No Linux, você pode executar este e anteriores passos chamando:
  $ Find. -nome -depth '* newmodule *' -execdir festança -c 'mv -i "$ 1" "$ {1 // newmodule / widget}"' festança {} \;

* Coloque o widget pasta para a pasta mod / do moodle diretório.

* Modificar version.php e definir a versão inicial de vocês módulo.

* Visita Configurações> Administração do Site> Notificações, você deve encontrar tabelas do módulo criado com sucesso

* Ir para a Administração do Site> Plug-ins> módulos de atividades> Gerenciar atividades e você deve achar que este
 newmodule foi adicionado à lista do módulos instalados.

* Você pode agora avançar para executar o seu próprio código, em uma tentativa de desenvolver seu módulo. 
Você provavelmente vai querer modificar mod_form.php e view.php como um primeiro passo. 
Verifique db / access.php para adicionar capacidades.
  
Vá para Configurações> Administração do Site> Desenvolvimento> editor XMLDB  e modificar tabelas do módulo.

Nós encorajamos você a compartilhar seu código e experiência - Visitar http://moodle.org

Boa sorte!