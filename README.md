```bash
#!/bin/bash
# Initializing user profile...

USER="Suellen Santiago"
ROLE="Cybersecurity | Data Engineering"
CURRENT_FOCUS="Segurança da Informação & Threat Intelligence"
BACKGROUND="Python, SQL, Data Engineering & BI"
EDUCATION="ADS — Análise e Desenvolvimento de Sistemas"

echo "[+] Acesso concedido."
echo "[+] Carregando perfil profissional..."

profile() {
    echo "-> Desenvolvendo experiência prática em Segurança da Informação."
    echo "-> Unindo engenharia de dados, infraestrutura e segurança."
    echo "-> Aprendendo através de laboratórios, experimentação e documentação."
}

profile

if [ -d "$HOME/pentest-homelab" ]; then
    echo "[+] Projeto atual: Pentest & Red Team Home Lab"
    echo "    KVM/QEMU | Proxmox | VLANs | Firewalls | Docker"
fi

echo ""
echo "[*] Core skills:"
echo "    Linux | Networking | Python | SQL | Git | Docker"
echo "    Data Engineering | Power BI | Microsoft Fabric | Power Platform"

echo ""
echo "[*] Interesse profissional em Cibersegurança e Segurança de Infraestrutura""

echo ""
echo "[+] Contato: suellensantiagodesouza@gmail.com"
echo "[+] Linkedin: suellen-santiago"
```
