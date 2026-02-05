CNPJ CPF Multinacional

**O que testar?**

* Garantir que, quando a empresa tiver **"identificação fiscal multinacional" habilitada**, o componente **não aplique formatação automática** (máscara) no campo CPF/CNPJ.

* Ok. Ele não aplica máscara.

* Garantir que, quando a empresa tiver **"identificação fiscal multinacional" habilitada**, o campo **não valide** CPF/CNPJ local (não mostrar erro "inválido" ao sair do campo).

  ok

* Garantir que, quando a empresa tiver **"identificação fiscal multinacional" habilitada**, o componente **não faça consultas à API de consulta CNPJ/CPF** (nenhuma chamada de rede para essa API).

  Ok

* Garantir que, quando a empresa tiver **"identificação fiscal multinacional" habilitada**, o campo permita **texto livre** (aceita letras, símbolos e números) dentro do limite de 18 caracteres.

  * Ok

* Garantir que, quando a empresa tiver **"identificação fiscal multinacional" habilitada**, o campo **tenha limite máximo de 18 caracteres** (não permite inserir mais que 18).

  * Ok

* Garantir que, ao **editar um cadastro existente** (que já tem CPF/CNPJ formatado), e a empresa estiver com a chave habilitada, o componente **não remova ou reformatte automaticamente** o valor — deve permanecer em texto livre conforme o usuário editar.

  * Ok

* Garantir que, com comportamento padrão (chave desabilitada), campos com CPF/CNPJ inválido **mostrem mensagem de erro** ao perder foco e bloqueiem submissão quando for regra bloquear.  
  * Ok

