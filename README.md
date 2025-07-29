
Projeto Final 1 – Mapeamento de Rede Corporativa

Este é um projeto de análise de segurança em uma rede simulada usando Docker.

 Objetivo

Mapear três redes e identificar possíveis vulnerabilidades usando ferramentas como Nmap, Rustscan e ARP-Scan.

 Ferramentas utilizadas

- Nmap
- Rustscan
- ARP-Scan

 Resultados principais

- Rede **corp_net**: Estações seguras
- Rede **infra_net**: MySQL com senha vazia e FTP com login anônimo
- Rede **guest_net**: Dispositivos pessoais com SMB aberto
- Serviço **rpcbind** exposto em vários hosts

 Plano de ação

- Corrigir senhas fracas
- Bloquear acesso ao rpcbind
- Isolar a rede guest com VLAN

 Relatório completo

Veja o relatório com detalhes técnicos e plano de ação no arquivo `relatorio-completo.md`.

 Autor

Marco Aurélio – Projeto de Cibersegurança (2025)
