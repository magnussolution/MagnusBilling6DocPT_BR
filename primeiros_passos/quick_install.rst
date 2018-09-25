*************
Instalação
*************

.. image:: ../_static/images/logo.png
        :scale: 85% 

|

Bem vindo a documentação do Magnusbilling em português.

|

Para instalar MagnusBilling, você precisa apenas de um servidor com CentOS 7 ou Debian 8, 64 ou 32 bits, instalação básica.

|
    
**1.** Execute os comandos abaixo como root. O script vai instalar Magnusbilling, Asterisk e todas as dependências necessárias, como: IPTables, Fail2ban, Apache, PHP e mysql.

Instale o Linux **minimal**.

::
     
  cd /usr/src
  yum -y install wget
  wget http://downloads.sourceforge.net/project/magnusbilling/install.sh
  chmod +x install.sh
  ./install.sh
     
|
|

**2.** Durante a instalação será solicitado o idioma padrão para o Mangusbilling. Escolha digitando o numero do idioma escolhido.


::

   Instalação completa. ATENÇÃO!! APÓS TERMINAR A INSTALAÇÃO, O SERVIDOR SERÁ REINICIADO AUTOMATICAMENTE!

   Use um browser para login.
      entre em: http://000.000.000.000
      Usuário: root
      Senha: magnus (Lembre-se de alterar a senha padrão)
|
     
.. image:: ../_static/images/ilogin.png
        :scale: 80%
|

  
