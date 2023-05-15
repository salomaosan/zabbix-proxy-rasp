### PARA INSTALAÇÃO PADRÃO 

ansible-playbook -i hosts main.yml -e "SERVER=127.0.0.1"

### PARA INSTALAÇÃO SOMENTE DO PROXY 

ansible-playbook -i hosts main.yml -e "SERVER=127.0.0.1" --tag "install-proxy"

### PARA INSTALAÇÃO SOMENTE DO AGENTE 

ansible-playbook -i hosts main.yml --tags "install-agent"