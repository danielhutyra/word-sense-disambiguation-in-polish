# Word sense disambiguation in polish language
My Master thesis. My proposal for solving the problem of disambiguating the meaning of words in Polish with the use of neural networks based on the architecture of transformers. The data used in this project comes from Poleval 2020.

# Results

|Algorithm|Combination|Always MWE|Recall KPWr|Precision KPWr|Recall Sherlock|Precision Sherlock|
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
|HERBERT|Maximum score |No|0,538|0,544|0,528|0,535|
|HERBERT|Maximum score |Yes|0,544|0,549|0,526|0,534|
|HERBERT|Maximum score for current sentence|No|0,571|0,576|0,553|0,561|
|HERBERT|Maximum score for current sentence|Yes|0,576|0,582|0,552|0,561|
|HERBERT|Maximum score from average score |No|0,535|0,540|0,520|0,527|
|HERBERT|Maximum score from average score |Yes|0,538|0,543|0,519|0,526|
|HERBERT|Average score for current sentence|No|0,575|0,580|0,564|0,572|
|HERBERT|Average score for current sentence|Yes|0,577|0,583|0,562|0,570|
|HERBERT|Weighted maximum score |No|0,564|0,569|0,552|0,560|
|HERBERT|Weighted maximum score |Yes|0,570|0,575|0,551|0,559|
|POLBERT|Maximum score |No|0,526|0,531|0,523|0,531|
|POLBERT|Maximum score |Yes|0,532|0,537|0,523|0,531|
|POLBERT|Maximum score for current sentence|No|0,541|0,546|0,545|0,553|
|POLBERT|Maximum score for current sentence|Yes|0,548|0,553|0,545|0,553|
|POLBERT|Maximum score from average score |No|0,521|0,527|0,509|0,517|
|POLBERT|Maximum score from average score |Yes|0,527|0,532|0,510|0,517|
|POLBERT|Average score for current sentence|No|0,539|0,545|0,545|0,553|
|POLBERT|Average score for current sentence|Yes|0,544|0,550|0,543|0,551|
|POLBERT|Weighted maximum score |No|0,539|0,545|0,533|0,540|
|POLBERT|Weighted maximum score |Yes|0,546|0,551|0,531|0,539|
|POLBERT|Poleval application|-|0,589|0,599|0,577|0,592|
|Wosedon|Personalized PageRank|-|0,494|0,532|0,532|0,562|
|Wosedon|Personalized PageRank W2W|-|0,618|0,625|0,594|0,607|
|Lesk|-|-|0,463|0,471|0,454|0,466|

