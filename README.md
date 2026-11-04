# Banking Data Engineering Cortex Code Lab

A 60-minute Cortex Code hands-on lab for **Data Engineering**, using Cortex Code in Snowsight.

Build a repeatable, reviewed customer net-spend transformation over synthetic retail-banking card and account transactions.

**Lab guide app:** _the facilitator adds the Streamlit URL here after deploying._

> All data in this repository is synthetic. It contains no customer data.

## For the Snowflake admin (before the lab)
1. Open [`admin/setup.sql`](admin/setup.sql) and run it **one section at a time** with an approved admin role.
2. Section 3: unzip [`data/banking-data-engineer-coco-hol-data.zip`](data/banking-data-engineer-coco-hol-data.zip) and upload the CSVs to the `HOL_DATA` stage in Snowsight.
3. Section 4 expected results: LOCATIONS 5 rows, CUSTOMERS 100 rows, TRANSACTIONS 1200 rows; NET_SPEND 339300.29.
4. Section 5: creates one shared participant role and one schema per participant; grant the role to each user. Keep the user roster private.
5. Section 7: verify as a participant role, not as admin.
6. Section 8 (cleanup) is commented out; run it only after the event with approval.

## For participants
Open the lab guide app, start at **Overview**, and follow the pages in order. Use only your assigned schema and role.

## Starter files
Each lab step that needs a file shows it in the app with a copy button and a download, plus the path to save it to.

## Attribution
Built from [coco-hol-template](https://github.com/sfc-gh-obenning/coco-hol-template) with the customer-coco-hol skill.
