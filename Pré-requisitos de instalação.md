# Pré-requisitos para a instalação

### Listagem:
* https://emdocs.gitbook.io/manual-do-cliente/o-sistema/requisitos-para-a-instalacao


### Links de instalação de pré-requisitos:

* Firebird versão 2.5.0:
  https://firebirdsql.org/en/firebird-2-5/
  
* DotNet versão mínima 4.7.2
  https://support.microsoft.com/pt-br/help/4054530/microsoft-net-framework-4-7-2-offline-installer-for-windows
  
  Obs.: Caso o Sistema operacional for Windows 10 e o sistema apresentar erro no DotNet, abra o link abaixo e atualize o Windows 10.
  https://www.microsoft.com/pt-br/software-download/windows10

### Configurar Portas no Windows Defender Firewall 

  Caminho:

   Painel de Controle => Sistema e Segurança => Windows Defender Firewall
   
  Regra de Entrada e Saída:
  Porta TCP
  Portas Locais: 3050,3054,8085
  Nome: Escolar Manager
