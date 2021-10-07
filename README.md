# INFO-550

## My project

This project aims to look into the long term impact of COVID-19 on China's regional air quality through health and economic perspectives. The data in this directory has already been pre-processed (missing data cleaning, grouping by variables) The Rmd document here deals with summarize pre-liminary results and plotting figures for eventual visualiztion purposes. 

To analyze the data you will need to install some R packages. The required packages can be installed using R commands.


'installed_pkgs <- row.names(installed.packages())
pkgs <- c("dplyr", "ggplot2")
for(p in pkgs){
	if(!(p %in% install_pkgs)){
		install.packages(p)
	}
}'

## Execute the analysis
To execute the analysis, from the project folder you can run

`Rscript -e "rmarkdown::render('HW2_HC.Rmd')"`

This will create a file called report.html output in your directory that contains the results.
