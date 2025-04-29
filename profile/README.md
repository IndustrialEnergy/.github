# Industrial Energy Data Exploration Interface
![Industrial Energy-](https://github.com/user-attachments/assets/f9e7616f-1b22-4c98-bf54-0747004b5be6)

#### Team Members/Graduate Students: Oksana Protsukha, Naomi Moraes, Eva Newby, Yos Ramirez. 

#### Client and Advisor: [Dr. Eric Masanet](https://bren.ucsb.edu/people/eric-masanet), the Industrial Sustainability Analysis Laboratory.

[Project Summary on the Bren Website](https://bren.ucsb.edu/projects/industrial-energy-data-exploration-interface)

This is a capstone project for the [Master of Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at [Bren School of Environmental Science and Management](https://bren.ucsb.edu/), University of California, Santa Barbara.

The industrial sector is a major contributor to greenhouse gas (GHG) emissions in the United States, accounting for 30% of energy-related CO₂ emissions with 1,360 million metric tons released in 2020 [1]. Dr. Eric Masanet and his research team at the Industrial Sustainability Analysis Laboratory, at the University of California, Santa Barbara, address this challenge by developing industrial decarbonization pathways that illuminate needed technology transitions. One of their key data sources is  the Industrial Assessment Centers (IAC) database, which contains over 40 years of industrial energy efficiency audits and recommendations, a program funded by the Department of Energy (DOE) and managed by over 50 universities across the country. Even though it is a valuable resource, the IAC database has several limitations. It lacks information on potential savings in GHG emissions and local air pollutants, and does not adjust for changes in technology costs over time. Additionally, it provides limited data visualization capabilities and its frequent updates complicate recent and/or real-time analysis. This project aims to address these gaps by developing a publicly accessible interface that integrates GHG emissions, air pollutants, and other key data with the IAC database, and adjusts economic metrics to present values for historical data. By streamlining access to critical data and expanding analytical and data visualization capabilities, this tool will accelerate research into industrial energy efficiency and support broader decarbonization efforts in the manufacturing sector. 

```
          ) ) )                     ) ) )
        ( ( (                      ( ( (
      ) ) )                       ) ) )
   (~~~~~~~~~)                 (~~~~~~~~~)
    | POWER |                   | POWER |
    |       |                   |       |
    I      _._                  I       _._
    I    /'   `\                I     /'   `\
    I   |   N   |               I    |   N   |
    f   |   |~~~~~~~~~~~~~~|    f    |    |~~~~~~~~~~~~~~|
  .'    |   ||~~~~~~~~|    |  .'     |    | |~~~~~~~~|   |
/'______|___||__###___|____|/'_______|____|_|__###___|___|
```
[1] Energy.gov. “DOE Industrial Decarbonization Roadmap.” Accessed September 23, 2024.
https://www.energy.gov/industrial-technologies/doe-industrial-decarbonization-roadmap.

## Repositories:
This project contains 2 repositories - 'dataintegration' and 'dashboard'.
- 'dataintegration' contains all the code required to clean, normalize, and integrate the datasets, and created an integrated dataset as the output. 
- 'dashboard' contains all the code necessary to create and deploy our interactive web application. 

## Key Datasets:
- Industrial Assessment Centers (IAC) data.
- Producer Price Intex (PPI) from the U.S Bureau of Labor Statistics.
- Combustion Emission Factors by Fuel Type from the U.S Environmental Protection Agency (EPA).
- Electricity Emissions by State and Year from the Energy Information Administration (EIA).
- Electricity Generation by State and Year from the Energy Information Administration (EIA).

## Data Produced:
- The scripts in the 'dataintegration' creates a cleaned, integrated dataset that is then used in the dashboard. Running the 'dashboard' code without running the 'dataintegration' code will not produce the correct output. 

## Acknowledgements:

Faculty Advisor & Client
- Dr. Eric  Masanet, The Bren School of Environmental Science & Management, U.S. Department of Energy, Capstone Advisor
- Dr. Carmen Galaz Garcia, The Bren School of Environmental Science & Management

Testing, Research & Development
- Aiden O’Neil, The Bren School of Environmental Science & Management 
- Dylan Radovic, The Bren School of Environmental Science & Management 

Project Data Resources: 
- U.S. Department of Energy, Industrial Assessment Center
- U.S. Environmental Protection Agency
- U.S. Department of Labour
- Bureau of Labor Statistics

