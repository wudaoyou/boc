# Draft email: Missing S/4HANA region entries

**Subject:** Action required: Review missing region entries for France, the United Kingdom, and Spain in SAP S/4HANA

Dear [Customer Name],

As part of the Business Integration Builder (BIB) configuration, we are mapping Employee Central state/province values to SAP S/4HANA regions for France, the United Kingdom, and Spain. Please confirm the SAP region codes for the following areas so we can complete the mapping:

France (FR):
- EC code BL: Saint Barthélemy
- EC code CP: Clipperton Island
- EC code MF: Saint Martin
- EC code NC: New Caledonia
- EC code PF: French Polynesia
- EC code TF: French Southern Territories
- EC code YT: Mayotte

United Kingdom (GB):
- EC code MDW: Medway
- EC code CAY: Caerphilly
- EC code CWY: Conwy

Spain (ES):
- EC code CE: Ceuta
- EC code ML: Melilla

Please review these values in the target S/4HANA system. For any region that is required for employee address replication and does not already exist, please maintain the appropriate country/region entry in **V_T005S** and its description where applicable. If a region already exists under a different SAP code, or an EC value should be excluded or treated as a separate country, please confirm the intended handling.

Once the SAP region codes are confirmed, please send us the country, SAP region code, and region description for each item. We will then complete the EC-to-SAP value mapping. The attached `state_mapping.xlsx` lists the open items with blank SAP Value cells in the **France T005S Map**, **GB T005S Map**, and **Spain T005S Map** tabs.

Thank you,

[Your Name]
