# Genesco(Python Project)

Retail Sales Comparative Sales Increase
Comparative sales increase is the "holy grail of retail," and so our project partner wants to understand how well the metrics his company collects help explain the change in sales for a given week for one fiscal year compared to the same week for the previous fiscal year. Comparing sales for the same period in two consecutive years is a measure of growth for the company and provides value to shareholders. The data provided shows this measure as a percent change ((SALES_AMT_TY - SALES_AMT_LY ) / SALES_AMT_LY) in the current time period as compared to the previous one.

- is the company measuring the right things?
- which metrics correlate most with comp sales increase?
- what measures either influence or help explain variations in comp increase
Metrics provided include employee metrics. The stores are "lightly staffed" and employees, typically, are full-time career employees. They earn a base compensation rate plus commission on sales. Managers and assistant managers may also earn bonuses.

Metrics also include foot traffic (measured by people exiting through the front door) and conversion rate (the percentage of customers who enter the store and make a purchase). The dataset includes a calculated measure STRAK_COMP_TRAFFIC_DELTA, which is the difference between the comparative sales percent and the foot traffic conversion rate. They consider this an important measure because if traffic is down and sales are up that tells a different story than if traffic is up but sales are down.

Stores report sales metrics daily, but they have been summed to weekly amounts in the provided dataset.

The fiscal year runs from February 1 to January 31, and the FY is for the ending year. For example FY2020 began on February 1, 2019 and will end January 31, 2020.

It may make sense to segment out different store types and different volume bands.

data dictionaries
nss_dictionary.xlsx provides a description of the sales, traffic, and employee metrics provided
store_master.xlsx provides information about each store
