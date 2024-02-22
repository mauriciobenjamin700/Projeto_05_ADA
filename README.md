# Projeto 05 ADA

Neste projeto, realizamos uma análise descritiva completa da base de dados disponível em [Kaggle](https://www.kaggle.com/datasets/giovamata/airlinedelaycauses), explorando tanto variáveis discretas quanto contínuas.

## Dados do Dataset

Este conjunto de dados é composto pelas seguintes variáveis:

- **Year**: Ano (2008)
- **Month**: Mês (1-12)
- **DayofMonth**: Dia do mês (1-31)
- **DayOfWeek**: Dia da semana (1 - segunda-feira, 7 - domingo)
- **DepTime**: Horário de partida real (local, hhmm)
- **CRSDepTime**: Horário de partida programado (local, hhmm)
- **ArrTime**: Horário de chegada real (local, hhmm)
- **CRSArrTime**: Horário de chegada programado (local, hhmm)
- **UniqueCarrier**: Código de transportadora único
- **FlightNum**: Número do voo
- **TailNum**: Número de cauda do avião: registro da aeronave, identificador único da aeronave
- **ActualElapsedTime**: Tempo decorrido real em minutos
- **CRSElapsedTime**: Tempo decorrido programado em minutos
- **AirTime**: Tempo de voo em minutos
- **ArrDelay**: Atraso na chegada, em minutos: Um voo é considerado "no horário" se operou menos de 15 minutos após o horário programado mostrado nos sistemas de reservas computadorizados (CRS) das transportadoras.
- **DepDelay**: Atraso na partida, em minutos
- **Origin**: Código IATA de origem do aeroporto
- **Dest**: Código IATA de destino do aeroporto
- **Distance**: Distância em milhas
- **TaxiIn**: Tempo de táxi na chegada, em minutos
- **TaxiOut**: Tempo de táxi na partida em minutos
- **Cancelled**: Foi o voo cancelado
- **CancellationCode**: Motivo do cancelamento (A = transportadora, B = clima, C = NAS, D = segurança)
- **Diverted**: 1 = sim, 0 = não
- **CarrierDelay**: Atraso da transportadora em minutos: O atraso da transportadora está dentro do controle da transportadora aérea. Exemplos de ocorrências que podem determinar atraso da transportadora são: limpeza da aeronave, danos à aeronave, aguardando a chegada de passageiros ou tripulação conectados, bagagem, colisão com pássaros, carregamento de carga, catering, computador, interrupção do equipamento da transportadora, legalidade da tripulação (descanso do piloto ou comissário de bordo), danos por mercadorias perigosas, inspeção de engenharia, abastecimento, manuseio de passageiros desativados, tripulação atrasada, atendimento sanitário, manutenção, excesso de reservas, atendimento de água potável, remoção de passageiro indisciplinado, embarque ou assentamento lento, estiva de bagagem de mão, atrasos de peso e equilíbrio.
- **WeatherDelay**: Atraso devido ao clima em minutos: O atraso meteorológico é causado por condições climáticas extremas ou perigosas que são previstas ou se manifestam no ponto de partida, durante o trajeto ou no ponto de chegada.
- **NASDelay**: Atraso do Sistema Nacional de Espaço Aéreo (NAS) em minutos: Atraso que está dentro do controle do Sistema Nacional de Espaço Aéreo (NAS) pode incluir: condições climáticas não extremas, operações aeroportuárias, volume intenso de tráfego, controle de tráfego aéreo, etc.
- **SecurityDelay**: Atraso de segurança em minutos: O atraso de segurança é causado pela evacuação de um terminal ou saguão, reembarque de aeronaves devido a violação de segurança, equipamentos de triagem inoperantes e/ou longas filas com mais de 29 minutos nas áreas de triagem.
- **LateAircraftDelay**: Atraso devido a aeronave atrasada em minutos: Atraso na chegada a um aeroporto devido à chegada tardia da mesma aeronave em um aeroporto anterior. O efeito cascata de um atraso anterior em aeroportos a jusante é referido como propagação do atraso.