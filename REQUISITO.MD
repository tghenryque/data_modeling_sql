# 📋 Levantamento de Requisitos

## Cenário apresentado pelo Sr. José

Sr. José quer modernizar sua oficina, e por enquanto, cadastrar os carros que entram para realizar serviços e os seus respectivos donos.  
Sr. José mencionou que cada cliente possui apenas um carro.  
Um carro possui uma marca.  
Sr. José também quer saber as cores dos carros para ter ideia de qual tinta comprar, e informar que um carro pode ter mais de uma cor.  
Sr. José necessita armazenar os telefones dos clientes, mas não quer que eles sejam obrigatórios.

## Análise dos requisitos

A partir do cenário apresentado, podemos identificar os seguintes requisitos técnicos:

- Cada **cliente** terá um registro único no sistema, vinculado a **um único carro**.  
- Cada **carro** terá informações sobre **modelo, placa e marca**.  
- As **cores dos carros** precisam ser armazenadas de forma que um mesmo carro possa ter **mais de uma cor**.  
- Os **telefones dos clientes** são opcionais, podendo não ser informados.  
- A estrutura do banco deve permitir consultas e relatórios consolidados sobre **clientes, carros, cores e serviços realizados**.
