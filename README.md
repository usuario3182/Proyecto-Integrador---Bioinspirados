# Proyecto-Integrador---Bioinspirados
Proyecto enfocado en replicar los resultados del paper Simultaneous Optimization of Deacetylation Degree and Molar Mass of Chitosan from Shrimp Waste con autores Daniel Dumitru Dinculescu 1 , Manuela Rossemary Apetroaei 2 , Cristiana Luminit,a Gîjiu 1,*, Mirela Anton 1 , Laura Enache 1 , Verginica Schröder 3 , Raluca Isopescu 1 and Ileana Rău

El paper utilizado: Dinculescu, D.D.;
Apetroaei, M.R.; Gîjiu, C.L.; Anton,
M.; Enache, L.; Schröder, V.; Isopescu,
R.; R ˘au, I. Simultaneous
Optimization of Deacetylation
Degree and Molar Mass of Chitosan
from Shrimp Waste. Polymers 2024,
16, 170. https://doi.org/10.3390/
polym16020170

# librerías

Se implementan métricas de desempeño como **IGD** (Inverted Generational Distance) y **HV** (Hypervolume) para comparar los frentes de Pareto obtenidos con los reportados en el artículo original.  
Este proyecto utiliza las siguientes librerías de Python:

- `pymoo`  
  - `pymoo.indicators.igd.IGD`  
  - `pymoo.indicators.hv.HV`  
  - `pymoo.operators.mutation.pm.PM`  
  - `pymoo.operators.crossover.sbx.SBX`  
  - `pymoo.algorithms.moo.nsga2.NSGA2`  
  - `pymoo.optimize.minimize`  
  - `pymoo.core.problem.Problem`  

- `pandas`  
- `numpy`  
- `statsmodels`  
- `matplotlib`  

## Instalación de librerías

Se recomienda usar **pip** para instalar las dependencias:

```bash
# Instalar pymoo
pip install pymoo

# Instalar pandas, numpy, statsmodels y matplotlib
pip install pandas numpy statsmodels matplotlib
