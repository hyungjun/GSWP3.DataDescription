Despike 2m air temperature (Tair)
=================================

Algorithm
---------
1. detect spikes (applied for each month)
    - when residual after remove diurnal and sub-diurnal cycle (harmonic wave number = days & days*2) is greater than 6-sigma
    - only for grids having considerable diurnal cycle (here, when 3-hourly variance < diurnal & sub-diurnal cycle * 2)

2. apply fail-safe
    - considering observational record lowest/highest (-89.2, 58 degC), clipping out 3-hourly value which exceeds -95 and 65 degC.

3. replace spikes
    - spikes replaced with linearly interpolated residuals + diurnal & sub-diurnal cycle



Annual summary
--------------

![Tair.1901](images/v1-v1.1.Tair.1901.png)
![Tair.1902](images/v1-v1.1.Tair.1902.png)
![Tair.1903](images/v1-v1.1.Tair.1903.png)
![Tair.1904](images/v1-v1.1.Tair.1904.png)
![Tair.1905](images/v1-v1.1.Tair.1905.png)
![Tair.1906](images/v1-v1.1.Tair.1906.png)
![Tair.1907](images/v1-v1.1.Tair.1907.png)
![Tair.1908](images/v1-v1.1.Tair.1908.png)
![Tair.1909](images/v1-v1.1.Tair.1909.png)
![Tair.1910](images/v1-v1.1.Tair.1910.png)
![Tair.1911](images/v1-v1.1.Tair.1911.png)
![Tair.1912](images/v1-v1.1.Tair.1912.png)
![Tair.1913](images/v1-v1.1.Tair.1913.png)
![Tair.1914](images/v1-v1.1.Tair.1914.png)
![Tair.1915](images/v1-v1.1.Tair.1915.png)
![Tair.1916](images/v1-v1.1.Tair.1916.png)
![Tair.1917](images/v1-v1.1.Tair.1917.png)
![Tair.1918](images/v1-v1.1.Tair.1918.png)
![Tair.1919](images/v1-v1.1.Tair.1919.png)
![Tair.1920](images/v1-v1.1.Tair.1920.png)
![Tair.1921](images/v1-v1.1.Tair.1921.png)
![Tair.1922](images/v1-v1.1.Tair.1922.png)
![Tair.1923](images/v1-v1.1.Tair.1923.png)
![Tair.1981](images/v1-v1.1.Tair.1981.png)
![Tair.1982](images/v1-v1.1.Tair.1982.png)
![Tair.1983](images/v1-v1.1.Tair.1983.png)
![Tair.1984](images/v1-v1.1.Tair.1984.png)
![Tair.1985](images/v1-v1.1.Tair.1985.png)
![Tair.1986](images/v1-v1.1.Tair.1986.png)
![Tair.1987](images/v1-v1.1.Tair.1987.png)
![Tair.2001](images/v1-v1.1.Tair.2001.png)
![Tair.2002](images/v1-v1.1.Tair.2002.png)
![Tair.2003](images/v1-v1.1.Tair.2003.png)
![Tair.2004](images/v1-v1.1.Tair.2004.png)
![Tair.2005](images/v1-v1.1.Tair.2005.png)
![Tair.2006](images/v1-v1.1.Tair.2006.png)
![Tair.2007](images/v1-v1.1.Tair.2007.png)
![Tair.2008](images/v1-v1.1.Tair.2008.png)
![Tair.2009](images/v1-v1.1.Tair.2009.png)
![Tair.2010](images/v1-v1.1.Tair.2010.png)
![Tair.2011](images/v1-v1.1.Tair.2011.png)
![Tair.2012](images/v1-v1.1.Tair.2012.png)
![Tair.2013](images/v1-v1.1.Tair.2013.png)
![Tair.2014](images/v1-v1.1.Tair.2014.png)

