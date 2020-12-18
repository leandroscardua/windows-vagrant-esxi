Utiliza o vagrant para instalar um box com Windows Server 2019 no ESXI ( Versão Gratuita )

 Programas:
--------
- Sistema Operacional : Linux
- Vagrant : 2.2.14
- ESXI: 6.7.0 Update 3 (Build 17167734)
- Ovftool: 4.4.0 (build-16360108)

 Requerimentos:
--------
- Habilitar SSH no ESXI
- Instalar o Ovftool no Linux ( https://code.vmware.com/tool/ovf )
- Instalar o pluing: vagrant-vmware-esxi ( https://github.com/josenk/vagrant-vmware-esxi#how-to-install )
- Vagrant box com windows: leandroscardua/ws2019 

 Arquivos:
--------

    .
    └── Vagrantfile              # arquivo de configuração do vagrant
     
 Execucao:
--------

    vagrant up --provider=vmware_esxi


