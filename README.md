# ansible-devops
Instalando ferramentas úteis ao Devops com o Ansible em sistemas do tipo RHEL/CentOS

### Atenção
Existe uma role para cada ferramenta em especifico, porém algumas ferramentas podem exigir a instalação de outras, como o caso do Kind que depende do Docker ou do Vagrant que depende do Virtualbox.

Nesses casos a fim de se manter a consistência para que não fosse preciso repetir todo o processo de instalação de uma ferramenta dentro da role da outra, recomenda-se que durante a criação da playbook de instalação seja feita a referência, a role da ferramenta que se pretende instalar e das outras ferramentas das quais ela depende.

Existem ainda duas playbooks nesse projeto exemplificando esse fluxo de trabalho, uma para instalação do Vagrant e outra do KIND.
