<div align='center'>

### <i> Criando um Monitoramento de Custos no Data Factory no Microsoft Azure. </i>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Microsoft-Teams-Animated-Emojis/master/Emojis/Travel%20and%20places/Star.png" alt="Hand with Fingers Splayed Light Skin Tone" width="20" height="20" />
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Microsoft-Teams-Animated-Emojis/master/Emojis/Hand%20gestures/Folded%20Hands%20Light%20Skin%20Tone.png" alt="Hand with Fingers Splayed Light Skin Tone" width="20" height="20" />

<br />

<img width="500" align="center" src="../img/azure.png">

</div>

<br />

<div align='left'>

> #### 🎯 OBJETIVO DO PROJETO

- Este projeto apresenta uma abordagem prática para explorar o ambiente Azure utilizando uma conta gratuita de estudante.
- A proposta é orientar o usuário desde os primeiros passos na plataforma até a criação de recursos completos, com foco especial na implantação e configuração do Azure Data Factory (ADF).

---

> #### ✍️ Pré-requisito

<div> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔹 Uma conta gratuita no Azure for Students ou Azure Free Tier. </div>
<div> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔹 Acesso ao Azure Portal. </div>

---

<br />

<div align="center">

### PASSO A PASSO DA CRIAÇÃO DO DESAFIO

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People%20with%20activities/Woman%20Walking%20Medium%20Skin%20Tone.png" alt="Woman Walking Medium Skin Tone" width="45" height="45" />
</div>

<br />

---

#### 1° - Início da Criação de Recursos

- Todo recurso no Azure deve estar associado a um <strong><em>Grupo de Recursos</em></strong>, que serve para organizar serviços relacionados ao mesmo projeto.
- O Grupo de Recursos é essencial para <u>gestão, manutenção, controle de custos e organização</u>.
- Cada recurso deve obrigatoriamente pertencer a **um único grupo de recursos**.

#### 2° - Padrão de Nomenclatura no Azure

- Uso de **abreviações padronizadas**:

  - `adf` → Azure Data Factory
  - `cosmos` → Azure Cosmos DB database
  - `vm` → Virtual machine
  - `sqldb` → Azure SQL database

- O sistema faz <b>validação automática</b> dos nomes durante a criação.

#### 3° - Escolha da Localização (Region/Location)

- A escolha da região depende de:

  - Requisitos de latência;
  - Normas de compliance;
  - Exigências do cliente.

- Regiões comuns:
  - `Brazil South` → hospedagem nacional, para clientes com essa exigência, sendo que tem maior custo;
  - `East US` ou `West Europe` → melhor custo-benefício.

#### 4. Configurações Avançadas na Criação

- <b>Integração com DevOps</b> (GitHub, Azure Repos);
- Configurações de <b>rede, segurança e criptografia</b>;
- Uso de **Tags** para organização:
  - Ex: `projeto = financeiro`, `ambiente = produção`.

#### 5° - Validação e Implantação do Recurso

- Validação automática feita pelo Azure;
- Resumo final da configuração exibido antes da criação.

#### 6° - Templates e Automação (ARM Templates)

- Geração de templates JSON com base na interface gráfica;
- Ideal para replicação e padronização de configurações.

#### 7° - Acompanhamento da Implantação

- Notificações em tempo real do progresso da criação;
- Detalhamento dos passos e provisionamentos executados.

#### 8° - Acesso ao Recurso Criado

- Após a criação, o recurso já pode ser acessado e gerenciado diretamente.

---

<br />

### ✔️ Gerenciar as funcionalidades

<br />

---

#### 1° - Ver Informações do Recurso

- Acesse a <b>visão geral</b> para consultar:
  - Nome;
  - Tipo;
  - Localização;
  - Status;
  - Logs de atividade.

#### 2° - Configurar Controle de Acesso (IAM)

- Vá até <b>"Controle de Acesso (IAM)"</b>;
- Atribua funções como `Leitor`, `Contribuidor`;
- Selecione o usuário e aplique a permissão.

#### 3° - Gerenciar Marcações (Tags)

- Crie ou edite tags para organização:
  - Exemplo: `Ambiente = Produção`, `Dono = Equipe X`.

#### 4° - Aplicar Bloqueios (Locks)

- Bloqueios disponíveis:
  - <b>Somente leitura</b>;
  - <b>Impedir exclusão</b>.

#### 5° - Personalizar o Dashboard

- Fixe gráficos e recursos no painel;
- Crie dashboards separados por equipe ou projeto;
- Edite visualmente tamanho, posição e cores.

#### 6° - Utilizar Notificações

- Acompanhe notificações como:
  - Sucesso na criação;
  - Erros;
  - Alertas de uso e performance.

#### 7° - Acessar Configurações Gerais

- Ajuste:
  - Idioma;
  - Tema (claro/escuro);
  - Região;
  - Preferências de notificação.

#### 8° - Usar Suporte e Feedback

- Acesse o centro de ajuda;
- Abra chamados;
- Envie sugestões e feedbacks para a Microsoft.

#### 9° - Utilizar o Cloud Shell

- Execute comandos com:

  - PowerShell;
  - Bash;
  - Python;

- Ideal para automações e práticas de IaC (Infraestrutura como Código).

#### 10° - Explorar Documentação Integrada

- Acesse a documentação oficial diretamente pelo portal;
- Excelente para aprofundamento e aprendizado contínuo.

#### 11° - Usar o Assistente com IA (Copilot)

- Use o Copilot para:
  - Criar recursos;
  - Gerar códigos;
  - Entender configurações;
  - Obter sugestões automatizadas e inteligentes.

---

> #### 🔗 Link para Administrar as aplicações

- [Microsoft Azure](https://portal.azure.com/#home)

---

> #### 🛠️ Ferramentas utilizadas

- Microsoft Azure (🌍 Plataforma Cloud)
- Azure Data Factory (🛠 Orquestração de Dados)
- VSCode

---

> #### 🧩 Tipo de desafio

- Básico.

---

> #### 🏆 Créditos

<div align="left"> <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Eyes.png" alt="Hand with Fingers Splayed Light Skin Tone" width="20" height="20" /> - ver mais em <a href="https://github.com/angelicakadja">AK</a>.<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand%20Medium%20Skin%20Tone.png" alt="Hand with Fingers Splayed Light Skin Tone" width="20" height="20" /></div>

</div>
