# SYSTEM TABLE STRUCTURE

## SQL TABLE NAME: tbl_lib
rows: ID | Qty | Stock_Code | Article | Description | Unit | ris_no | Category 

## SQL TABLE NAME : tbl_division

rows: divisionID | divisionName


## SQL TABLE NAME : tbl_section

rows: sectionID | sectionName | division 

## SQL TABLE NAME : section_inventory

rows: sectionID | stock_code| sectionQty

## SQL TABLE NAME : users
rows: sectionID | divisionID

## SQL TABLE NAME : tbl_depletion_thresholds
rows: id | stock_code | divisionID | depletion_threshold

## SQL TABLE NAME : issuance_records
rows: id | date | stock_code | qty | division | section

## SQL TABLE NAME : delivery_records
rows: id | date | stock_code | qty | divisionID | sectionID

