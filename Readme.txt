This folder includes data and results for the research "Assembly Line Balancing Problem with Parallel Stations and Variable Task-Worker Options". All files are stored in Excel.

"experiment dataset" contains the input data for all instances. In each tab, column "task ID" shows the task ID, "immediate predecessors" lists the predecessors for the task, "model type" refers to the product type, and column D-F are three worker options. Each worker option is formatted in this way: "X_n,Y_m,Z_p,...:d" where "X","Y","Z" represent the worker types, "n","m","p" show the quantity for "X","Y","Z", and "d" is the duration. Note that the number of worker types per task may vary from 1.

All instances are modified from a basic task list in tab "basic". In each instance, tasks are randomly selected according to their problem size. When the problem scale is for 2 product types, then only product type "A" and "B" will be considered.

Detailed definition on OS (order strength) can be searched in:
Otto, Alena, Christian Otto, and Armin Scholl. 2013. “Systematic data generation and test design for solution algorithms on the example of SALBPGen for assembly line balancing.” European Journal of Operational Research 228 (1): 33–45.

Other files are results. "MIP only" includes the results for using MIP only. "MIP with LBBDA" refers to use LBBDA as the solution approach. "2mod" and "3mod" are for 2 product types and 3 product types, respectively. Instance 1-5 have 5 tasks per product, 6-10 have 7 tasks per product, 11-15 have 10, 16-20 have 12, 21-25 have 15 and 26-30 have 18 tasks per product.
