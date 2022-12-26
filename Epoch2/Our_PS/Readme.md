# PS

There are four problem statments. We choose: PS1

## Cisco Inventory Management and Demand Prediction

Cisco manages inventory stock for multiple products (identified by PLID) for different business units and stores
them in storage facilities of different capacities. The company should be able to predict demand for each product
for the upcoming quarter and plan the inventory stock to ensure there are no delays in order fulfillment.
Additionally, they need to ascertain which product should be stocked in which storage facility to efficiently utilize
the available facilities.

The storage facility capacity is defined by the number of products that can be stored and can be categorized into
T-shirt sizes XS, S , M , L, XL. Please use the appropriate binning based on the given data for the number of
products in each facility. Like XS can be 0-100 products and so on.

Based on the dataset of historical month-wise product booking data, write the software to predict demand for
each product for the upcoming quarters and assign the appropriate facility category in which that need to be
stored. Clean the data appropriately and Evaluate the model’s accuracy.

### Data Attributes
- **Business Unit:** Business unit where Product ID belongs.
- **Product Family:** Broad family name to which the Product ID is hierarchically mapped.
- **PLID:** Name of the Product ID against which the booking is made.
- **Fiscal Quarter:** Fiscal Quarter in which the product booking was made.(eg: Q1 FY2016)
- **Fiscal Month:** Fiscal Month Name in which the product booking was made.(eg: OCT FY2016)
- **Booked_Qty:** Booked quantity of the Product ID.
- **Booking_Date:** This Date attribute holds the date on which the Product booking was made.
