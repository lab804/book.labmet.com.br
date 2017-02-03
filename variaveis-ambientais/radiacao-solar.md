| Tipo | Radiação Solar |
| :--- | :--- |
| Sensor | [RTC](/rtc.md) - [BHT1750](/bh1750.md) |
| Descrição | Responsável por mensurar a radição solar |
| Função | O dado coletado de data, hora e  deve ser enviado como parâmentro para API por meio da estação meteorológica. A API o confrotará com valores de máximo e mínimo pré definidos para a cultura em questão. A partir deste, alertará o usuário sobre quais áreas estão ou não háptas para realizar [operações agricolas](/operacoes-mecanizadas.md). |
| Parâmetros | Data e Hora - Latitude  |
| Retorno | Indica nível de rediação, hora do nascer do sol, fotoperíodo e ângulo solar |
| Observações | 1\) Armazenar dados coletados no banco de dados              2\) A radição solar é obtida via calculos ciênticos a partir dos dados retornados pelo RTC e BH1750. |



