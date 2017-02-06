| Tipo | Radiação Solar |
| :--- | :--- |
| Sensor | [RTC](/rtc.md) - [BHT1750](/bh1750.md) |
| Descrição | Responsável por mensurar a radição solar |
| Funcionalidades | Os dados coletados de data, hora e iluminância devem ser enviados como parâmetros para API por meio da estação meteorológica. A API irá confrontar com valores de máximo e mínimo pré definidos para a cultura em questão. A partir deste, alertará o usuário sobre quais áreas estão ou não aptas para realizar [operações agrícolas](/operacoes-agrícolas.md). |
| Parâmetros | Data e Hora - Latitude |
| Retorno | Indica nível de rediação, hora do nascer do sol, fotoperíodo e ângulo solar |
| Observações | 1\) Armazenar dados coletados no banco de dados              2\) A radição solar é obtida via calculos ciênticos a partir dos dados retornados pelo RTC e BH1750. |



