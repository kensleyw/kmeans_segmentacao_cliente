# kmeans_segmentacao_cliente
## Problema de negócio
Medições do consumo de energia elétrica em uma residência com taxa de amostragem de um minuto durante um período de quase 4 anos. Diferentes grandezas elétricas e alguns valores de submedição estão disponíveis.

### Arquitetura dos dados
* **1.date:** Data no formato dd/mm/aaaa
* **2.time:** hora no formato hh:mm:ss
* **3.global_active_power:** potência ativa média global doméstica por minuto (em quilowatts)
* **4.global_reactive_power:** potência reativa média global doméstica por minuto (em quilowatts)
* **5.voltage:** tensão média por minuto (em volts)
* **6.global_intensity:** intensidade de corrente média global por minuto doméstica (em amperes)
* **7.sub_metering_1:** submedição de energia nº 1 (em watt-hora de energia ativa). Corresponde à **cozinha**, contendo majoritariamente **uma máquina de lavar louça, um forno e um micro-ondas** (as placas não são elétricas mas sim a gás).
* **8.sub_metering_2:** submedição de energia nº 2 (em watt-hora de energia ativa). Corresponde à **lavandaria**, contendo **máquina de lavar roupa, máquina de secar roupa, frigorífico e luz**.
* **9.sub_metering_3:** submedição de energia nº 3 (em watt-hora de energia ativa). Corresponde a um **aquecedor elétrico e a um ar condicionado**.
