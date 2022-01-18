# NAICS
<img src="img.svg.png">

The North American Industry Classification System or NAICS is a classification of business establishments by type of economic activity. It is used by government and business in Canada, Mexico, and the United States of America.

It has largely replaced the older Standard Industrial Classification (SIC) system, except in some government agencies, such as the U.S. Securities and Exchange Commission (SEC).

An establishment is typically a single physical location, though administratively distinct operations at a single location may be treated as distinct establishments. Each establishment is classified to an industry according to the primary business activity taking place there. NAICS does not offer guidance on the classification of enterprises (companies) which are composed of multiple establishments.

NAICS is designed to provide common definitions of the industrial structure of the three countries and a common statistical framework to facilitate the analysis of the three economies.


## The data provided contains:
<b>Raw data:</b><br>
15 CSV files beginning with RTRA.<br>
These files contain employment data by industry at different levels of aggregation; 2-digit NAICS, 3-digit NAICS, and 4-digit
NAICS. <br>
<ul>
Columns mean as follows:
    <li>
 SYEAR: Survey Year.
        </li>
    <li>
 SMTH: Survey Month.
        </li>
    <li>
 NAICS: Industry name and associated NAICS code in the bracket.
        </li>
    <li>
 _EMPLOYMENT_: Employment.
        </li>
</ul>
<b>b- LMO Detailed Industries by NAICS:</b><br> 
An excel file for mapping the RTRA data to the desired data. <br>
The first column of this file has a list of 59 industries that are frequently used.<br>
The second column has their NAICS definitions. <br>
Using these NAICS definitions and RTRA data, you would create a monthly employment data series from 1997 to 2018 for these 59
industries.<br>

<b>c- Data Output Template:</b><br>
An excel file with an empty column for employment. 

## Task
In this task, we need to understand how the NAICS works as a hierarchical structure for defining industries at different levels of aggregation.

<b>For example:</b><br>
In NAICS 2017 – Statistics Canada.pdf (see page 22), a 2-digit NAICS industry (e.g., 23 - Construction) is composed of some 3-digit NAICS industries (236 - Construction of buildings, 237 - Heavy and civil engineering construction, and a few more 3-digit NAICS industries).

Similarly, a 3-digit NAICS industry (e.g., 236 - Construction of buildings), is composed of 4-digit NAICS industries (2361 - Residential building construction and 2362 -Non-residential building construction).

Article: https://www.datainsightonline.com/post/how-economic-crisis-affected-the-industries
