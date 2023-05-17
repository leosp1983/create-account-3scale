**Objetivo**
-------------

- Playbook para criar Accounts (Tenants) no 3Scale ambientes desenvolvimento, homologação e produção

=======================================================================

**Legenda**
-------------

- https://aap.orizon.com.br -> Console Ansible
- https://master.api.ocpdh.orizon.com.br/ -> 3Scale desenvolvimento e homologação
- https://master.api.ocppr.orizon.com.br/ -> 3Scale produção

=======================================================================

**Funções**
-------------
 
- [x] Valida se existe o tenant solicitado na criação;
- [X] Cria e ativa o tenant; 
- [X] Ativa o user svc_devops para administração do tenant;
- [X] Cria integração com o realm 3scale-infra;
- [x] Salva o token do tenant criado no git.orizon.com.br

=======================================================================

**Inventário**
-------------

- [x] jaen04.orizon.local - 172.18.0.237 ( ansible execution node )