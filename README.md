# Calculate-Pure-Premium-of-auto-insurance
Variable information in the data:

ID: policy key
Veh_value: market value of the vehicle in $10,000’s
Veh_body: Type of vehicles
Veh_age: Age of vehicles (1=youngest, 4=oldest)
Gender: Gender of driver
Area: Driving area of residence
Dr_age: Driver’s age category from young (1) to old (6)
Exposure: The basic unit of risk underlying an insurance premium
Claim_ind: Indicator of claim (0=no, 1=yes)
Claim_counts: The number of claims
Claim_cost: Claim amount

‘Pure Premium’ is calculated using this formula:  PP = Frequency * Severity = loss $ / exposure.
The model results are not evaluated on accuracy, but on the *Gini index*
