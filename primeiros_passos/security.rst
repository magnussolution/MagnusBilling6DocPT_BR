***********
Segurança
***********

Recomendamos muito cuidado e atenção com a segurança de seu servidor. Para garantir use Firewalls, senhas fortes, principalmente no SSH, não use a senha do SSH para outras senhas, e principalmente mantenha sempre o sistema actualizado, principalmente o MagnusBilling e o Linux.


MagnusBilling
^^^^^^^^^^^^^
O script de instalação instala e configura o IPTables e Fail2Ban para você. Na instalação a senha do MagnusBilling é magnus, você deve mudar esta senha. NAO ESQUECER.


Firewall
^^^^^^^^
Apesar do script de instalação configurar o IPTables para você, é recomendável que você revise as configurações. Você pode verificar as configurações com o comando abaixo.

::

 iptables -L

*  `Firewall Doc`_


Upgrade
^^^^^^^^

Muitos dos problemas encontrados, ja podem ter sido solucionado, por tanto, mantenha atualizado seu MagnusBilling e seu Linux.

Centos
::

 yum update
 yum upgrade

Debian
::

 apt-get update
 apt-get upgrade

Magnusbilling
::

 /var/www/html/mbilling/protected/update.sh

Se voce quer atualizar com segurança, considere contratar nosso `suporte pago`_.



Fail2ban
^^^^^^^^

Fail2ban é usado para proteger seu SSH, Asterisk  e web server. 
Você pode ver os ip bloqueados pelo Fail2ban como próximo comando. Ou via WEB no menu firewall

::

 iptables -L


SSH
^^^^^^^^

Use senhas realmente fortes no SSH para proteger seu servidor.



.. _suporte pago: http://magnussolution.com/br/?s=suporte-por-hora
.. _Firewall Doc: /pt/latest/firewall/iptables.html