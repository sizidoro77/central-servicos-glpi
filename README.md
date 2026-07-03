<h1 align="center" style="font-weight: bold;">Central de Serviços GLPI 💻</h1>

<p align="center">
    <img src="./.github/logo.png" width="180px" alt="GLPI Logo">
</p>

<p align="center">
    <b>Ambiente de Service Desk baseado em GLPI para otimização de chamados e inventário de TI. 🚀🛠️</b>
</p>

---

## 💻 Tecnologias e Infraestrutura

*   **GLPI (v10.x):** Core do sistema para gerenciamento de chamados (ITSM) e governança de ativos.
*   **Stack LAMP/WAMP:** Infraestrutura base utilizando Apache (Servidor Web), MariaDB/MySQL (Banco de Dados) e PHP.
*   **Ambiente de Hospedagem:** Virtualização isolada via Hyper-V / VMware rodando Ubuntu Server.

---

## 🚀 Instruções de Uso

Siga as etapas abaixo para acessar o laboratório e simular o fluxo de atendimento:

### 1. Acesso ao Sistema
Abra o seu navegador e acesse a interface central do sistema:
> [http://localhost/glpi/front/central.php](http://localhost/glpi/front/central.php)

### 2. Autenticação de Teste
Utilize as credenciais homologadas abaixo para validar os diferentes perfis de acesso:

| Perfil | Usuário (Login) | Senha |
| :--- | :--- | :--- |
| **Usuário Final (Requerente)** | `Gabriel` | `Sd112406` |
| **Analista Técnico (Suporte)** | `Samuel` | `Sd112406` |

### 3. Simulação de Abertura de Chamado
1. Autentique-se com o perfil **Gabriel**.
2. Clique em **"Criar um chamado"**, selecione a categoria desejada (Ex: *Redes* ou *Hardware*), preencha os detalhes da ocorrência e envie.

### 📸 Demonstração do Ambiente
<br>
<p align="center">
    <img src="./assents/Login.png" alt="Tela de Login do GLPI" width="45%">
    <img src="./.github/example.png" alt="Painel de Controle" width="45%">
</p>

### 4. Resolução Técnica
1. Desconecte-se e faça login com o perfil **Samuel**.
2. Localize o chamado no painel de controle, assuma o ticket, insira a solução técnica e encerre o atendimento.

---
