# TradeReportGenerator
This repo contains a Core Java Project named "TradeReportGenerator" meant to generate data reports from incoming daily trade buy/sell instructions.

The project is zipped attached in this repo.

The main starting point of application is Runner.java.
Please use JDK 8 to execute this project as there are some Java 8 constructs used.

In order to execute the main class, from your favourite IDE either one can pass one program argument 
viz. "inputFiles//tradeData_BUY_AND_SELL_200.csv" else the default file will be used to execute "inputFiles//tradeData_BUY_AND_SELL_200000.csv".

There are some sample input CSV files in the "inputFiles" folder.
The CSV input files were created using an additional utility class "CsvTradeDataWriter.java".One can tweak and use this 
class if want to create more sample data.

There are also some sample output data report files in folder "sampleOutputFiles" which contain the printed report data report for reference with different set of trade detail instructions.
The sample output files was used for my testing needs and can be treated as a reference to understand the format in which the data report is printed on console.
