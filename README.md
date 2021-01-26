# Data_Portfolio

Here is my [LinkedIn][f1] <br />
Here is my [twitter][f2]   <br />
![Video Presentation](https://www.youtube.com/watch?v=-vsqB16p-Jo) of a project that I made for Govt. of Arunachal Pradesh. <br />
This is my [CV](https://drive.google.com/file/d/17Q0Icn2PGEAazRZTe9L0rWzIRwTcvM0f/view?usp=sharing) <br />


Here is the code for a 'dashboard' I built in R which displays the HDI Trajectory of the 'input' nation
`HDI <- read.csv(file.choose())
##Creating a function to analyise and visualise the HDI pertaining to a country.
country.plot <- function(){  
  a <- readline(prompt = "Which Country?")  #Asking for the Input country
  country.hdi<-HDI$Historical.Index.of.Human.Development..Prados.de.la.Escosura.[HDI$Entity == a] #Extracting country data
  year.hdi <- HDI$Year[HDI$Entity == a]  #Extracting pertaining years
  final.hdi<-cbind(year.hdi, country.hdi) #Merging the 2 aforementioned columns
  plot(final.hdi, xlab = "year", ylab = "HDI", main = a, type = "b") #Plotting the final table
  print(this is the mean HDI of a)
  print(mean(HDI$Historical.Index.of.Human.Development..Prados.de.la.Escosura.[HDI$Entity == a]))
}

country.plot()  #Calling the function`




















[f1]: https://www.linkedin.com/in/akshar-katariya-15a63b17a/
[f2]: https://twitter.com/AksharKatariya
