# Data Schemas

Specifications for all references to regions, sectors and age groups
can be found in `enums.py`

## `credit_score.csv`

* Region: UK region
* mean: (-inf to inf) mean personal credit score per region
* stdev: (0 to inf) standard deviation of credit score per region

## `demand.csv`

* columns: UK sector
* rows: UK sector
* values: (0 to 1) demand contribution from row sector
  to column sector. All rows sum to 1.
 
## `earnings.csv`
 
* Region: UK region
* earnings: (0 to inf) median personal earnings per region

## `expenses.csv`

* Region: UK region
* expenses: (0 to inf): minimum personal expenses per region

## `gdp.csv`

* Region: UK Region
* Sector: UK Sector
* Age: Age banding
* gdp: (0 to inf) GDP per region, sector, age group


## `growth_rates.csv`

* Sector: UK Sector
* growth_rates: (0 to inf) historic peacetime growth rates per sector

## `input_output.csv`

* Sector: UK Sector
* employee_compensation: (0 to inf): mean employee compensation per sector
* taxes_minus_subsidies: (0 to inf): mean taxes minus subsidies per sector
* capital_consumption: (0 to inf): mean capital consumption per sector
* net_operating_surplus: (0 to inf): mean net operating surplus per sector

## `keyworker.csv`

* Sector: UK Sector
* keyworker: (0 to 1): fraction workers per sector who still go to work and are unaffected by lockdown

## `largecap_pct_turnover.csv`

* Sector: UK Sector
* largecap_pct_turnover (0 to 1): fraction of turnover generated by large-cap corporations per sector

## `populations.csv`

* region: UK Region
* columns: A0, A10, ..., A80 (10 year age bands)
* values: (0 to inf): population of each region by age group

## `smallcap_cash.csv`

* Sector: UK Sector
* smallcap_cash: (0 to inf): number of days of surplus cashflow of cash reserves per sector for small-cap corporations

## `supply.csv'`

* columns: UK sector
* rows: UK sector
* values: (0 to 1) supply contribution from row sector
  to column sector. All rows sum to 1.

## `vulnerability.csv`

* Sector: UK Sector
* vulnerability: (0 to 1): index representing maximum productivity of each sector under a lockdown situation

## `wfh.csv`

* Sector: UK Sector
* wfh: (0 to 1): productivity of each sector when working from home

## `workers.csv`

* Region: UK Region
* Sector: UK Sector
* Age: Age banding
* workers: (0 to inf) Number of workers per region, sector, age group