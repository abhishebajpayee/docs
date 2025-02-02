---
title: Sobre a segurança da cadeia de suprimento da sua empresa
intro: Você pode habilitar recursos que ajudam seus desenvolvedores a entender e atualizar as dependências das quais o código do seu projeto depende.
shortTitle: Sobre a segurança da cadeia de suprimento
permissions: ''
versions:
  ghes: '*'
  ghae: issue-4864
type: how_to
topics:
  - Enterprise
  - Security
  - Dependency graph
---

You can allow users to identify their projects' dependencies by {% ifversion ghes %}enabling{% elsif ghae %}using{% endif %} the dependency graph for {% data variables.product.product_location %}. For more information, see "{% ifversion ghes %}[Enabling the dependency graph for your enterprise](/admin/code-security/managing-supply-chain-security-for-your-enterprise/enabling-the-dependency-graph-for-your-enterprise){% elsif ghae %}[About the dependency graph](/code-security/supply-chain-security/understanding-your-software-supply-chain/about-the-dependency-graph){% endif %}."

Você também pode permitir que os usuários de {% data variables.product.product_location %} encontrem e corrijam vulnerabilidades nas dependências do seu código, habilitando {% data variables.product.prodname_dependabot_alerts %}{% ifversion ghes > 3.2 %} e {% data variables.product.prodname_dependabot_updates %}{% endif %}. Para obter mais informações, consulte "[Habilitar {% data variables.product.prodname_dependabot %} para a sua empresa](/admin/configuration/configuring-github-connect/enabling-dependabot-for-your-enterprise)."

Depois de habilitar o {% data variables.product.prodname_dependabot_alerts %}, você poderá ver os dados da vulnerabilidade de {% data variables.product.prodname_advisory_database %} em {% data variables.product.product_location %} e sincronizar manualmente os dados. Para obter mais informações, consulte[Visualizando os dados de vulnerabilidade da sua empresa](/admin/code-security/managing-supply-chain-security-for-your-enterprise/viewing-the-vulnerability-data-for-your-enterprise)".
