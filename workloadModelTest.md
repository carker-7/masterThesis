
# Workload model testing

Here the result of the workload model testing is presented. The data values were collected once every second for the duration of 6 minutes. Thus the average values are of 360 values. The top 10 processes when it comes to the average CPU value are included in each table. All tables are also ordered by the largest average CPU value.


## Workload model ID 0
The first workload model contains zero air targets and zero sea targets, and it was tested without any scenario or sensors running. It is only a measurement of the system being booted up.


### Server C2A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|IA5	|	X|	101,356	|146,7|	0,571|	0,571    |
|Mux1	|	X|	5,23778|	23,33|	0,601117|	0,602    |
|IA2	|	X	|2,38817	|26,67|	0,53679	|0,537    |
|Process6D	|	X|	2,22724	|90,32|	0,634675|	0,638    |
|Process12	|	X|	1,73374|	23,33|	0,770478|	0,771    |
|Process6A|		X|	1,66951|	13,33|	0,667|	0,667    |
|Process7B	|	X|	1,636|	13,33|	0,472|	0,472    |
|IA1	|	X|	1,42851	|16,13|	0,513234|	0,562    |
|Process6B	|	X|	1,2235|	10	|0,48679|	0,488    |
|IA6	|	X|	0,751797|	10|	0,396	|0,396    |


### Server C2B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process19C	|	X|	1,34359	|16,67|	0,13713	|0,141    |
|Process18|		X|	1,27407	|16,67|	0,298551	|0,299    |
|Process16A	 |	X|	1,23188	|20	|0,567117|	0,592    |
|Mux2B	|	X|	0,741457|	3,333|	0,29621|	0,324    |
|Process17	|	X|	0,457447|	6,667|	0,087|	0,087    |
|Process19A	 |	X|	0,448229|	6,667|	0,088|	0,088    |
|Process19B	| 	|	0|	0|	0,001|	0,001    |
|Process19D	 |	|	0|	0|	0,001|	0,001    |


### Server SSA processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Mux4B	 |	X|	0,991421|	6,667|	2,625|	2,625     |
|Process33C	|	|	0,749278|	22,58|	1,744|	1,744     |
|DB7	|	X|	0,370034|	6,452|	5,73314|	5,734     |
|Process31B	|	X|	0,292122|	6,667|	1,79186|	1,792     |
|Process31C	|	X|	0,223974|	3,333|	1,291|	1,291     |
|Process31A	|	X|	0,189623|	3,333|	1,324|	1,324     |
|Process32	|	X|	0,189068	|3,333|	1,913|	1,913     |
|DB10	 |	X|	0,180966|	3,333	|1,191|	1,191     |
|DB8	|	X|	0,137681|	3,333	|2,723|	2,723     |
|DB9	|	X	|0,10333	|3,333	|1,177|	1,177     |


### Server SSB processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process42A	|	|	23,3215|	30|	1,087|	1,087     |
|Process44|		X|	0,585912|	6,667	|2,801	|2,801     |
|Mux5B	|	X|	0,455774|	6,667|	2,362	|2,362     |
|Process39B	|	X|	0,24994|	13,33	|2,79608	|2,802     |
|Process38	||		0,0173143|	3,333	|0,031	|0,031     |
|Process41	|	|	0,00865714|	3,333|	0,038|	0,038     |
|Process43	|	|	0,00837922	|3,226|	0,04|	0,04     |
|Process39A|	 |	0|	0|	0,024|	0,024     |
|Mux5A	|	|	0|	0	|0,024|	0,024     |


### Node A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|C2MMI	|	X|	24,8158|	136,7|	10,3165	|10,33     |
|Process24	|	|	9,65496|	20|	0,756003|	0,757     |
|Process25|	|		7,22747	|10	|0	|0     |
|Process26|	|	4,65683	|23,33	|0,479|	0,479     |
|Mux3	|	X|	2,106|	10|	1,704|	1,704     |
|Process23	|	|	0|	0	|0,015	|0,015     |

### Node B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|SSMMI	| 	X| 	17,1564	| 36,67	| 9,05492| 	9,068     |
|Process48	| 		| 7,29896| 	10| 	0| 	0     |
|Process47| 	| 	6,99725	| 10| 	0,758| 	0,758     |
|Process49	| 	| 	3,09217	| 6,667| 	0,549| 	0,549     |
|Mux6A	|  	X| 	0,967668| 	6,667| 	1,771| 	1,771     |
|Process45	| 	| 	0,00865714	| 3,333	| 0,014| 	0,014     |
|Process46	| 	| 	0,00865714| 	3,333| 	0,015| 	0,015     |
|Mux6B	| 	| 	0| 	0	| 0,011| 	0,011     |


