<h1 align="center">
	<br>
	MEAN-MEDIAN-MODE
	<br>
</h1>
   
  
`ketika melihat suatu grup data, pengetahuan dasar yang bisa kita peroleh, "bagaimana mean, median dan modus-nya"`  
## Data  
  
```bash  
suhu = [36,37,36,36.5,37,37.5,38,39,36,37,36,40,37]
```  
## Script  
## Mean
```bash  
import numpy

suhu = [36,37,36,36.5,37,37.5,38,39,36,37,36,40,37]

mean_suhu = numpy.mean(suhu)
print("Mean = ", format(mean_suhu,'.2f'))
```  
## Median  
```bash  
import numpy

suhu = [36,37,36,36.5,37,37.5,38,39,36,37,36,40,37]

median_suhu = numpy.median (suhu)
print("Median = ", format(median_suhu,'.2f')) 
``` 
## Mode  
```bash  
from scipy import stats

suhu = [36,37,36,36.5,37,37.5,38,39,36,37,36,40,37]

mode_suhu = stats.mode(suhu)
print("Mode = ", mode_suhu)  
```
  

    
  

Refer to:  
https://www.w3schools.com/python/python_ml_mean_median_mode.asp
