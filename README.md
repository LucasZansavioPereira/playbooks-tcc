# Playbooks de hardening

Playbooks Ansible usados no Trabalho de Graduação **"Uso de ferramentas open source no fortalecimento da segurança de servidores Linux"** (Fatec Ourinhos).

Aplicam o hardening nos servidores Ubuntu 24.04 a partir dos achados da auditoria feita com o Lynis.

- `hardening_geral.yml`: medidas comuns aos servidores Web e de banco de dados
- `hardening_web.yml`: medidas específicas do servidor Web (Nginx + PHP-FPM)
- `hardening_db.yml`: medidas específicas do servidor de banco de dados (MariaDB)

Cada tarefa tem um comentário com título, origem (Lynis ou Autor) e o que faz.
