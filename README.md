# Microsoft_Azure_Gerenciando_Politicas_Acessos

# Gerenciando Políticas | Azure 

## 1- Portal de Confiança do Azure

O Portal de Confiança do Azure é uma plataforma que oferece visibilidade e controle sobre a conformidade e a segurança dos seus recursos no Azure. Ele fornece informações sobre práticas recomendadas, conformidade com normas e a segurança dos dados. Para acessar e utilizar o Portal de Confiança, siga estes passos:

**Acesse o Portal de Confiança**:
 
Este portal facilita a gestão de políticas de conformidade e ajuda a garantir que seus recursos estejam alinhados com as melhores práticas de segurança e as exigências regulatórias. O Portal de Confiança inclui uma visão geral das certificações e do cumprimento de normas do Azure, permitindo que você avalie rapidamente o estado de conformidade e identifique áreas que necessitam de atenção.

## 2- Purview do Azure

O Purview do Azure permite que você experimente novos serviços e funcionalidades antes de serem lançados oficialmente. Para começar a usar um recurso em Purview, siga estes passos:

1- **Acesse o Portal do Azure**:
   - Faça login no [Portal do Azure](https://portal.azure.com/).
   
2- **Navegue para 'Todas as funções'**:
   - No menu de navegação à esquerda, selecione **"Todos os serviços"** e procure por recursos em Purview.

3- **Selecione e Ative o Purview**:
   - Escolha o recurso que você deseja experimentar e siga as instruções para ativar o Purview.
   - Esteja ciente de que recursos em Purview podem não ser totalmente estáveis e podem ter funcionalidades limitadas.
 
## 3- Bloqueio de Recursos

O Bloqueio de Recursos no Azure permite que você impeça a exclusão ou modificação acidental de recursos críticos. Para criar um bloqueio de recurso, siga estes passos:

1- **Navegue até o Recurso**:
   - No menu de navegação à esquerda, selecione **"Recursos"** e escolha o recurso que você deseja proteger.

2- **Configure o Bloqueio**:
   - No painel do recurso, selecione **"Bloqueios"**.
   - Clique em **"Adicionar bloqueio"** e escolha um tipo de bloqueio:
     - **ReadOnly**: Impede alterações, mas permite leitura.
     - **CanNotDelete**: Impede exclusão do recurso.

3- **Defina o Nome e Descrição**:
   - Insira um nome e uma descrição para o bloqueio.
   - Clique em **"Salvar"** para aplicar o bloqueio ao recurso.
   

## 4- Gerenciamento de Policies

O gerenciamento de políticas no Azure ajuda a garantir que os recursos estejam em conformidade com as normas e regulamentos da sua organização. Para criar uma política, siga estes passos:

1- **Navegue para 'Azure Policy'**:
   - No menu de navegação à esquerda, selecione **"Azure Policy"**.

2- **Crie uma Nova Política**:
   - Selecione **"Definitions"** e clique em **"New Policy Definition"**.
   - Defina os critérios e a política que você deseja aplicar.

3- **Aplique a Política**:
   - Após definir a política, selecione **"Assignments"** e clique em **"Assign Policy"**.
   - Escolha a política criada e defina o escopo de aplicação (como um grupo de recursos ou uma assinatura).

     Importante: Selecione se quer deixar ativado a policy ou não.
   
4- **Revise e Salve**:
   - Revise os detalhes e clique em **"Create"** para aplicar a política.

---
