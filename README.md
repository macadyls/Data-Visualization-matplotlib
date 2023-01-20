# Data Visualization using matplotlib

## Pymaceutical

 The dataset given is from a pharmaceutical company, Pymaceutical, that has recently completed an animal study for cancer.
 249 mice identified with SCC tumour growth were treated through a variety of drug regimens, with Capomulin being the drug of interest.
 Over the course of 45 days, tumour development was observed and measured.
 
 ## Observable trends
 
1. Capomulin and Ramicane had the lowest tumor volume of 40.68 mm and 40.22 mm respectively. 
2. Capomulin and Ramicane were also the only drug regimens that had a standard error below 5, implying the more reliable choice. 
3. Capomulin and Ramicane were the most popular drug regimen with 230 and 228 mice respectively.
4. There is a strong positive correlation between mouse weight and average tumor volume at 0.83. 
This indicates that as mouse weight rises, the potential tumor size follows.
5. There is a potential outlier in the Infubinol regimen as a mouse had a tumour volume (36.32 mm) below the lower bound (36.83 mm). 
However, it is by a relatively small amount.
6. Mouse ID g989 had duplicate varying tumor sizes at the same timepoints and had to therefor be excluded in the analysis.

## Technical report and plots

The in-depth [technical report](https://github.com/macadyls/Data-Visualization-matplotlib/blob/main/pymaceuticals.ipynb) includes plots such as:
- Bar charts
- Pie charts
- Box and whisker plot
- Line chart
- Scatter plot
