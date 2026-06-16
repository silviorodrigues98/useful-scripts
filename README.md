# Coleção de Scripts Úteis

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Batch](https://img.shields.io/badge/Batch-4D4D4D?style=for-the-badge&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/Licen%C3%A7a-MIT-green?style=for-the-badge)

> Coleção de scripts para Windows e Linux: ativação, manutenção do sistema, redes, instalação de software e automação de tarefas repetitivas.

## 📂 Estrutura

```
📦 useful-scripts/
├── 📁 Windows/
│   ├── 📁 Activation/       # Ativação de produtos Microsoft
│   ├── 📁 DevTools/         # Ferramentas para desenvolvedores
│   ├── 📁 Installation/     # Instaladores automatizados
│   ├── 📁 Maintenance/      # Manutenção e limpeza do sistema
│   ├── 📁 Network/          # Diagnóstico e configuração de rede
│   ├── 📁 PowerManagement/  # Gerenciamento de energia
│   └── 📁 Utilities/        # Utilitários diversos
├── 📁 Linux/
│   ├── 📁 Installation/     # Instalação de pacotes e ferramentas
│   └── 📁 System/           # Configuração e manutenção do sistema
├── LICENSE
└── README.md
```

## 🚀 Como usar

### Windows
```powershell
# Execute como Administrador
.\Windows\Installation\install-choco.ps1
.\Windows\DevTools\setup-dev-env.ps1
```

### Linux
```bash
# Dê permissão de execução
chmod +x Linux/Installation/*.sh
./Linux/Installation/install-docker.sh
```

## 📜 Scripts disponíveis

### Windows
| Categoria | Script | Descrição |
|-----------|--------|-----------|
| Activation | `ativar-office.ps1` | Ativação do Microsoft Office |
| DevTools | `setup-dev-env.ps1` | Configura ambiente de desenvolvimento |
| Installation | `install-choco.ps1` | Instala Chocolatey + pacotes essenciais |
| Maintenance | `clean-system.ps1` | Limpeza de arquivos temporários |
| Network | `network-diagnostics.ps1` | Diagnóstico completo de rede |
| PowerManagement | `power-settings.ps1` | Otimização de energia |

### Linux
| Categoria | Script | Descrição |
|-----------|--------|-----------|
| Installation | `install-docker.sh` | Instala Docker e Docker Compose |
| System | `setup-ubuntu.sh` | Configuração pós-instalação do Ubuntu |

## 📄 Licença

MIT © [Silvio Rodrigues](https://github.com/silviorodrigues98)
