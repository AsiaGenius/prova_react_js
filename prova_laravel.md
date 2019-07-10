# Prova Pratix

Essa prova é simples, não tem segredo. A API fará uma consulta, em uma URL, e deverá retornar **A MESMA ESTRUTURA** só que com algumas modificações.

**Você deverá usar Laravel, e garantir que esteja usando um código limpo e fluido.**

#### Tarefas

- Construa uma API Laravel, onde você fará uma consulta nessa URL: https://api.pratix.top/api/geo/get/simple/radio/40/-3.7553375/-38.6296543
- Deverá retornar o mesmo objeto jSON só que; O objeto *payments->name* deverá retornar a palavra Profissional antes da string, isto é, se atualmente o valor do objeto *payments->name* for João, então no retorno da API deverá retornar *Profissional João*. Entendeu? Só adicionar o 'Profissional' na frente.
- Deverá retornar, dentro do objeto *atuação* um novo valor chamado **total_de_servicos: X***; Isto é, se no objeto atuacao->servicos possuir 1 serviço, então ele deverá informar a quantidade de serviço que aquele profissional presta. Se o objeto possuir 3 valores, deverá retornar 3. Se possuir 1 valor, retornar 1. Vamos basicamente contar, quantos serviços aquele profissional oferece!


Isso é tudo!


Boa sorte!
