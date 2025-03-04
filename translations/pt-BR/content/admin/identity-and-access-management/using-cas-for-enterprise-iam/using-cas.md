---
title: Usar CAS
redirect_from:
  - /enterprise/admin/articles/configuring-cas-authentication
  - /enterprise/admin/articles/about-cas-authentication
  - /enterprise/admin/user-management/using-cas
  - /enterprise/admin/authentication/using-cas
  - /admin/authentication/using-cas
  - /enterprise/admin/authentication/authenticating-users-for-your-github-enterprise-server-instance/using-cas
  - /admin/identity-and-access-management/authenticating-users-for-your-github-enterprise-server-instance/using-cas
intro: 'Se você usar o CAS (Serviço de Autenticação Central) para centralizar o acesso a vários aplicativos Web, poderá integrar o {% data variables.product.product_name %} configurando a autenticação do CAS para sua instância.'
versions:
  ghes: '*'
type: how_to
topics:
  - Accounts
  - Authentication
  - Enterprise
  - Identity
  - SSO
ms.openlocfilehash: 4bd9c8baf32ab09c593a251ca4f1cb698e075501
ms.sourcegitcommit: 1309b46201604c190c63bfee47dce559003899bf
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/10/2022
ms.locfileid: '145093966'
---
## Sobre a autenticação do CAS no {% data variables.product.product_name %}

O CAS é um protocolo de SSO (logon único) que centraliza a autenticação em vários aplicativos Web. Para obter mais informações, confira "[Central Authentication Service](https://en.wikipedia.org/wiki/Central_Authentication_Service)" no Wikipédia.

Depois de configurar o CAS, as pessoas que usam o {% data variables.product.product_location %} devem usar um token de acesso pessoal para autenticar solicitações de API ou Git por HTTP(S). As credenciais do CAS não podem ser usadas para autenticar essas solicitações. Para obter mais informações, confira "[Como criar um token de acesso pessoal](/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)".

Se você configurar o CAS, as pessoas com contas em seu IdP (provedor de identidade) não consumirão uma licença de usuário até que a pessoa entre no {% data variables.product.product_location %}.

{% data reusables.enterprise_user_management.built-in-authentication %}

## Considerações de nome de usuário no CAS

{% data reusables.enterprise_user_management.consider-usernames-for-external-authentication %} Para obter mais informações, veja "[Considerações de nome de usuário para autenticação externa](/admin/identity-and-access-management/managing-iam-for-your-enterprise/username-considerations-for-external-authentication)".

## Atributos CAS

Os atributos a seguir estão disponíveis.

| Nome do atributo           | Tipo     | Descrição |
|--------------------------|----------|-------------|
| `username`               | Obrigatório | Nome do usuário no {% data variables.product.prodname_ghe_server %}. |

## Configurar o CAS

{% data reusables.enterprise_site_admin_settings.access-settings %} {% data reusables.enterprise_site_admin_settings.management-console %} {% data reusables.enterprise_management_console.authentication %}
3. Selecione **CAS**.

   ![Captura de tela da seleção do CAS para autenticação](/assets/images/enterprise/management-console/cas-select.png)
4. {% data reusables.enterprise_user_management.built-in-authentication-option %}

   ![Captura de tela da opção de autenticação interna de fallback do CAS](/assets/images/enterprise/management-console/cas-built-in-authentication.png)
5. No campo **URL do Servidor**, digite a URL completa do servidor CAS. Se o servidor CAS usar um certificado que não pode ser validado pelo {% data variables.product.prodname_ghe_server %}, use o comando `ghe-ssl-ca-certificate-install` para instalá-lo como um certificado confiável. Para obter mais informações, confira "[Utilitários de linha de comando](/admin/configuration/configuring-your-enterprise/command-line-utilities#ghe-ssl-ca-certificate-install)".
