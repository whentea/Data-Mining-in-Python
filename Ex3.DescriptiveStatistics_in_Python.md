<h1 align="center">
	<br>
	DESCRIPTIVE STATISTICS (DS)
	<br>
</h1>
   
  
`DS dapat digunakan untuk mengetahui nilai observasi data dan untuk mengetahui sebaran data"`  
## Data  
  
```bash
Data dapat diunduh dari https://mathcs.org/statistics/datasets/index.html atau https://github.com/whentea/Data_Collection
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
