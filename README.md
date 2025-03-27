
# 🧰 Canivete USB – Pendrive Multiboot para Manutenção e Resgate

Transforme seu pendrive em um canivete suíço digital com múltiplas ISOs de boot para manutenção, diagnóstico e recuperação de sistemas.

---

## ⚠️ AVISO LEGAL

Este conteúdo é fornecido com fins educacionais e técnicos.  
Use por sua **própria conta e risco**. Não aplique em máquinas de terceiros sem autorização expressa.

---

## 🎯 Objetivo

Criar um pendrive multiboot funcional e versátil para técnicos de TI, permitindo carregar diversas ISOs em um único dispositivo, incluindo:

- Ferramentas de recuperação
- Antivírus offline
- Live CDs Linux
- Instaladores do Windows
- Utilitários de diagnóstico e clonagem

---

## 🔧 Ferramenta Recomendada: **Ventoy**

[Ventoy](https://ventoy.net) é uma ferramenta open source que transforma o pendrive em um carregador de ISOs.  
Com ele, basta copiar os arquivos `.iso` para o pendrive – sem precisar reformatar a cada nova imagem.

---

## 🛠️ Como Criar seu Canivete USB

### 1. Baixe e instale o Ventoy

- Acesse [https://ventoy.net/en/download.html](https://ventoy.net/en/download.html)
- Extraia o `.zip`
- Execute `Ventoy2Disk.exe` (Windows) ou use terminal (Linux)
- Selecione o pendrive e clique em **Install**

> ⚠️ O conteúdo do pendrive será apagado. Faça backup antes.

---

### 2. Adicione as ISOs que desejar

Exemplos de ISOs úteis:

| ISO | Finalidade |
|-----|------------|
| `HirensBootCD.iso` | Diagnóstico, reset de senha, partição |
| `RescueZilla.iso` | Clonagem de discos e backup |
| `Kaspersky Rescue.iso` | Antivírus offline |
| `Ubuntu.iso` | Live Linux para manutenção |
| `Windows10.iso` | Instalação do Windows |

---

### 3. Dar Boot

- Insira o pendrive no computador
- Acesse o menu de boot (geralmente F12, F10, ESC ou DEL)
- Escolha o pendrive
- Selecione a ISO no menu do Ventoy

---

## 🗂️ Organização Sugerida

Você pode organizar as ISOs por pastas:

```
/isos
   /windows
   /linux
   /rescue
   /tools
```

(O Ventoy reconhece as ISOs mesmo dentro de subpastas)

---

## 🧪 Recursos Extras

- Suporte a **Secure Boot**
- **Persistência** para distros Linux
- **Menu personalizado** (via JSON)
- Compatível com BIOS legado e UEFI

---

## 🛡️ Ética e Responsabilidade

Ferramentas de diagnóstico e boot devem ser usadas com ética e conhecimento.  
Este repositório visa ajudar profissionais e estudantes da área técnica. **Use com bom senso.**

---

## 📝 Licença

Distribuído sob a licença [MIT](LICENSE).  
Você pode usar, modificar e compartilhar com os devidos créditos.

---

**Feito por [rivaed](https://github.com/rivaed) – seu pendrive técnico, de verdade.**

