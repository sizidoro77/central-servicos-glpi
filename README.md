<h1 align="center" style="font-weight: bold;">Central de Serviços GLPI 💻</h1>

<p align="center">
    <img src="./.github/logo.png" width="180px" alt="GLPI Logo">
</p>

<p align="center">
    <b>Ambiente de Service Desk baseado em GLPI para otimização de chamados e inventário de TI. 🚀🛠️</b>
</p>

---

## 💻 Tecnologias e Infraestrutura

* **GLPI (v10.x):** Núcleo do sistema para gerenciamento de serviços (ITSM) e governança de ativos.
* **Stack LAMP/WAMP:** Infraestrutura base utilizando Apache (Servidor Web), MariaDB/MySQL (Banco de Dados) e PHP.
* **Ambiente de Hospedagem:** Virtualização isolada via Hyper-V / VMware rodando Ubuntu Server.

---

## 🚀 Instruções de Uso e Fluxo de Atendimento

Siga as etapas abaixo para acessar o laboratório e simular o fluxo completo de suporte:

### 1. Acesso ao Sistema
Abra o seu navegador e acesse a interface central do sistema:
> [http://localhost/glpi/front/central.php](http://localhost/glpi/front/central.php)

### 2. Autenticação de Teste
Utilize as credenciais homologadas abaixo para validar os diferentes níveis de permissão (perfis de acesso):

| Perfil | Usuário (Login) | Senha |
| :--- | :--- | :--- |
| **Usuário Final (Requerente)** | `Gabriel` | `Sd112406` |
| **Analista Técnico (Suporte)** | `Samuel` | `Sd112406` |

---

### 3. Abertura de Chamado (Perfil: Usuário Final)
1. Autentique-se utilizando o perfil **Gabriel**.
2. Clique em **"Criar um chamado"**, selecione a categoria desejada (Ex: *Redes* ou *Hardware*), preencha os detalhes da ocorrência e envie o formulário.

<p align="center">
    <img src="./assents/Login.png" alt="Tela de Login do GLPI" width="48%">
    <img src="./assents/Criar chamado.png" alt="Painel de Criação de Chamado" width="48%">
</p>

---

### 4. Triagem e Recebimento (Perfil: Analista Técnico)
1. Desconecte-se do perfil anterior e autentique-se como o analista **Samuel**.
2. Acesse o menu **Assistência > Chamados** para visualizar as demandas pendentes na fila de atendimento.

<p align="center">
    <img src="./assents/Login Samuel.png" alt="Tela de Login do GLPI Analista" width="48%">
    <img src="./assents/Recebimento do chamado.png" alt="Painel de Controle de Recebimento" width="48%">
</p>

---

### 5. Resolução Técnica e Encerramento
1. Dentro do ticket selecionado, atribua o chamado ao seu usuário (técnico).
2. Execute o diagnóstico, insira a solução técnica detalhada no histórico e altere o status para **Solucionado/Fechado** para encerrar o ciclo do chamado.

---
