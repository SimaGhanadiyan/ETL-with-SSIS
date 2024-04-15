# ETL Process with SSIS

This repository contains a simple data warehouse designed for practicing the ETL (Extract, Transform, Load) process using SSIS (SQL Server Integration Services) software.

## Description

The ETL process involves the following steps:

1. **Initial Load of Dimensions:** Each dimension is loaded separately using SSIS packages for the initial data load.
   
2. **Incremental Load:** Incremental load queries are implemented using Execute SQL Task to update dimension data incrementally.

3. **Fact Table Handling:** 
   - A staging layer is created using Data Flow Tasks for the fact table.
   - Data is populated and cleared in each run.
   - A core layer is established to integrate the fact data.

4. **Deployment:** The project is deployed to SQL Server for execution.

## Overview

This repository provides valuable insights into implementing the ETL process using SSIS. It serves as a practical resource for understanding how to design and execute ETL workflows efficiently.
