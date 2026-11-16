# Tenant Management System
An Android app for landlords to record tenants, see total rent, and call tenants.
## Features
- Register and log in
- Dashboard with number of tenants and total rent
- Add tenants and view all tenants (saved with Room)
- Call a tenant, options menu and navigation drawer.

## Architecture
ui/ Activities, Fragments and TenantViewModel (UI layer)
data/ Tenant, TenantDao, TenantDatabase, TenantRepository (data layer)
Screens → TenantViewModel (LiveData) → TenantRepository → Room

## Team
| Stage              | Member         | Admission No. | Pull request                                                         |
|--------------------|----------------|---------------|----------------------------------------------------------------------|
| 1 Lead             | Mutisya        | 152360        |                                                                      |
| 2 ViewModel        | Faith Kaburu   | 189528        | (https://github.com/JustTheTech-debug/TenantManagementSystem/pull/2) |
| 3 Room             | Eunice Wanjiku | 154722        | (https://github.com/JustTheTech-debug/TenantManagementSystem/pull/1) |
| 4 Screens          | Lilian Kimweli | 182069        | (https://github.com/JustTheTech-debug/TenantManagementSystem/pull/3) |
| 5 Data integration | Sherly Mosoti  | 179567        | (https://github.com/JustTheTech-debug/TenantManagementSystem/pull/4) |
| 6 Release          | George Njogu   | 189937        |                                                                      |