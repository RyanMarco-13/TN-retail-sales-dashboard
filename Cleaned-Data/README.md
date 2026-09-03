# Raw Data

This folder contains the original, uncleaned sales dataset (`raw_sales_data.csv`) with 414 records.

## Known issues in this raw file:
- Duplicate rows
- Inconsistent city name spelling and casing (chennai, CHENNAI, Chenai, Combatore)
- Inconsistent payment mode casing (UPI, upi, Upi)
- Mixed date formats (DD-MM-YYYY, MM/DD/YYYY, YYYY-MM-DD, DD/MM/YY)
- Currency symbols mixed into the UnitPrice column
- A few negative Quantity values
- Some TotalAmount values that don't match Quantity × UnitPrice
- Missing values in City, PaymentMode, and Rating

See the main [README](../README.md) for the full cleaning process applied to this data.
