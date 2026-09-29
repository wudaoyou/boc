# Draft email: Missing S/4HANA region entries

**Subject:** Action required: Review missing region entries for France, the United Kingdom, and Spain in SAP S/4HANA

Dear [Customer Name],

We compared the Employee Central state/province values with the SAP S/4HANA region extracts provided for France, the United Kingdom, and Spain. The following areas do not yet have a confirmed SAP region code in our mapping:

| Country (SAP key) | EC code | Area |
| --- | --- | --- |
| France (FR) | BL | Saint Barthélemy |
| France (FR) | CP | Clipperton Island |
| France (FR) | MF | Saint Martin |
| France (FR) | NC | New Caledonia |
| France (FR) | PF | French Polynesia |
| France (FR) | TF | French Southern Territories |
| France (FR) | YT | Mayotte |
| United Kingdom (GB) | MDW | Medway |
| United Kingdom (GB) | CAY | Caerphilly |
| United Kingdom (GB) | CWY | Conwy |
| Spain (ES) | CE | Ceuta |
| Spain (ES) | ML | Melilla |

Please review these values in the target S/4HANA system. For any region that is required for employee address replication and does not already exist, please maintain the appropriate country/region entry in **V_T005S** and its description where applicable. If a region already exists under a different SAP code, or an EC value should be excluded or treated as a separate country, please confirm the intended handling.

Once the SAP region codes are confirmed, please send us the country, SAP region code, and region description for each item. We will then complete the EC-to-SAP value mapping. The attached `state_mapping.xlsx` lists the open items with blank SAP Value cells in the **France T005S Map**, **GB T005S Map**, and **Spain T005S Map** tabs.

Thank you,

[Your Name]
