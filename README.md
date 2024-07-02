July 2024

UPS World Ease which is a contractual service. UPS World Ease shipments move to a single Port of Entry (POE), clear customs, split, and continue on for final delivery. The UPS World Ease service is the grouping of one or more shipments destined for one import country (or into the European Union for European Union consolidated shipments) into one master shipment for the purpose of consolidated customs clearance. It provides an automated solution for uploading of PLD, the planned flow to final consignee, and simplified billing.

The UPS World Ease service is available for US and non-US origins to all of the current consolidated clearance countries. The European Union service provides consolidation of multiple country shipments into one outbound European Union shipment. The service is available for all UPS services.

All child shipments must have the same ship date, importer of record, and billing option. Valid service levels and service level combinations are provided in the shipper-specific POE file received from UPS.

UPS World Ease service is valid for UPS Worldwide Express, UPS Worldwide Expedited, UPS Standard, UPS Worldwide Saver®/UPS Express Saver, UPS Worldwide Express Plus, and UPS Worldwide Express NA1 services.

UPS World Ease service is also valid for Transborder movement between European Union countries and non-European Union countries within Europe (e.g., Norway; Switzerland) for shipments that contain goods not in free circulation.

For UPS World Ease, the ultimate consignee of each child shipment is captured. Each child shipment is rated and priced individually.

UPS World Ease service does not require separate freight rates to be set up. UPS World Ease shipments are rated using the worldwide service rates. Each child shipment should be rated and priced separately using the current worldwide service rates.

UPS World Ease shipments are not eligible for UPS Returns services.

Movements between two European Union countries that contain goods not in free circulation are valid for UPS World Ease. Likewise, movements between two European Union countries that contain goods in free circulation are not valid for UPS World Ease.






- Note: The child shipments are not required to have the same service level. Valid service levels are based on the unique information provided in the shipper-specific POE file received from UPS.

All child shipments must have the same shipper number, ship date, Importer of Record, and billing option.

For UPS World Ease service to the European Union, the master shipment must contain individual shipments with destinations in different countries within the European Union.

For UPS World Ease consolidated shipments destined to the European Union, the shipping system must allow the importer of record (sold to) country to be any country within the European Union.

- For UPS World Ease consolidated shipments destined to the European Union, the shipping system must allow the importer of record (sold to) country to be any country within the European Union.

- For UPS World Ease consolidated shipments destined to the European Union, the shipping system must allow the doc box (ship to) address to be any country within the European Union.

	
The following billing options must be valid: Prepaid; Free on Board; Cost and Freight; Freight Collect; Third Party; Delivered Duty Paid; V.A.T. Unpaid; and Free Domicile.

- The importer account number must be required for all valid billing options for UPS World Ease.

Credit card must not be a valid payment option.

All child shipments must clear in the same port as the master shipment.

UPS World Ease service must be valid for UPS Worldwide Express, UPS Worldwide Expedited, UPS Standard, UPS Worldwide Saver/UPS Express Saver, UPS Worldwide Express Plus, and UPS Worldwide Express NA1 services.

UPS World Ease shipments must be valid for Transborder movement between European Union countries and non-European Union countries within Europe (e.g., Norway; Switzerland) for shipments that contain goods not in free circulation.

- UPS World Ease shipments must not have a mix of child shipments with goods in free circulation and goods not in free circulation.

All existing package types for the services valid for UPS World Ease shipments must be allowed, with the exception of letters and value boxes (i.e., 10KG and 25KG) for UPS World Ease child shipments.

- Note: The package types may be mixed within a master shipment.


Specific doc indicator values are required.

- Document shipments must not be valid for child shipments; i.e., UPS World Ease shipments must be non-docs only.

- The doc box must be documents only.


The ship to of each child shipment must be captured. Each child shipment must be rated and priced individually. The following rules must apply.

- Each shipment must be zoned from origin to destination.

- Freight charges must be calculated from origin (ship from address) to the ship to address.

