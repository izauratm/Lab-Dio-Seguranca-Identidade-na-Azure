# 🛡️ Resumo do Lab: Identidade, Acesso e Segurança Microsoft Azure AZ-900
Este repositório reúne os principais aprendizados adquiridos durante o laboratório de **Identidade, Acesso e Segurança na Azure** da plataforma [DIO.me](https://web.dio.me), Arquitetura e Serviços Azure - Módulo 2. O foco está nos benefícios e aplicações práticas da plataforma Microsoft Azure, explorando seus recursos e funcionalidades. O Bootcamp oferece uma base sólida em tecnologias de nuvem, abordando desde os conceitos fundamentais até os componentes essenciais da arquitetura Azure.
Entre os temas estudados estão: criação e gerenciamento de máquinas virtuais, configuração de bancos de dados e soluções de armazenamento, além de tópicos avançados como arquitetura em nuvem, governança, monitoramento e segurança de ambientes cloud.

---
## 📘 Tópicos Abordados
 A segurança na nuvem é um dos pilares mais importantes para qualquer empresa que utiliza serviços como o Microsoft Azure.
 No centro dessa segurança, está o gerenciamento de identidade, acesso e segurança que serão abordados a seguir.
 
---
## 🪪 Identidade, Acesso e Segurança no Azure

## 🔐 Microsoft Entra ID
- Gerenciamento de identidades
- Autenticação única (SSO)
- Autenticação multifator (MFA)
- Acesso condicional

## 🏢 Entra Domain Services
- Domínio gerenciado na nuvem
- Suporte a LDAP, Kerberos, NTLM
- Autenticação para apps legados
<img width="500" height="300" alt="fig6" src="https://github.com/user-attachments/assets/88fb8ebd-8194-4bef-a59f-91369e96b31a" />

## ✅ Autenticação vs. Autorização
- Autenticação: Verifica identidade
- Autorização: Define permissões

## 📛 Acesso Condicional
- Baseado em:
  - Localização
  - Dispositivo
  - Aplicativo
- Ações:
  - Exigir MFA
  - Bloquear acesso
  - Permitir com restrições
  <img width="500" height="300" alt="fig5" src="https://github.com/user-attachments/assets/fa84fef2-8cf3-46c8-91fc-3d7faecad59e" />
  
---

### 🔐 Microsoft Entra ID – Configuração de Organização

Este documento reúne os principais recursos e funcionalidades disponíveis ao configurar uma organização no **Microsoft Entra ID**, o serviço de gerenciamento de identidades e acesso baseado em nuvem da Microsoft.
Ao criar uma organização no Entra ID, é provisionado um diretório na nuvem que centraliza o controle de identidades, acessos e políticas de segurança. 
A seguir, exploraremos as principais opções e ferramentas estudadas durante o curso, que permitem administrar usuários, grupos, permissões, domínios personalizados, integrações híbridas e muito mais.

---

### 🏢 Nome da Organização e Domínio

- Ao criar um diretório, é atribuído um domínio padrão: `suaempresa.onmicrosoft.com`, por exemplo.
- É possível **customizar o nome do domínio** adicionando seu domínio corporativo (ex: `suaempresa.com`) para facilitar logins e integração com e-mails.

---

### 👥 Usuários

- **Criar novo usuário**: Adição manual ou via sincronização com AD local.
- **Usuários excluídos**: Contas removidas recentemente, com opção de restauração (até 30 dias).
- Atribuição de funções, licenças e grupos no momento da criação.

---

### 🧑‍🤝‍🧑 Grupos

- Criação de **grupos de segurança** ou **Microsoft 365**.
- Permite controle de acesso a recursos e aplicativos.
- Suporte a **atribuição dinâmica** com base em atributos (ex: departamento, cargo).

---

### 🛡️ Regras e Administradores

- Definição de funções administrativas:
  - Administrador Global
  - Administrador de Usuários
  - Administrador de Segurança
- Uso de **ID Governance** para automações, revisões e ciclo de vida de acesso.

---

### 🌐 Identidades Externas

- Colaboração com **convidados e parceiros**.
- Suporte a autenticação via redes sociais (Google, Facebook).
- Ideal para cenários B2B e B2C.

---

### 🔄 Microsoft Entra Connect

- Ferramenta para **sincronizar identidades locais** com a nuvem.
- Modos de sincronização:
  - Senha hash
  - Pass-through authentication
  - Single Sign-On (SSO)

---

### 🧠 Health (Preview)

- Painel de **saúde do diretório**.
- Monitora sincronizações, alertas e status de serviços conectados.

---

### 🔐 Permissionamentos

- Gerenciamento de permissões com base em funções (RBAC).
- Uso do **Permissions Management** para visualizar e controlar acessos em múltiplas nuvens.

---

### 🛡️ Microsoft Defender for Cloud

- Proteção contra ameaças para identidades e recursos.
- Detecção de logins suspeitos, credenciais comprometidas e atividades anômalas.
- Integração com políticas de **Acesso Condicional baseado em risco**.

---


## ✅ Conclusão

A configuração e o gerenciamento de uma organização no **Microsoft Entra ID** representam um dos pilares fundamentais para garantir segurança, controle e eficiência em ambientes de nuvem. 
Ao explorar recursos como usuários, grupos, identidades externas, permissionamentos e integração com o Microsoft Defender for Cloud, é possível construir uma estrutura robusta de identidade e acesso que se adapta às necessidades modernas de empresas e equipes.
Este conteúdo reforça a importância de aplicar boas práticas de segurança desde o início da jornada na nuvem, utilizando ferramentas como **Acesso Condicional**, **MFA**, **Entra Connect** e **RBAC** para proteger dados, aplicações e usuários contra ameaças internas e externas.
O aprendizado adquirido neste laboratório não apenas nos prepara para certificações como a **AZ-900**, mas também oferece uma base sólida para atuarmos com responsabilidade e estratégia em projetos reais na plataforma Microsoft Azure.


---
> Este conteúdo faz parte do projeto **Entendendo sobre Segurança e Identidade na Azure- Laboratório** da plataforma [DIO.me](https://web.dio.me).

---
 
### 📚 Recursos Adicionais
- [O que é o Microsoft Entra?](https://learn.microsoft.com/pt-br/entra/fundamentals/what-is-entra)
- [Como renomear o Azure AD](https://learn.microsoft.com/pt-pt/azure/active-directory/fundamentals/how-to-rename-azure-ad)
- [Padrões de segurança no Microsoft Entra ID](https://learn.microsoft.com/pt-br/entra/fundamentals/security-defaults)
- [Como criar, convidar e excluir usuários](https://learn.microsoft.com/pt-br/entra/fundamentals/how-to-create-delete-users)
- [Atributos de Segurança Personalizados](https://learn.microsoft.com/pt-br/entra/fundamentals/custom-security-attributes-overview)
- [O que é Azure RBAC](https://learn.microsoft.com/pt-br/azure/role-based-access-control/overview)
- [Calculadora de Preços Azure](https://azure.microsoft.com/pt-br/pricing/calculator/?ef_id=_k_EAIaIQobChMI14z7o_fWjwMVc0FIAB3PYQApEAAYASACEgLE-fD_BwE_k_&OCID=AIDcmmzmnb0182_SEM__k_EAIaIQobChMI14z7o_fWjwMVc0FIAB3PYQApEAAYASACEgLE-fD_BwE_k_&gad_source=1&gad_campaignid=1635078708&gbraid=0AAAAADcJh_s0nlhmSLvv4COb6oAkGNm0s&gclid=EAIaIQobChMI14z7o_fWjwMVc0FIAB3PYQApEAAYASACEgLE-fD_BwE)
- [Assinatura do Azure](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/azure-subscription-service-limits)
  
📎 Link do curso: [Microsoft Azure AZ-900 - DIO.me](https://web.dio.me/track/microsoft-azure-az-900)

🖼️ Imagens: Fonte Dio.me
