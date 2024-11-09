This dataset can track crucial details for each parcel, such as its origin, destination, status, and more.

## Dataset Fields for Parcel Information

| Field Name            | Data Type | Description                                          |
|-----------------------|-----------|------------------------------------------------------|
| ParcelID              | String    | Unique identifier for each parcel                    |
| SenderName            | String    | Name of the person or company sending the parcel     |
| SenderAddress         | String    | Full address of the sender                           |
| SenderContact         | String    | Contact number or email of the sender                |
| RecipientName         | String    | Name of the person or company receiving the parcel   |
| RecipientAddress      | String    | Full address of the recipient                        |
| RecipientContact      | String    | Contact number or email of the recipient             |
| ParcelWeight          | Float     | Weight of the parcel in kilograms                    |
| ParcelDimensions      | String    | Dimensions of the parcel (Length x Width x Height in cm) |
| ParcelValue           | Float     | Declared value of the parcel (in local currency)     |
| ShippingDate          | Date      | Date the parcel was shipped                          |
| EstimatedDelivery     | Date      | Estimated delivery date                              |
| ActualDelivery        | Date      | Actual delivery date (if delivered)                  |
| Status                | String    | Current status of the parcel (e.g., In Transit, Delivered, Out for Delivery, Returned) |
| TrackingUpdates       | List      | List of tracking events (with location and timestamp)|
| DeliveryMethod        | String    | Type of delivery method (e.g., Standard, Express, Same-Day) |
| ShippingCost          | Float     | Cost of shipping (in local currency)                 |
| PaymentStatus         | String    | Status of payment (e.g., Paid, Unpaid, COD)          |
| HandlingInstructions  | String    | Special handling instructions (e.g., Fragile, Keep Upright) |
| DeliveryAttempts      | Integer   | Number of delivery attempts made                     |
| ReturnStatus          | Boolean   | Indicates if the parcel was returned                 |
| ReturnReason          | String    | Reason for return (if applicable)                    |
