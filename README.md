# 🛠️ Sysadmin Toolkit

Scripts úteis para administração de sistemas Linux. Este repositório reúne automações práticas que facilitam o dia a dia de um administrador de sistemas.

---

## 📜 Scripts disponíveis

### 1. `backup_dir.sh`
Faz backup de um diretório específico, compactando o conteúdo com a data e hora atual.

**Uso:**
```bash
bash backup_dir.sh
```

---

### 2. `check_disk.sh`
Monitora o espaço em disco. Se ultrapassar 90%, envia um alerta (simulado por email).

**Uso:**
```bash
bash check_disk.sh
```

---

### 3. `system_health_report.sh`
Gera um relatório com uptime, uso de CPU, memória e espaço em disco.

**Uso:**
```bash
bash system_health_report.sh
```

---

### 4. `bulk_user_add.sh`
Cria usuários a partir de um arquivo `usuarios.txt`, gerando senhas aleatórias para cada um.

**Exemplo do arquivo `usuarios.txt`:**
```
joao
maria
pedro
```

**Uso:**
```bash
bash bulk_user_add.sh
```

---

### 5. `basic_hardening.sh`
Aplica configurações básicas de segurança em um servidor Linux.

**Uso:**
```bash
sudo bash basic_hardening.sh
```

---

### 6. `ip_change_notifier.sh`
Detecta mudanças no IP público do servidor e envia uma notificação via webhook (como Discord ou Slack).

**Uso:**
```bash
bash ip_change_notifier.sh
```

---

## 🧾 Licença
MIT License

---

## 📬 Contato
Criado por [Fábio] - Projeto educacional. Sinta-se livre para contribuir ou adaptar os scripts ao seu ambiente!
