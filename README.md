# -criar-Inst-ncia-Gerenciada-de-SQL-do-Azure

Assinatura: selecione a assinatura.

Grupo de recursos: escolha um existente ou crie um novo.

Nome da instância: defina o nome único.

Região: escolha a mais próxima do seu uso.

Camada de serviço: escolha entre:

General Purpose (uso geral, custo menor).

Business Critical (alta performance, baixa latência).

🔹 3. Aba Configuração

Defina:

Número de vCores.

Quantidade de armazenamento.

Configure o SQL collation se necessário.

🔹 4. Aba Rede

A Instância Gerenciada de SQL precisa estar em uma VNET.

Escolha a rede virtual e a sub-rede.

Configure conectividade (pode habilitar acesso público ou somente privado).

🔹 5. Aba Segurança

Defina autenticação:

Somente SQL (usuário/senha).

Azure AD + SQL (mais seguro).

Ative ou não Azure Defender e backup automático.

🔹 6. Revisar + Criar

O Azure valida as configurações.

Clique em Criar.
