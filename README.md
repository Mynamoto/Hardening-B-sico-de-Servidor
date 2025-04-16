# Hardening-B-sico-de-Servidor

#!/bin/bash
echo "Desabilitando root SSH login..."
sed -i 's/^PermitRootLogin.*/PermitRootLogin no/' /etc/ssh/sshd_config

echo "Atualizando pacotes..."
apt update && apt upgrade -y

echo "Ativando firewall..."
ufw allow OpenSSH
ufw enable

echo "Servidor reforçado com configurações básicas."
