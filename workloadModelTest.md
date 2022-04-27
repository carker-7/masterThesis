
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
When testing this workload model the scenario and sensors were running. The workload was minimal and consisted of one air target and one sea target.


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


## Workload model ID 2
When testing this workload model the scenario and sensors were running. The workload consisted of 100 air targets and 100 sea targets.


### Server C2A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|IA5	|	X|	101,322	|130|	0,571	|0,571    |
|Process6B	|	X|	10,643|	183,3|	0,766917|	0,953    |
|Process12	|	X	|9,94883|	306,7|	0,842096|	0,855    |
|Mux1|		X|	7,16895	|45,16|	0,606	|0,606    |
|IA4	|	X|	6,09688|	153,3|	0,592322|	0,608    |
|Process6D	|	X|	4,88249	|141,9	|0,666758|	0,672    |
|IA2	|	X|	4,32697|	46,67|	0,549216|	0,55    |
|Process6A	|	X	|3,34197	|254,8|	0,722621	|0,724    |
|IA1	|	X	|2,0156	|66,67|	0,613883|	0,615    |
|Process13	|	X	|2,01297	|183,3|	0,303281|	0,304    |


### Server C2B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process16A	|	X|	2,45236	|87,1|	0,608597|	0,61    |
|Process18	|	X|	2,34006|	67,74|	0,397374|	0,404    |
|Process19C	 |	X|	1,15367|	9,677|	0,190844|	0,202    |
|Mux2B	|	X	|0,904278|	6,667	|0,333044|	0,334    |
|Process19A	|	X|	0,604057|	6,667|	0,087|	0,087    |
|Process17	|	X|	0,301335|	6,667	|0,095|	0,095    |
|Process19B	|	|	0|	0|	0,001|	0,001    |
|Process19D	|	|	0|	0|	0,001|	0,001    |


### Server SSA processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Mux4B|		X|	1,40811	|13,33	|2,632|	2,632    |
|Process32	|	X|	1,111|	40|	3,25423	|3,557    |
|Process31C	|	X|	1,07077	|83,33|	2,93103|	2,962    |
|Process33C	|	|	1,02384	|22,58|	1,965|	1,965    |
|DB7	|	X|	0,413044|	6,667|	5,74359|	5,757    |
|Process31B	|	X|	0,3086|	3,333|	1,736|	1,736    |
|DB10|		X|	0,196613|	3,333|	1,191|	1,191    |
|Process31A	|	X|	0,16393	|3,333|	1,355|	1,355    |
|DB8	|	X|	0,137958|	3,333|	2,727|	2,727    |
|DB9	|	X|	0,120922|	3,333	|1,255|	1,255    |


### Server SSB processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process42A	|	|	37,8856	|80	|1,091|	1,091    |
|Process43	|	|	2,11161	|6,667|	0,122|	0,122    |
|Process44|		X|	1,38015	|6,667	|3,52164|	3,525    |
|Mux5B	|	X|	0,87021|	6,667|	2,51706	|2,528    |
|Process41|		|	0,62753	|6,667|	0,043|	0,043    |
|Process39B	 |	X|	0,224255|	6,667	|2,87|	2,87    |
|Process38	|	|	0,00865714	|3,333|	0,031|	0,031    |
|Process39A	 |	|	0|	0	|0,024|	0,024    |
|Mux5A	|	|	0|	0	|0,024|	0,024    |


### Node A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|C2MMI	|	X	|65,3078	|306,7|	11,7658|	12,19     |
|Process24	|	|	9,11698	|13,33	|0,76|	0,76     |
|Process25	|	|	5,85298	|10|	0|	0     |
|Process26	|	|	3,91134	|10	|0,488	|0,488     |
|Mux3	|	X|	1,89934	|16,67|	1,76899|	1,776     |
|Process23|		|	0	|0	|0,015|	0,015     |


### Node B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|SSMMI	|	X|	32,218	|66,67	|9,9203	|9,929     |
|Process47	|	|	9,57822|	13,33|	0,756|	0,756     |
|Process48|	|	7,08449	|10	|0	|0     |
|Process49	|	|	3,45276	|10	|0,549	|0,549     |
|Mux6A|		X	|1,45724|	6,667|	1,772|	1,772     |
|Process45	|		|0,0173143|	3,333	|0,014|	0,014     |
|Process46|		|	0,00865714	|3,333|	0,015	|0,015     |
|Mux6B	|	|	0|	0|	0,011	|0,011     |


