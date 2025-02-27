# Componentes de Arquitetura do Azure

### Componentes de Arquitetura do Azure

- Como o Azure é amplamente utilizado e pertence a uma empresa consolidada, existem acessos aos recursos em diversas regiões do mundo, isso deve ser considerado quando vamos escolher um recurso para a empresa fazer o acesso com base em sua proximidade.

- A principal vantagem em escolher um acesso próximo a empresa, é a redução do delay na comunicação.

- O preço para alocar recursos não é tabelado, assim fazendo com que algumas regiões fiquem mais acessíveis financeiramente do que outras.

- Os recursos podem existir somente em algumas regiões.

- O Azure está presente em 60 regiões e representa mais de 140 países.

- As regiões são compostas de um ou mais datacenters. Eles oferecem flexibilidade e escala para reduzir a latência do cliente.

- As regiões preservam a residência dos dados com uma oferta abrangente de conformidade.

- A região é formada por um grupo de datacenters.

- Toda a responsabilidade sobre o funcionamento das regiões é da Microsoft(provider).

- Fornece proteção contra tempo de inatividade devido a falha do datacenter.

- Separa fisicamente os datacenters dentro da mesma região.

### Entendendo Pares de Região e Grupos de Recursos

- No mínimo 300 milhas de separação entre pares de regiões.

- Replicação automática para alguns serviços.

- Recuperação de região priorizada em caso de interrupção.

- Toda região possui uma região par, para servir de desastre recovery.

- Regiões soberanas do Azure
- Regiões exclusivas.
  - Região governamental dos EUA que atende as necessidades militares.
  - Localizada somente dentro dos EUA.
  - Acesso somente para contas verificadas e autorizadas.
- Azure China
  - Provedor estrangeiro de nuvem pública da China em conformidade com a regulamentação do governo chinês.
  - Não está disponível para usuários não verificados e autorizados.
  - É gerenciada pela empresa 21Vianet.
  - Todos os dados permanecem dentro da China.
- Recursos para as regiões
    - Máquinas virtuais.
    - Contas de armazenamento.
    - Redes virtuais.
    - Serviços de aplicativos.
    - Banco de dados SQL.
    - Funções.
    - Recursos não precisam estar dentro da mesma região.
    - Um grupo de recursos é um contêiner que você usa para gerenciar e agregar recursos em uma única unidade.
    - Recursos podem existir em somente um grupo de recursos.
    - Os recursos podem ser movidos para diferentes grupos de recursos.
    - Aplicativos podem utilizar vários grupos de recursos.

### Assinatura da Azure e Grupos de Gerenciamentos

- Assinatura do desenvolvimento
    - reservada para a equipe de desenvolvimento.
      
- Assinatura de testes
    - destinada para a equipe de testes.
      
- Assinatura de produção
    - produto final para os clientes.

- Uma conta pode ter diversas assinaturas, mas uma assinatura está associada a somente uma conta.

- Para cada assinatura, terá uma fatura.

- Uma vantagem em separar as assinaturas é uma melhor organização de custos.

- Limite do controle de acesso: gerenciar e controlar o acesso aos recursos que os usuários podem provisionar com assinaturas específicas.

- Grupos de gerenciamento podem incluir várias assinaturas do Azure.

- As assinaturas herdam as condições aplicadas ao grupo de gerenciamento.
  
  
