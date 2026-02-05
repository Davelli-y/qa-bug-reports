## **✅ Casos de Teste – | Visualização de Pedidos Finalizados no Flutter**

1. **Verificar existência da chave de configuração**

   - [x] ~~Confirmar se a chave `abrirPedidoJaExportadoComFlutter` foi criada no banco com valor padrão **Não** após a migration.~~

2. **Verificar atualização automática para novas empresas**

   - [x] ~~Criar nova empresa e validar se a trigger define o valor padrão **Sim** para a chave.~~

3. **Validar abertura de pedido finalizado com configuração \= Não**

   - [x] ~~Configurar a empresa com valor **Não**.~~

   - [x] ~~Abrir um pedido finalizado.~~

   - [x] ~~O sistema deve abrir na **tela antiga de pedidos exportados**.~~

4. **Validar abertura de pedido finalizado com configuração \= Sim**

   - [x] ~~Configurar a empresa com valor **Sim**.~~

   - [x] ~~Abrir um pedido finalizado.~~

   - [x] ~~O sistema deve abrir na **tela Flutter**, em modo **somente visualização**.~~

5. **Verificar exibição de políticas aplicadas nos itens (Flutter)**

   - [x] ~~No pedido aberto via Flutter, validar se cada item exibe suas **políticas comerciais aplicadas** corretamente.~~

6. **Validar comportamento em modo somente visualização**

   - [x] ~~O sistema deve bloquear edição e manter modo **read-only**.~~

7. **Validar comportamento para pedidos não finalizados**

   - [x] ~~Abrir um pedido ainda **não finalizado**.~~

   - [x] ~~O sistema deve seguir comportamento normal de **edição Flutter** (sem redirecionamento para pedidos exportados).~~

8. **Validar comportamento para empresas antigas sem configuração**

   - [x] ~~Testar uma empresa criada antes da migration.~~

   - [x] ~~Abrir pedido finalizado.~~

   - [x] ~~O sistema deve assumir comportamento padrão (abrir tela antiga).~~

