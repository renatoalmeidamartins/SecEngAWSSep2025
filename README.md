# SecEngAWSSep2025


## Avaliação do curso
- Acesse [aws.training](https://aws.training)
- Clique em  "sign in" e faça log in com a mesma conta usada para acessar o material e laboratório
- Vá no topo, à direita, em "Minha Conta", e então "Transcript", clique na seção de "Arquivado" (acesso direto nesta URL https://www.aws.training/Account/Transcript/Archived)
- Deve estar aí um botão para avaliar o curso.

## Links de material didático e acesso às classes
- [Link para entrada na reunião](https://awsvirtual.webex.com/awsvirtual/j.php?MTID=m8fb442b63a0890097a0b13f90bbd7104)
- [Acesso ao ambiente de laboratório](https://us-east-1.student.classrooms.aws.training/class/ilt%23gzaKY6Bgic7HXmgfzNVnzC)
- [Skill builder](https://skillbuilder.aws/learn)
- [Security Fundamentals](https://skillbuilder.aws/learn/S2N5PM41ZK/aws-security-fundamentals-second-edition/E71QQGTCRZ), curso gratuito no Skill Builder, listado como pre-req do curso
- [Catálogo de cursos AWS ministrador por instrutor](https://releases.awstc.com/)

### Links do dia 1
- [Parodia de My shot, com Lambda reduzindo seu ops](https://www.youtube.com/watch?v=zMua0cuhFnc)
- [Boas práticas para criação de OUs em umna organização](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_ous_best_practices.html)
- [OWASP, boa ferramenta de código aberto para modelagem de ameaças](https://owasp.org/www-project-threat-dragon/)
- [Endpoints e quotas de serviços AWS](https://docs.aws.amazon.com/general/latest/gr/aws-service-information.html)
- [Assinando pedidos para a AWS (SIGv4)](https://docs.aws.amazon.com/AmazonS3/latest/API/sig-v4-authenticating-requests.html)
- [Gerador de politicas AWS](https://awspolicygen.s3.amazonaws.com/policygen.html)
- Serviços gratuitos na AWS:
  - [Antes de 15 de julho de 2025](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-free-tier.html)
  - [Depois de 15 de julho de 2025](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/free-tier.html)
- [Boas práticas com usuário root](https://docs.aws.amazon.com/IAM/latest/UserGuide/root-user-best-practices.html)
- [Atividades que só podem ser feitas pelo uusário root](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html#root-user-tasks)
- [IAM Roles Anywhere](https://docs.aws.amazon.com/rolesanywhere/latest/userguide/introduction.html)
- [Condições disponíveis em políticas](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_elements_condition.html)
- [Exemplo de uso de política de sessão](https://aws.amazon.com/blogs/security/create-fine-grained-session-permissions-using-iam-managed-policies/)
- [Simulador de políticas de IAM](https://policysim.aws.amazon.com/home/index.jsp)
- Limites de permissão:
  - [Documentação geral](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html#access_policies_boundaries-delegate)
  - [Exemplos de uso](https://aws.amazon.com/blogs/security/when-and-where-to-use-iam-permissions-boundaries/)
  - [Exemplo de desenvolvedores de aplicações criando roles](https://github.com/aws-samples/example-permissions-boundary)
- [Cloudtrail lake](https://aws.amazon.com/blogs/mt/announcing-aws-cloudtrail-lake-a-managed-audit-and-security-lake/)
- [Apenas root user pode ativar MFA delete](https://docs.aws.amazon.com/AmazonS3/latest/userguide/MultiFactorAuthenticationDelete.html)
- [Uso de trust policies com roles](https://aws.amazon.com/blogs/security/how-to-use-trust-policies-with-iam-roles/)
- [Sequencia de avaliação de políticas](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_evaluation-logic.html)
- [Catálogo de controles do Control Tower](https://docs.aws.amazon.com/controltower/latest/controlreference/controls-reference.html)
- [Migrando de landing zone legadas para Control tower](https://docs.aws.amazon.com/prescriptive-guidance/latest/aws-control-tower/introduction.html)
- [Lancamento dos "planos" do Cognito](https://aws.amazon.com/blogs/aws/improve-your-app-authentication-workflow-with-new-amazon-cognito-features/)
### Links do dia 2
- [Configuração do Identity Center com Entra](https://docs.aws.amazon.com/singlesignon/latest/userguide/idp-microsoft-entra.html)
- [Exemplo de como uma Managed Identity do Azure - conta associável a, entre outros, VMs - pode assumir roles na AWS](https://aws.amazon.com/blogs/security/how-to-access-aws-resources-from-microsoft-entra-id-tenants-using-aws-security-token-service/)
- [Uso do SDK de criptografia em Java](https://github.com/aws/amazon-s3-encryption-client-java)
- [Chaves KMS multi-região](https://docs.aws.amazon.com/kms/latest/developerguide/mrk-how-it-works.html)
- [Criação de grants de KMS](https://docs.aws.amazon.com/kms/latest/developerguide/grants.html)
- [Comando create-grant na CLI de KMS](https://docs.aws.amazon.com/cli/latest/reference/kms/create-grant.html)
- [Rotação manual de chave, atenção à vantagem do uso de alias](https://docs.aws.amazon.com/kms/latest/developerguide/rotate-keys-manually.html)
- [Rotação automática de chave, veja que o id não muda](https://docs.aws.amazon.com/kms/latest/developerguide/rotate-keys.html)
- Armazenamento externo de chaves:
  - [Anúncio do início do suporte em 2022](https://aws.amazon.com/blogs/aws/announcing-aws-kms-external-key-store-xks/)
  - [Detalhes do funcionamento](https://docs.aws.amazon.com/kms/latest/developerguide/keystore-external.html)
- [FIPS 140-2, padrão para dispositivos criptográficos publicado pelo NIST](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.140-2.pdf)
- [KMS "puro" também é FIPS 140-2 nível 3 (antes privilégio do CloudHSM)](https://aws.amazon.com/blogs/security/aws-kms-now-fips-140-2-level-3-what-does-this-mean-for-you/)
- [Funções de rotação de segredos com Secrets Manager](https://docs.aws.amazon.com/secretsmanager/latest/userguide/reference_available-rotation-templates.html)
- [Uso de bucket keys do KMS, no S3, para reduzir custo de consumo de chaves de KMS em objetos no S3, em até 99%](https://aws.amazon.com/blogs/storage/reducing-aws-key-management-service-costs-by-up-to-99-with-s3-bucket-keys/)
- [Criação de tipos de dados "customizados" no Macie](https://docs.aws.amazon.com/macie/latest/user/cdis-create.html)
- [Exemplos do uso de S3 Server-Side-Encryption, com chave fornecida pelo cliente](https://docs.aws.amazon.com/AmazonS3/latest/userguide/ServerSideEncryptionCustomerKeys.html)
- [URLs pre-assinadas no S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/ShareObjectPreSignedURL.html)
- [Anuncio de replicação para multiplos buckets/regiões no S3](https://aws.amazon.com/blogs/aws/new-amazon-s3-replication-adds-support-for-multiple-destination-buckets/)
- ["Convertendo" um banco RDS não-criptografado para criptografado (utiliza snapshot e recupera em uma instância nova)](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/encrypt-an-existing-amazon-rds-for-postgresql-db-instance.html)
- [Criptografia em trânsito em RDS é possível via option groups](https://aws.amazon.com/blogs/database/customizing-security-parameters-on-amazon-rds-for-sql-server/)
- [Exemplo de política para exigir acesso HTTPS em bucket S3, se aplicaria de forma similar a Dynamo](https://docs.aws.amazon.com/AmazonS3/latest/userguide/example-bucket-policies.html#example-bucket-policies-HTTP-HTTPS)
- Fine-Grained access control no DynamoDB
  - [Artigo original](https://aws.amazon.com/blogs/aws/fine-grained-access-control-for-amazon-dynamodb/)
  - [Documentação atual](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/specifying-conditions.html)
- [Grupos de regras com assinatura de ameaças gerenciada pela AWS](https://docs.aws.amazon.com/network-firewall/latest/developerguide/aws-managed-rule-groups-threat-signature.html)
- [Anúncio do Gateway Load Balancer - atenção aos parceiros suportados já em 2020](https://aws.amazon.com/blogs/aws/introducing-aws-gateway-load-balancer-easy-deployment-scalability-and-high-availability-for-partner-appliances/)
- [Definindo políticas no bucket para acesso do Cloudfront - OAC, atual x OAI, legado](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-restricting-access-to-s3.html)
- [Shuffle sharding em DNS](https://aws.amazon.com/blogs/architecture/shuffle-sharding-massive-and-magical-fault-isolation/)
- [Políticas de roteamento do Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)
- [O pequeno Bobby tables, exemplo clássico de injeção de SQL](https://xkcd.com/327/)
- Infos de Shield
  - [Recursos principais do Shield Advanced](https://docs.aws.amazon.com/waf/latest/developerguide/ddos-advanced-summary-capabilities.html)
  - [Grupos de proteção no Shield](https://docs.aws.amazon.com/waf/latest/developerguide/ddos-protection-groups.html)
  - [Formas de mitigação usadas no Shield](https://docs.aws.amazon.com/waf/latest/developerguide/ddos-event-mitigation.html)
- [Anúncio do Network Firewall](https://aws.amazon.com/blogs/aws/aws-network-firewall-new-managed-firewall-service-in-vpc/)
- [Apresentação sobre o Firewall manager](https://pages.awscloud.com/rs/112-TZM-766/images/2020_0525-SID_Slide-Deck.pdf)
- [Otimizando o uso do Firewall Manager, especificamente com regras WAF](https://aws.amazon.com/blogs/security/aws-firewall-manager-retrofitting-harmonizing-central-security-with-application-team-flexibility/)
- [Anúncio do Firewall Manager em 2018, atenção pois hoje suporta muito mais recursos](https://aws.amazon.com/blogs/aws/aws-firewall-manager-central-management-for-your-web-application-portfolio/)

### Links do dia 3
- [Conformance packs do AWS Config](https://docs.aws.amazon.com/config/latest/developerguide/conformancepack-sample-templates.html)
- [Formatos de arquivos suportados no Macie](https://docs.aws.amazon.com/macie/latest/user/discovery-supported-storage.html)
- [Criação da role necessária para execução de automações](https://docs.aws.amazon.com/systems-manager/latest/userguide/automation-setup-iam.html)
- [Ações suportadas em documentos de automação do Systems Manager](https://docs.aws.amazon.com/systems-manager/latest/userguide/automation-actions.html)
- [Anúncio do suporte de regras de AWS Config usando Guard como linguagem](https://aws.amazon.com/blogs/mt/announcing-aws-config-custom-rules-using-guard-custom-policy/)
- [Repo com vários artefatos de doc e exemplos associados a Guard](https://github.com/aws-cloudformation/cloudformation-guard)
- [Repo com diversas regras de Guard definidas](https://github.com/aws-cloudformation/aws-guard-rules-registry)
- [Usando EventBridge para filtrar eventos originados no GuardDuty](https://docs.aws.amazon.com/guardduty/latest/ug/guardduty_findings_eventbridge.html)
- [Anuncio do suporte de eventos de parceiros integrados ao EventBridge](https://aws.amazon.com/blogs/aws/amazon-eventbridge-event-driven-aws-integration-for-your-saas-applications/)
- [Anuncio do preview do Security Lake](https://aws.amazon.com/about-aws/whats-new/2022/11/amazon-security-lake-preview/)
- [Queries pre-definidas no Athena, para consultas relacionadas a segurança - requer o deploy de um modelo do CloudFormation](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-run-athena-query.html)
- [Centralização de logs usando OpenSearch - solução de exemplo](https://aws.amazon.com/solutions/implementations/centralized-logging-with-opensearch)
- [Inspeção de tráfego sob demanda - em resposta a um evento do Guard Duty](https://aws.amazon.com/blogs/networking-and-content-delivery/using-vpc-traffic-mirroring-to-monitor-and-secure-your-aws-infrastructure/)
