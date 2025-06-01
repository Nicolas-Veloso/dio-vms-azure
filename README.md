# Como Criar uma Máquina Virtual no Azure

## 1. Acessar o Portal do Azure
- Vá para [https://portal.azure.com](https://portal.azure.com)
- Faça login com sua conta Microsoft

## 2. Criar um Recurso
- No menu lateral, clique em **"Criar um recurso"**
- Selecione **"Máquina Virtual"** na lista de recursos

## 3. Configurar a Máquina Virtual
- **Assinatura e grupo de recursos**: selecione ou crie um novo
- **Nome da VM**: defina um nome para sua máquina virtual
- **Região**: escolha a região mais próxima para melhor desempenho
- **Imagem**: selecione o sistema operacional (ex: Windows Server, Ubuntu)
- **Tamanho**: escolha a especificação da máquina (CPU, RAM)

## 4. Autenticação
- Selecione o método de autenticação:
  - **Usuário e senha** ou
  - **Chave SSH** (recomendado para Linux)

## 5. Configurações de Rede
- Configure a **rede virtual**, **sub-rede** e **IP público**
- Permita as portas necessárias (ex: RDP para Windows, SSH para Linux)

## 6. Disco e Armazenamento
- Escolha o tipo de disco (SSD ou HDD)
- Configure discos adicionais, se necessário

## 7. Revisar e Criar
- Revise todas as configurações
- Clique em **"Criar"** para iniciar a implantação

## 8. Acessar a Máquina Virtual
- Após a criação, vá para **"Máquinas Virtuais"** no menu
- Selecione sua VM e clique em **"Conectar"**
- Use RDP (Windows) ou SSH (Linux) para acessar

> **Dica:** Lembre-se de encerrar a VM quando não estiver usando para evitar custos desnecessários.