## Workload model ID 1
When testing this workload model the scenario and sensors were running.
The workload was minimal and consisted of one air target and one sea target.


### Server C2A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|IA5	|	X|	101,151	|123,3	|0,571|	0,571    |
|Mux1	|	X|	5,58384	|13,33|	0,603|	0,603    |
|Process12|		X|	2,9015|	80|	0,781919|	0,785    |
|Process6D|		X|	2,60152|	66,67|	0,636914|	0,641    |
|IA2	|	X	|2,5412|	33,33	|0,549|	0,549    |
|Process6A	|	X|	2,28282|	90	|0,701678|	0,704    |
|IA1	|	X|	2,0181|	26,67|	0,598205|	0,605    |
|Process6B	|	X	|1,62707	|63,33|	0,541319|	0,545    |
|Process7B	|	X	|1,61901|	46,67|	0,530855|	0,542    |
|Process10A	|	X	|1,4166	|156,7|	0,562688|	0,571    |


### Server C2B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process16A	|	X|	1,47765	|56,67|	0,593899|	0,596    |
|Process18	|	X|	1,29136|	30	|0,340974|	0,345    |
|Process19C	| 	X	|1,12882	|23,33	|0,153753|	0,162    |
|Mux2B	|	X|	0,766605|	10|	0,333|	0,333    |
|Process19A	|	X|	0,569156|	6,667|	0,089|	0,089    |
|Process17	|	X|	0,396286|	6,667|	0,095|	0,095    |
|Process19B	|	|	0|	0|	0,001|	0,001    |
|Process19D	|	|	0|	0	|0,001|	0,001    |


### Server SSA processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Mux4B|	X|	1,70358	|43,33|	2,63182	|2,632     |
|Process33C	|	|	1,06295	|41,94	|1,91132	|2,013     |
|Process31C	|	X|	0,740922|	73,33|	2,25381	|2,362     |
|Process32|		X|	0,557717|	16,67|	2,49938	|2,852     |
|DB7	|	X|	0,421979|	6,667|	5,737|	5,737     |
|Process31B	|	X|	0,318091	|3,333	|1,736|	1,736     |
|Process31A	|	X|	0,206938|	3,333|	1,329|	1,329     |
|DB8	|	X	|0,172031|	3,333|	2,72301|	2,726     |
|DB10|	 	X|	0,146338|	3,333|	1,191|	1,191     |
|DB9	|	X	|0,0862935|	3,333|	1,177|	1,177     |


### Server SSB processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
| Process | Java | Avg CPU | Max CPU  | Avg MEM | Max MEM    |
|Process42A	|	|	25,2842	|36,67	|1,091	|1,091     |
|Process43	|	|	5,04153	|10|	0,114|	0,114     |
|Mux5B	|	X|	1,57316	|83,33|	2,4921|	2,737     |
|Process44	|	X|	1,35367|	50	|3,39294	|3,394     |
|Process41	|	|	0,604361|	6,667	|0,038	|0,038     |
|Process39B	|	X|	0,249956|	6,667	|2,85758	|2,858     |
|Process38	|	|	0,0173143|	3,333|	0,031|	0,031     |
|Process39A	|	|	0|	0	|0,024|	0,024     |
|Mux5A	|	|	0|	0|	0,024|	0,024     |


### Node A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|C2MMI	|	X|	60,9988	|396,7|	10,7915|	11,21     |
|Process24	|		|9,02204|	13,33|	0,76|	0,76     |
|Process25|	|		6,70911|	10	|0	|0     |
|Process26|		|	4,20408	|10	|0,488216|	0,571     |
|Mux3	|	X|	2,33921|	6,667|	1,751|	1,751     |
|Process23	|	|	0,00865714	|3,333|	0,015	|0,015     |


### Node B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|SSMMI	|	X|	26,9708	|154,8|	9,46174	|9,761     |
|Process47	|	|	7,11426|	13,33	|0,756|	0,756     |
|Process48	|	|	7,09008	|10	|0	|0     |
|Process49	|	|	3,52231|	10|	0,549|	0,549     |
|Mux6A	|	X|	1,51197	|16,67|	1,771|	1,771     |
|Process46|		|	0,00865714	|3,333|	0,015|	0,015     |
|Mux6B	||	0|	0|	0,011|	0,011     |
|Process45	|	|	0|	0|	0,014|	0,014     |
