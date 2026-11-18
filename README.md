# Vynvia para Cursor

Prospecção B2B no Brasil pelo agente do Cursor. Com o plugin da Vynvia, o agente busca empresas na região que você quiser, escreve a abordagem com os dados de cada uma, envia pelo WhatsApp no ritmo seguro da sua conta e acompanha follow-ups e respostas. Tudo fica registrado na Vynvia.

## O que vem no plugin

- **Servidor MCP `vynvia`** (`mcp.json`): o servidor remoto da Vynvia, `https://www.vynvia.com.br/api/mcp`, por HTTP, com login pela sua conta (OAuth). Não há chave nem token para configurar.
- **Skills** (`skills/`):
  - `prospectar-nicho`: escolhe o nicho, busca, prioriza os melhores leads pelo perfil da conta e pelo limite do dia, escreve, revisa e envia o primeiro contato;
  - `follow-ups-do-dia`: compromissos, triagem de quem está esperando desfecho (respondeu, não respondeu, encerrou), retornos, primeiros contatos, reativação de quem ficou sem responder (quando você pedir) e um resumo no fim;
  - `responder-lead`: registra a resposta, classifica o que o lead quer e escreve a continuação certa para cada caso;
  - `o-que-esta-funcionando`: balanço da prospecção por nicho e região, com a recomendação da próxima busca.

## O que você precisa

Uma conta na [Vynvia](https://www.vynvia.com.br). A conexão funciona em todos os planos, inclusive o grátis; as buscas e as mensagens gastam a cota do plano. Na primeira chamada, o Cursor abre a tela de autorização da Vynvia para você entrar e permitir o acesso.

## Sem o plugin

Dá para usar só o servidor MCP. No Cursor, adicione um servidor MCP do tipo HTTP com o endereço `https://www.vynvia.com.br/api/mcp` e autorize na página da Vynvia que abrir.

## Exemplos

- "Busque escritórios de contabilidade em Juiz de Fora - MG e me mostre as primeiras mensagens."
- "O que eu tenho pra hoje na Vynvia?"
- "A Clínica Sorriso respondeu: 'pode me mandar mais detalhes?'. Como respondo?"
- "Como está a minha prospecção? Onde eu busco a seguir?"
- "Quem eu posso reativar?"

## Política de privacidade

O plugin não guarda dados: ele liga o agente ao servidor da Vynvia, que trata os dados conforme a [Política de Privacidade](https://www.vynvia.com.br/privacidade). Em resumo:

- **Coleta**: os dados da sua conta e os das empresas que você busca (dados públicos de pessoas jurídicas).
- **Uso e armazenamento**: para buscar, escrever e registrar a prospecção na sua conta, em servidores no Brasil.
- **Compartilhamento**: com os provedores necessários ao serviço (hospedagem, banco de dados, modelos de IA), sem venda de dados.
- **Retenção**: enquanto a conta estiver ativa, e pelo prazo previsto na política depois do encerramento.
- **Contato**: privacidade@vynvia.com.br.

A IA conectada nunca recebe o telefone dos leads: o envio pelo WhatsApp sai por um link que a Vynvia monta, dentro do limite diário da conta.

## Suporte

suporte@vynvia.com.br · [vynvia.com.br/mcp](https://www.vynvia.com.br/mcp)

## Licença

MIT