- Free Domicile, Delivered Duty Paid V.A.T. Unpaid [Split Duty & Tax (SDV)] surcharges must apply at the master shipment level.

- Extended destination and residential surcharges must apply at the child shipment level.



UPS World Ease shipments must be rated using the worldwide service rates.

- Rate and price each child shipment separately using the current worldwide service rates. All surcharges and accessorials available to the current worldwide and Transborder movements must be valid for UPS World Ease shipments with the following exceptions.

    - Early A.M.

    - Collect on Delivery


UPS World Ease shipments must not be eligible for UPS Returns services; i.e., UPS Returns services cannot be added to UPS World Ease master shipments.

The shipping system must allow the user to designate a maximum of nine copies, in increments of 1, per customs documentation.

- The minimum number of copies for the master invoice must be three.

- The minimum number of copies for the consolidated invoice detail must be one.

- The minimum number of copies for the NAFTA, CO, and SED must be one.

    - Note: These documents are optional.

- The minimum number of copies for child invoice must be zero.

    - A child invoice is not required.

The POE for each destination country (or multiple European Union countries) will be defined based on the UPS World Ease service contract.

- Example: The POE, per the contract for all EUCC shipments for a specific customer should flow through Germany. The Account Executive should be able to set up Germany as the POE. During shipment processing, the shipping system should select Germany as the POE.

The shippers (authorized to ship the European Union shipments) must move to a single POE, clear customs, split, and continue on for final delivery.

In addition to all currently required shipment data, the following must be created for master shipment when the user closes out and all specific shipments have been consolidated.

- UPS World Ease number (Global consolidated clearance number –GCCN) – the master shipment ID.

    - This field contains an 11-digit alphanumeric that identifies the shipment as being a UPS World Ease shipment.

    - The UPS World Ease number (GCCN) must be identical to the shipment ID on the lead (i.e., master) shipment.

    - The UPS World Ease number (GCCN) must be used to identify all the child shipments associated with the consolidated shipment.


- Clearance country (Port of entry country)

- Clearance port

- Number of shipments consolidated.

    - This field must contain the total number of shipments (the lead doc box and all the child shipments) associated with the consolidated shipment.

- Number of packages consolidated.

    - The number of packages must include the lead doc box and packages in the consolidation clearance count.

- Total weight consolidated.

    - The total weight must include the lead doc box and all packages.

- Total value consolidated

    - The value of the entire consolidated clearance movement must be shown in only one currency.

- Weight unit of measure in LBS or KGS (Represents the unit of measure used for the total actual weights of the consolidated shipment, as found on the master invoice).

    - Valid entries are “LBS” for Pounds and “KGS” for Kilograms.


The user must provide an importer of record (sold to) name and address for any UPS World Ease shipment process.

- The importer of record must be entered once for each consolidated shipment.

The user must provide the importer of record account number for all valid UPS World Ease billing options.

- If the origin of the shipment is US, the destination is Canada, and a non-resident importer, the user must enter the non-resident importer account number in place of the importer of record account number.

    - Note: The importer of record (sold to address) is typically different than the ship to address for UPS World Ease shipments. Therefore, the user should be able to select from an existing list or add another importer of record for each shipment.

- If the origin of the shipment is Canada, the destination is US, and a non-resident importer, the user must enter the non-resident importer account number in place of the importer of record account number.

The user must provide at least one invoice line entry for each shipment in the consolidated clearance movement.

The currency for all child shipments within a UPS World Ease shipment must be of the same currency type.

The weight for all child shipments within a UPS World Ease shipment must be of the same unit of measure (LBS or KGS).

The user must have the ability to process single-piece and multiple-piece child shipments.

The shipments that are selected as consolidated clearance movements, but do not meet all business rules for consolidation, must be handled as regular (non-consolidated) international shipments.

- Note: Refer to the Aggregate UPS World Ease shipments (UPS World Ease closeout process) section for a complete list of business rules.

A master carton will remain open for 7 days, on the 8th day the master carton will be deleted from the system.

Only the user that added a child shipment to a master carton can remove the child shipment from the master carton.
