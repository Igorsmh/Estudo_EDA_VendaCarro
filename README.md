# Projeto de Análise de Preços de Carros Usados


Olá a todos!

Realizei este projeto-estudo com a intenção de melhorar minhas habilidades em EDA, parte muito importante para compreender bem os dados que temos e assim gerar um modelo mais preciso futuramente. 

Primeiro, tive que lidar com alguns desafios. Encontrei dados faltantes que precisavam ser preenchidos de maneira inteligente, garantindo que nossa análise não fosse prejudicada. Além disso, dei uma olhada nos valores extremos (outliers) e fiz algumas limitações para manter nossas análises mais sólidas.

Aqui esta uma descrição do conjunto de dados usado
O conjunto de dados em questão contém informações relacionadas a veículos anunciados para venda. Cada registro ou linha no conjunto de dados possui os seguintes campos:

- `price`: O preço do veículo anunciado para venda.

- `model_year`: O ano do modelo do veículo.

- `model`: O modelo específico do veículo.

- `condition`: A condição do veículo, que pode ser uma descrição como "novo", "usado", "excelente", "bom" etc.

- `cylinders`: O número de cilindros do motor do veículo.

- `fuel`: O tipo de combustível que o veículo utiliza, como gasolina, diesel, etc.

- `odometer`: A quilometragem registrada no veículo quando o anúncio foi publicado.

- `transmission`: O tipo de transmissão do veículo, como automática ou manual.

- `paint_color`: A cor da pintura do veículo.

- `is_4wd`: Um campo booleano que indica se o veículo é 4 por 4 (tração nas quatro rodas).

- `date_posted`: A data em que o anúncio do veículo foi publicado.

- `days_listed`: O número de dias que o anúncio permaneceu ativo antes de ser retirado.

Aqui estão algumas coisas que descobri ao longo dessa jornada:

Idade vs. Preço: Não é nenhuma surpresa que carros mais novos tendem a custar mais. Mas o que realmente chamou a atenção foi como o preço cai drasticamente após 10 anos de uso. Isso nos dá uma visão clara da depreciação dos carros ao longo do tempo.

Quilometragem Importa: A quilometragem percorrida por um carro é um fator crucial no preço. As pessoas estão dispostas a comprar carros com até 200.000 quilômetros rodados, contanto que o preço não ultrapasse $10.000. Parece que, para muitos compradores, o número de quilômetros é mais importante do que a aparência geral do veículo.

Modelo vs. Preço: Não posso deixar de mencionar que o modelo do carro tem um grande impacto no preço. Carros de marcas, modelos ou com recursos específicos podem valer mais no mercado de usados.

Relação Idade e Quilometragem: Aqui está uma surpresa: carros mais antigos tendem a ter mais quilômetros rodados. Claro, faz sentido, afinal, quanto mais antigo o carro, mais tempo ele teve para acumular quilômetros na estrada.

Em resumo, este projeto proporcionou uma análise profunda do mercado de carros usados, revelando insights valiosos que podem ser úteis para compradores e vendedores. É incrível como os dados podem nos contar histórias fascinantes sobre a vida dos carros no mercado de usados. Espero que as conclusões deste projeto ajudem todos a tomarem decisões mais informadas na compra e venda de veículos usados.
