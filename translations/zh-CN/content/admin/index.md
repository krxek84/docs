---
title: 企业管理员文档
shortTitle: Enterprise administrators
intro: '适用于{% ifversion ghes %}部署、{% endif %}配置{% ifversion ghes %}、{% endif %}和管理 {% data variables.product.product_name %} 的企业管理员{% ifversion ghes %}、系统管理员{% endif %}和安全专家的文档和指南。'
redirect_from:
  - /github/setting-up-and-managing-your-enterprise/managing-your-enterprise-account
  - /github/setting-up-and-managing-your-enterprise
  - /github/installing-and-configuring-github-insights/exploring-your-usage-of-github-enterprise
  - /github/installing-and-configuring-github-insights/metrics-available-with-github-insights
  - /github/installing-and-configuring-github-insights/key-metrics-for-collaboration-in-pull-requests
  - /github/installing-and-configuring-github-insights/viewing-and-filtering-key-metrics-and-reports
  - /github/installing-and-configuring-github-insights/github-insights-and-data-protection-for-your-organization
  - /github/site-policy/github-insights-and-data-protection-for-your-organization
  - /insights/installing-and-configuring-github-insights/configuring-the-connection-between-github-insights-and-github-enterprise
  - /github/installing-and-configuring-github-insights/navigating-between-github-insights-and-github-enterprise
  - /github/installing-and-configuring-github-insights/enabling-a-link-between-github-insights-and-github-enterprise
  - /insights/installing-and-configuring-github-insights/enabling-a-link-between-github-insights-and-github-enterprise
  - /insights/installing-and-configuring-github-insights/managing-permissions-in-github-insights
  - /github/installing-and-configuring-github-insights/about-github-insights
  - /insights/installing-and-configuring-github-insights/about-github-insights
  - /github/installing-and-configuring-github-insights/installing-github-insights
  - /insights/installing-and-configuring-github-insights/installing-github-insights
  - /github/installing-and-configuring-github-insights/system-overview-for-github-insights
  - /insights/installing-and-configuring-github-insights/system-overview-for-github-insights
  - /github/installing-and-configuring-github-insights/updating-github-insights
  - /insights/installing-and-configuring-github-insights/updating-github-insights
  - /insights/installing-and-configuring-github-insights/about-data-in-github-insights
  - /github/installing-and-configuring-github-insights/managing-data-in-github-insights
  - /github/installing-and-configuring-github-insights/managing-settings-in-github-insights
  - /insights/installing-and-configuring-github-insights/managing-available-metrics-and-reports
  - /github/installing-and-configuring-github-insights/managing-contributors-and-teams
  - /insights/installing-and-configuring-github-insights/managing-contributors-and-teams
  - /github/installing-and-configuring-github-insights/creating-and-managing-events
  - /insights/installing-and-configuring-github-insights/managing-events
  - /github/installing-and-configuring-github-insights/creating-and-managing-goals
  - /insights/installing-and-configuring-github-insights/managing-goals
  - /github/installing-and-configuring-github-insights/managing-organizations
  - /insights/installing-and-configuring-github-insights/managing-organizations
  - /github/installing-and-configuring-github-insights/managing-repositories
  - /insights/installing-and-configuring-github-insights/managing-repositories
  - /insights/exploring-your-usage-of-github-enterprise
  - /insights/exploring-your-usage-of-github-enterprise/metrics-available-with-github-insights
  - /insights/exploring-your-usage-of-github-enterprise/navigating-between-github-enterprise-and-github-insights
  - /insights/exploring-your-usage-of-github-enterprise/setting-your-timezone-for-github-insights
  - /insights/exploring-your-usage-of-github-enterprise/viewing-key-metrics-and-reports
  - /insights
  - /insights/installing-and-configuring-github-insights/configuring-github-insights/configuring-the-connection-between-github-insights-and-github-enterprise
  - /insights/installing-and-configuring-github-insights/configuring-github-insights/enabling-a-link-between-github-insights-and-github-enterprise
  - /insights/installing-and-configuring-github-insights/configuring-github-insights
  - /insights/installing-and-configuring-github-insights/configuring-github-insights/managing-permissions-in-github-insights
  - /insights/installing-and-configuring-github-insights
  - /insights/installing-and-configuring-github-insights/installing-and-updating-github-insights/about-github-insights
  - /insights/installing-and-configuring-github-insights/installing-and-updating-github-insights
  - /insights/installing-and-configuring-github-insights/installing-and-updating-github-insights/installing-github-insights
  - /insights/installing-and-configuring-github-insights/installing-and-updating-github-insights/system-overview-for-github-insights
  - /insights/installing-and-configuring-github-insights/installing-and-updating-github-insights/updating-github-insights
  - /insights/installing-and-configuring-github-insights/managing-data-in-github-insights/about-data-in-github-insights
  - /insights/installing-and-configuring-github-insights/managing-data-in-github-insights
  - /insights/installing-and-configuring-github-insights/managing-data-in-github-insights/managing-available-metrics-and-reports
  - /insights/installing-and-configuring-github-insights/managing-data-in-github-insights/managing-contributors-and-teams
  - /insights/installing-and-configuring-github-insights/managing-data-in-github-insights/managing-events
  - /insights/installing-and-configuring-github-insights/managing-data-in-github-insights/managing-goals
  - /insights/installing-and-configuring-github-insights/managing-data-in-github-insights/managing-organizations
  - /insights/installing-and-configuring-github-insights/managing-data-in-github-insights/managing-repositories
  - /admin/configuration/configuring-your-enterprise/configuring-data-encryption-for-your-enterprise