## Workload model ID 3
When testing this workload model the scenario and sensors were running. The workload consisted of 200 air targets and 200 sea targets.


### Server C2A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|IA5	|	X|	101,012	|126,7|	0,571|	0,571    |
|Process12	|	X|	9,09048|	93,33|	0,853732|	0,854    |
|IA4	|	X|	8,87427	|156,7	|0,613099|	0,617    |
|Mux1	|	X|	8,6171	|58,06	|0,606|	0,606    |
|IA2	|	X|	5,64834	|70,97|	0,551223|	0,552    |
|Process6D	|	X	|4,49786	|103,2	|0,669244|	0,671    |
|Process6B	|	X|	3,78676|	110	|0,970177|	0,971    |
|Link1	|	X	|2,6222|	150	|0,536418|	0,558    |
|Process6A|		X|	2,61655	|30	|0,725862|	0,726    |
|IA1	|	X|	1,86837|	13,33|	0,614439|	0,615    |


### Server C2B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process18	|	X|	2,72409	|13,33|	0,490694|	0,612    |
|Process16A	 |	X	|1,75832|	6,667|	0,611|	0,611    |
|Process19C|	 	X|	1,18242	|6,667|	0,243881|	0,26    |
|Mux2B	|	X|	0,837525|	6,667	|0,349016|	0,375    |
|Process17|	X|	0,674179|	110	|0,102468|	0,112    |
|Process19A	|	X	|0,490956|	3,333|	0,087|	0,087    |
|Process19B	|	|	0|	0|	0,001|	0,001    |
|Process19D	|	|	0|	0|	0,001|	0,001    |


### Server SSA processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process31C	|	X|	2,51402|	133,3|	3,54294	|3,757    |
|Mux4B	|	X|	1,3598	|6,667|	2,632|	2,632    |
|Process32|		X|	1,1244|	16,67|	3,40277|	3,405    |
|Process33C	|		|1,03835	|19,35|	1,976|	1,976    |
|DB7	|	X|	0,344618|	3,333|	5,758|	5,758    |
|Process31B	|	X|	0,334849|	3,333|	1,736|	1,736    |
|Process31A	|	X	|0,171753|	3,333|	1,355|	1,355    |
|DB10	 |	X|	0,145782	|3,333	|1,191|	1,191    |
|DB8	|	X|	0,137681|	3,333	|2,727|	2,727    |
|DB9|	X|	0,0860156|	3,333	|1,255|	1,255    |


### Server SSB processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process42A	|	|	49,4985|	113,3|	1,091|	1,091    |
|Process43	|	|	2,35706|	10|	0,125|	0,125    |
|Process44|		X|	1,32932	|13,33|	3,57009|	3,579    |
|Mux5B	|	X|	0,742301|	6,667|	2,535|	2,535    |
|Process41|		|	0,44934|	6,667|	0,043|	0,043    |
|Process39B	 |	X	|0,198842|	10	|2,872|	2,872    |
|Process39A	|	|	0|	0	|0,024|	0,024    |
|Mux5A	|	|	0|	0	|0,024|	0,024    |
|Process38|		|	0|	0|	0,031|	0,031    |


### Node A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|C2MMI	|	X	|66,1805|	120	|11,93|	11,93     |
|Process24	|	|	8,94057|	13,33|	0,762|	0,762     |
|Process25|		|	5,76165	|6,667|	0|	0     |
|Process26	|	|	3,78453|	10	|0,488|	0,488     |
|Mux3|		X|	1,93339	|10|	1,776|	1,776     |
|Process23	|	|	0|	0	|0,015|	0,015     |


### Node B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|SSMMI	|	X|	42,8966	|133,3|	10,1475	|10,17     |
|Process47	||		9,30182	|13,33|	0,756	|0,756     |
|Process48	||		7,00825|	10|	0|	0     |
|Process49	||		3,61225|	10|	0,549|	0,549     |
|Mux6A	|	X|	1,57118	|6,667|	1,772|	1,772     |
|Mux6B		||	0|	0	|0,011	|0,011     |
|Process45	||		0|	0|	0,014|	0,014     |
|Process46		||	0|	0|	0,015|	0,015     |


## Workload model ID 4
When testing this workload model the scenario and sensors were running. The workload consisted of 300 air targets and 300 sea targets.


