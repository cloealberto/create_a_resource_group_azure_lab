# 🌐 LAB de Criação de Resource Group e VNET

Este projeto é um laboratório prático de criação de **Resource Groups** e **Virtual Networks (VNETs)** diretamente pelo **Portal do Azure**. Ele visa demonstrar como configurar e gerenciar esses recursos essenciais para a infraestrutura em nuvem de forma visual e intuitiva.

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter:

- Uma conta ativa no [Azure](https://azure.microsoft.com/) com permissões para criar recursos.
- Acesso ao [Portal do Azure](https://portal.azure.com/).

## 🚀 Iniciando o LAB

### 1. 📦 Criação do Resource Group

1. No Portal do Azure, navegue até **Resource Groups**.
2. Clique em **Create**.
3. Preencha as seguintes informações:
   - **Resource Group Name**: Escolha um nome para o grupo, como `AZ900_LAB`.
   - **Region**: Selecione a localização desejada (por exemplo, `East US 2`).
4. Clique em **Review + Create** e, em seguida, em **Create**.

### 2. 🌍 Criação da VNET

1. No Portal do Azure, navegue até **Virtual Networks**.
2. Clique em **Create**.
3. Preencha os campos:
   - **Subscription**: Escolha a assinatura correta.
   - **Resource Group**: Selecione o grupo que você criou (`AZ900_LAB`).
   - **Name**: Escolha um nome para a VNET, como `VNET1`.
   - **Region**: Aqui usamos uma região diferente do Resource Group (`Brazil South`)
4. Clique em **Review + Create** e, em seguida, em **Create**.

### 3. 🔄 Verificando os Recursos

Após criar os recursos, verifique se tudo foi configurado corretamente:

1. No Portal do Azure, vá até **Resource Groups** e selecione o grupo que você criou.
2. Certifique-se de que sua **Virtual Network** aparece na lista de recursos.
3. Verifique as configurações de rede e subnets dentro da **VNET**.

### 4. 🧹 Limpando os Recursos

Após concluir o LAB, é importante remover os recursos para evitar cobranças indesejadas:

1. No Portal do Azure, navegue até **Resource Groups**.
2. Selecione o Resource Group que você criou.
3. Clique em **Delete Resource Group** e confirme o nome para remover todos os recursos associados.

## 📖 Documentação Adicional

- [Documentação sobre Resource Groups](https://learn.microsoft.com/azure/azure-resource-manager/management/manage-resource-groups-portal)
- [Documentação sobre Virtual Networks](https://learn.microsoft.com/azure/virtual-network/virtual-networks-overview)

## 🤝 Contribuição

Se tiver sugestões ou encontrar algum problema, sinta-se à vontade para abrir _issues_ ou enviar melhorias.

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

*Visite meu perfil no Linkedin: [Cloe Alberto de Souza](https://linkedin.com/in/cloealberto)*