introLinks:
  overview: '{% ifversion ghes %}/admin/overview/about-github-enterprise-server{% elsif ghae %}/admin/overview/about-github-ae{% elsif ghec %}/admin/overview/about-enterprise-accounts{% endif %}'
  Releases: '{% ifversion ghes %}/admin/all-releases{% endif %}'
changelog:
  label: enterprise
featuredLinks:
  guides:
    - '{% ifversion ghae %}/admin/user-management/auditing-users-across-your-enterprise{% endif %}'
    - /admin/identity-and-access-management/managing-iam-for-your-enterprise/about-authentication-for-your-enterprise
    - /admin/policies/enforcing-policies-for-your-enterprise/about-enterprise-policies
    - '{% ifversion ghae %}/admin/configuration/restricting-network-traffic-to-your-enterprise{% endif %}'
    - '{% ifversion ghes %}/admin/configuration/configuring-backups-on-your-appliance{% endif %}'
    - '{% ifversion ghes %}/admin/enterprise-management/creating-a-high-availability-replica{% endif %}'
    - '{% ifversion ghes %}/admin/overview/about-upgrades-to-new-releases{% endif %}'
    - '{% ifversion ghec %}/admin/user-management/managing-users-in-your-enterprise/roles-in-an-enterprise{% endif %}'
    - '{% ifversion ghec %}/admin/user-management/managing-organizations-in-your-enterprise/adding-organizations-to-your-enterprise{% endif %}'
  guideCards:
    - '{% ifversion ghes > 2.22 %} /admin/github-actions/getting-started-with-github-actions-for-github-enterprise-server {% elsif ghes < 3.0 %} /admin/enterprise-management/upgrading-github-enterprise-server {% endif %}'
    - '{% ifversion ghes > 2.22 %} /admin/packages/getting-started-with-github-packages-for-your-enterprise {% elsif ghes < 3.0 %} /admin/user-management/customizing-user-messages-for-your-enterprise {% endif %}'
    - '{% ifversion ghes > 2.22 %} /admin/configuration/configuring-advanced-security-features {% elsif ghes < 3.0 %} /admin/installation/setting-up-a-staging-instance {% endif %}'
    - '{% ifversion ghae %}/admin/configuration/initializing-github-ae{% endif %}'
    - '{% ifversion ghae %}/admin/user-management/customizing-user-messages-for-your-enterprise{% endif %}'
    - '{% ifversion ghae %}/admin/github-actions/getting-started-with-github-actions-for-github-ae{% endif %}'
    - '{% ifversion ghec %}/admin/policies/enforcing-policies-for-your-enterprise/enforcing-github-actions-policies-for-your-enterprise{% endif %}'
    - '{% ifversion ghec %}/admin/policies/enforcing-policies-for-your-enterprise/enforcing-policies-for-advanced-security-in-your-enterprise{% endif %}'
    - '{% ifversion ghec %}/admin/policies/enforcing-policies-for-your-enterprise/enforcing-repository-management-policies-in-your-enterprise{% endif %}'
  popular:
    - /admin/overview/about-github-enterprise-server
    - '{% ifversion ghae %}/admin/release-notes{% endif %}'
    - '{% ifversion ghes %}/github/getting-started-with-github/setting-up-a-trial-of-github-enterprise-server{% endif %}'
    - '{% ifversion ghes %}/admin/installation{% endif %}'
    - '{% ifversion ghae %}/admin/identity-and-access-management/configuring-authentication-and-provisioning-for-your-enterprise-using-azure-ad{% endif %}'
    - '{% ifversion ghae %}/billing/managing-billing-for-your-github-account/about-billing-for-your-enterprise{% endif %}'
    - '{% ifversion ghae %}/admin/overview/about-upgrades-to-new-releases{% endif %}'
    - '{% ifversion ghae %}/admin/configuration/configuring-your-enterprise/deploying-github-ae{% endif %}'
    - '{% ifversion ghes %}/billing/managing-your-license-for-github-enterprise{% endif %}'
    - /admin/configuration/command-line-utilities
    - '{% ifversion ghec %}/admin/configuration/configuring-your-enterprise/verifying-or-approving-a-domain-for-your-enterprise{% endif %}'
    - '{% ifversion ghec %}/admin/monitoring-activity-in-your-enterprise/reviewing-audit-logs-for-your-enterprise/about-the-audit-log-for-your-enterprise{% endif %}'
    - '{% ifversion ghec %}/admin/monitoring-activity-in-your-enterprise/exploring-user-activity/managing-global-webhooks{% endif %}'
    - /billing/managing-your-license-for-github-enterprise/using-visual-studio-subscription-with-github-enterprise/setting-up-visual-studio-subscription-with-github-enterprise
    - /admin/enterprise-support/about-github-enterprise-support
  videos:
    - title: GitHub in the Enterprise – Maya Ross
      href: 'https://www.youtube-nocookie.com/embed/1-i39RqaxRs'
    - title: What's new for GitHub Enterprise – Jarryd McCree
      href: 'https://www.youtube-nocookie.com/embed/ZZviWZgrqhM'
    - title: Enforcing information security policy through GitHub Enterprise – Thomas Worley
      href: 'https://www.youtube-nocookie.com/embed/DCu-ZTT7WTI'
  videosHeading: GitHub Universe 2021 videos
layout: product-landing
versions:
  ghec: '*'
  ghes: '*'
  ghae: '*'
children:
  - /overview
  - /installation
  - /configuration
  - /identity-and-access-management
  - /user-management
  - /policies
  - /monitoring-activity-in-your-enterprise
  - /enterprise-management
  - /github-actions
  - /packages
  - /code-security
  - /guides
  - /release-notes
  - /all-releases
ms.openlocfilehash: ebd1473538d42928ff3d9abb3c0e2bd9f12767f5
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/05/2022
ms.locfileid: '146454171'
---