### Server C2A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|IA5	|	X|	101,132	|123,3|	0,574|	0,574    |
|Process12	|	X	|13,6382	|106,7|	0,859029|	0,862    |
|IA4	|	X|	10,7622|	120	|0,616065|	0,617    |
|Mux1	|	X|	9,88852	|56,67|	0,606|	0,606    |
|IA2	|	X|	7,32563	|73,33|	0,551694|	0,552    |
|Process6D	|	X|	5,65562|	120	|0,669229|	0,672    |
|Process6B	|	X|	5,15495	|96,77|	0,97286	|0,973    |
|Link1	|	X	|3,35645	|136,7|	0,559|	0,559    |
|Process6A	|	X	|2,71711|	10	|0,729278|	0,73    |
|IA1	|	X|	2,41124|	103,3|	0,61534|	0,62    |


### Server C2B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process18	|	X|	3,3497|	16,67|	0,635195|	0,637    |
|Process16A	|	X	|2,3426	|13,33|	0,611|	0,611    |
|Process19C	|	X|	1,50668	|6,667|0,313143	|0,334    |
|Mux2B	|	X	|0,749561|	6,667|	0,41|	0,41    |
|Process19A	|	X|	0,595397|	3,333|	0,087|	0,087    |
|Process17	|	X	|0,301888|	3,333	|0,117938|	0,134    |
|Process19B	|	|	0|	0|	0,001|	0,001    |
|Process19D	|	|	0|	0|	0,001|	0,001    |



### Server SSA processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process31C	|	X|	2,79479|	153,3|	4,35871	|4,572    |
|Process32	|	X|	1,51428	|19,35|	3,272|	3,272    |
|Mux4B	|	X|	1,46312|	6,667|	2,632|	2,632    |
|Process33C	|		|1,02437	|23,33|	1,961|	1,961    |
|Process31B	|	X|	0,378138|	6,667|	1,736|	1,736    |
|DB7	|	X|	0,335127|	3,333|	5,76|	5,76    |
|DB10|	 X|	0,198003|	3,333|	1,191|	1,191    |
|DB8	|	X|	0,172309|	3,333|	2,727|	2,727    |
|DB9	|	X	|0,138514|	3,333|	1,255|	1,255    |
|Process31A	|	X|	0,111987	|3,333|	1,355|	1,355    |


### Server SSB processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|Process42A	|	|	60,7825	|113,3	|1,091|	1,091    |
|Process43	|		|2,71011	|6,667|	0,132|	0,132    |
|Process44|		X|	0,888356|	10	|3,59878|	3,601    |
|Mux5B	|	X|	0,708782|	6,667|	2,539|	2,539    |
|Process41	|	|	0,361932|	3,333	|0,043|	0,043    |
|Process39B	|	X	|0,172865|	3,333|	2,872|	2,872    |
|Process38	|	|	0,00865714|	3,333|	0,031|	0,031    |
|Process39A	|	|	0|	0|	0,024|	0,024    |
|Mux5A	|	|	0|	0|	0,024|	0,024    |


### Node A processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|C2MMI	|	X|	72,3349|	123,3|	11,9985|	12,02     |
|Process24|		|	8,88888	|13,33|	0,762|	0,762     |
|Process25	|	|	5,64768|	6,667|	0|	0     |
|Process26	|	|	3,70523	|10	|0,488	|0,488     |
|Mux3	|	X|	2,06437	|6,667	|1,776|	1,776     |
|Process23	|	|	0|	0|	0,015|	0,015     |


### Node B processes

|  Process  | Java |  Average %CPU | Max %CPU | Average %MEM | Max %MEM | 
|-----------|:----:|:-------------:|:--------:|:------------:|:--------:|
|SSMMI	|	X|	52,7401	|83,33|	10,38|	10,38    |
|Process47	|	|	9,3177|	13,33	|0,756	|0,756    |
|Process48	|	|	6,94235|	10|	0|	0    |
|Process49	|	|	3,52565|	10|	0,551|	0,551    |
|Mux6A	|	X|	1,39914	|6,667|	1,77227|	1,774    |
|Process46	|		|0,0173143|	3,333|	0,015|	0,015    |
|Process45	|	|	0,00865714	|3,333|	0,014|	0,014    |
|Mux6B	|	|	0|	0|	0,011|	0,011    |
