# Proxmox-Grafana-Dasboard
Dashboard de monitoramento do proxmox via Grafana


Dashboard do grafana destinado a monitorar proxmox e suas VMs.

Para o processo inicial estou utilizando Zabbix 6.4 + Zabbix Template Proxmox (via API) + Grafana 10.1 + Plugin Grafana Zabbix alexanderzobnin-zabbix-app 4.4.1 + Proxmox 8.0.4

Template padrão do zabbix 6.4

![image](https://github.com/mariorpn/Proxmox-Grafana-Dasboard/assets/16324587/83c18efd-6058-40d8-b881-f3f0d9077a9b)

Template extra - https://github.com/saulotarsobc/oluas_proxmox
![image](https://github.com/mariorpn/Proxmox-Grafana-Dasboard/assets/16324587/fe69a024-f374-479b-8d76-97c2792da6ac)

Configuração do host - Zabbix
![image](https://github.com/mariorpn/Proxmox-Grafana-Dasboard/assets/16324587/08135913-a2f5-4af8-8abf-0ab2156f6330)

Configuração das macros no host - Zabbix
![image](https://github.com/mariorpn/Proxmox-Grafana-Dasboard/assets/16324587/3c875100-9475-4f08-b11d-b13be1cd64bc)

Alterando o grupo a ser monitorado nesta variavel
![image](https://github.com/mariorpn/Proxmox-Grafana-Dasboard/assets/16324587/c43e4368-bc00-4383-8bd8-3e6befdd447c)

Substitua o valor pelo nome do grupo desejado
![image](https://github.com/mariorpn/Proxmox-Grafana-Dasboard/assets/16324587/21b6748e-5e6e-4a30-8cbc-02e048c270c1)

PS: todos os nodes de proxmox tem que estar neste grupo
