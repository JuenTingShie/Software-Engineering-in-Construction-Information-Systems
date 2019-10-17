---
title: Hill ⛰️ Function Points Tables
tags: Documents
---
# Function Points Tables

|  EI(FTR) |     1-4     |    5-15     |     15~     |
| :------: | :--------:  | :--------:  | :--------:  |
|    ~2    |   Low(3)    |   Low(3)    | Average(4)  |
|     2    |   Low(3)    | Average(4)  |   High(6)   |
|     2~   | Average(4)  |   High(6)   |   High(6)   |

|  EO(FTR) |     1-5     |    6-19     |     19~     |
| :------: | :--------:  | :--------:  | :--------:  |
|    ~2    |   Low(4)    |   Low(4)    | Average(5)  |
|   2or3   |   Low(4)    | Average(5)  |   High(7)   |
|     3~   | Average(5)  |   High(7)   |   High(7)   |
  
|  EQ(FTR) |     1-5     |    6-19     |     19~     |
| :------: | :--------:  | :--------:  | :--------:  |
|    ~2    |   Low(3)    |   Low(3)    | Average(4)  |
|   2or3   |   Low(3)    | Average(4)  |   High(6)   |
|     3~   | Average(4)  |   High(6)   |   High(6)   |
  
| ILF(RET) |     1-19    |   20-50     |     51~     |
| :------: | :--------:  | :--------:  | :--------:  |
|     1    |   Low(7)    |   Low(7)    | Average(10) |
|    2~5   |   Low(7)    | Average(10) |   High(15)  |
|     6~   | Average(10) |   High(15)  |   High(15)  |

| EIF(RET) |     1-19    |   20-50     |     51~     |
| :------: | :--------:  | :--------:  | :--------:  |
|     1    |   Low(5)    |   Low(5)    | Average(7)  |
|    2~5   |   Low(5)    | Average(7)  |   High(10)  |
|     6~   | Average(7)  |   High(10)  |   High(10)  |



## 2-Tier Application with "Core Functions"

| Role  |  Process  | Type | DET | FTR | RET | Complexity | UFP | Priority |
| :---: | :-------: | :--: | :-: | :-: | :-: | :--------: | :-: | :------: |
| Application | Storing staff | ILF | 12 |  | 1 | Low | 7 | 1 |
| Admin | Add staff | EI | 13 | 1 |  | Low | 3 | 1 |
| Admin | Review staff | EQ | 13 | 1 |  | Low | 3 | 1 |
| Admin | Delete staff | EI | 13 | 1 |  | Low | 3 | 1 |
| Staff | Login | EQ | 4 | 1 |  | Low | 3 | 1 |
| Staff | Logout | EI | 1 | 1 |  | Low | 3 | 1 |
| Staff | Search | EQ | 27 | 2 |  | High | 6 | 1 |
|  |  |  |  |  |  |  |  |  |

## 2-Tier Application with "All Functions"

| Role |  Process  | Type | DET | FTR | RET | Complexity | UFP | Priority |
| :--: | :-------: | :--: | :-: | :-: | :-: | :--------: | :-: | :------: |
| Staff | Review item | EQ | 24 | 1 |  | Low | 3 | 2 |
| Staff | Delete item | EI | 24 | 2 |  | High | 6 | 2 |
| Staff | Review USER | EQ | 10 | 1 |  | Low | 3 | 2 |
| Staff | Delete USER | EI | 10 | 1 |  | Low | 3 | 2 |
| Application | Storing NEWS | EIF | 5 |  | 3 | Low | 3 | 3 |
| Staff | Add NEWS | EI | 6 | 1 |  | Low | 3 | 3 |
| Staff | Review NEWS | EQ | 6 | 1 |  | Low | 3 | 3 |
| Staff | Delete NEWS | EI | 6 | 1 |  | High | 6 | 3 |
|  |  |  |  |  |  |  |  |  |

## 3-Tier Application with "Core Functions"

| Role |  Process  | Type | DET | FTR | RET | Complexity | UFP | Priority |
| :--: | :-------: | :--: | :-: | :-: | :-: | :--------: | :-: | :------: |
| Application | Storing USER | ILF | 6 |  | 1 | Low | 7 | 1 |
| USER | Add USER | EI | 7 | 1 |  | Low | 3 | 1 |
| USER | Review USER | EQ | 7 | 1 |  | Low | 3 | 1 |
| USER | Delete USER | EI | 7 | 1 |  | Low | 3 | 1 |
| Application | Storing item | ILF | 23 |  | 1 | Low | 7 | 1 |
| USER | Add items | EI | 24 | 1 |  | Average | 4 | 1 |
| USER | Review item | EQ | 24 | 1 |  | Average | 4 | 1 |
| USER | Delete item | EI | 24 | 1 |  | Average | 4 | 1 |
|  |  |  |  |  |  |  |  |  |

## 3-Tier Application with "All Functions"

| Role |  Process  | Type | DET | FTR | RET | Complexity | UFP | Priority |
| :--: | :-------: | :--: | :-: | :-: | :-: | :--------: | :-: | :------: |
|  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |