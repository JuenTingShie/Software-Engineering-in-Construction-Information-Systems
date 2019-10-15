---
title: Hill ⛰️ Functions Points Analysis
tags: Documents
---
# Functions Analysis

[Function Points Tables](/9b9Jw1NFS9aE800en7HhKw)

| Function Points Analysis | |
| :--------------------: | :---------------------------: |
| **Transaction**       | **Files**                     |
| External Input(EI)     | External Interface Files(EIF) |
| External Output(EO)    | External Logic Files(ILF)     |
| External Inquiries(EQ) |                               |

<details open>
<summary>External Input(EI)</summary>

> An external input (EI) is an elementary process that processes data or control information that comes from outside the application boundary. The primary intent of an EI is to maintain one or more ILFs and/or to alter the behavior of the system. 
>> 外部輸入（EI）是處理來自應用程序邊界之外的數據或控制信息的基本過程。 EI的主要目的是維護一個或多個ILF和/或更改系統的行為。

</details>

<details>
<summary>External Output(EO)</summary>

> An external output (EO) is an elementary process that sends data or control information outside the application boundary. The primary intent of an external output is to present information to a user through processing logic other than, or in addition to, the retrieval of data or control information . The processing logic must contain at least one mathematical formula or calculation, create derived data maintain one or more ILFs or alter the behavior of the system. 
>> 外部輸出（EO）是在應用程序邊界之外發送數據或控制信息的基本過程。外部輸出的主要目的是通過除數據或控制信息的檢索之外或之外的處理邏輯，向用戶呈現信息。處理邏輯必須包含至少一個數學公式或計算，創建派生數據以維護一個或多個ILF或更改系統的行為。
</details>

<details>
<summary>External Inquiries(EQ)</summary>

> An external inquiry (EQ) is an elementary process that sends data or control information outside the application boundary. The primary intent of an external inquiry is to present information to a user through the retrieval of data or control information from an ILF of EIF. The processing logic contains no mathematical formulas or calculations, and creates no derived data. No ILF is maintained during the processing, nor is the behavior of the system altered.
>> 外部查詢（EQ）是一個基本過程，它在應用程序邊界之外發送數據或控制信息。外部查詢的主要目的是通過從EIF的ILF檢索數據或控制信息向用戶呈現信息。處理邏輯不包含數學公式或計算，也不創建任何派生數據。在處理期間不維護ILF，也不會更改系統的行為。
</details>

<details>
<summary>External Interface Files(EIF)</summary>

> An external interface file (EIF) is a user identifiable group of logically related data or control information referenced by the application, but maintained within the boundary of another application. The primary intent of an EIF is to hold data referenced through one or more elementary processes within the boundary of the application counted. This means an EIF counted for an application must be in an ILF in another application.
> >外部接口文件（EIF）是用戶可識別的一組邏輯相關數據或應用程序引用的控制信息，但保持在另一個應用程序的邊界內。 EIF的主要目的是將通過一個或多個基本過程引用的數據保存在所計數的應用程序範圍內。這意味著為一個應用計算的EIF必須在另一個應用的ILF中。
</details>

<details>
<summary>Internal Logic Files(ILF)</summary>

> An ILF is a user-identifiable group of logically related data or control information maintained within the boundary of the application. The primary intent of an ILF is to hold data maintained through one or more elementary processes of the application being counted.
> >ILF是在應用程序範圍內維護的用戶可識別的邏輯相關數據或控制信息組。 ILF的主要目的是保存通過計數的應用程序的一個或多個基本過程維護的數據。
</details>

## 3-tier Web Application
### Buyer
  - [x]Search
    - Search bar
    - Choose tags
    - Choose category
    - Choose price range
  - [ ]Product Details
    - Click read more
  - [ ]Contact
    - Chat with other  users
    - Check sellers profile
  - [ ]Compare
    - Add to compare
    - Remove from compare
  - [ ]Cart
    - Add to cart
    - Remove from cart
  - [x]Payment
    - Choose type of trading
    - Choose payment method
    - Choose delivery method
    - Confirm payment button
    - Print receipt
    - Save receipt
    - Check delivery status
    - Confirm product acceptance
    - Check transactions history
  - [ ]Comment / Score
    - Comment and score the seller
    - Comment and score to this trad(about website experience)
  - [ ]Report bug / Other users
  - [ ]Get Help Button
  - [ ]Forum
    - Make a new thread in forum
    - Comment on the thread 
  - [ ]Editing profile
  - [ ]Login
    - Input user ID and password
    - Making account (fill registration form)

  
### Seller
   
  - [x]Upload stuff
    - Upload photo/videos of product
    - Adding description of product
    - Adding tags
    - Adding categories
    - Adding price range
    
  - [ ]Contact
    - Chat with other users
    - Check buyers profile
    
  - [ ]Transactions
    - Confirm Delivery Process
    - Check transaction history
    - Check product acceptence status
    - Check payment status
    
  - [ ]Comment / Score
    - Comment and score the seller
    - Comment and score to this trad(about website experience)
  - [ ]Report bug / other users
  - [ ]Get Help Button
  - [ ]Forum
    - Make a new thread in forum
    - Comment on the thread 
  - [ ]Editing profile
  - [ ]Login
    - Input user ID and password
    - Making account (fill registration form)

### Application

  - [ ]Display products thumbnail
  - [ ]Display product details
  - [ ]Display price trend
  - [ ]Display trending and best seller products
  - [ ]Display buyers/sellers profile
  - [ ]Display help/tutorial/QnA page
  - [ ]Display payment method
  - [ ]Display delivery method
  - [ ]Display transaction method
  - [ ]Display transaction details
  - [ ]Display transaction history
  - [ ]Display payment status
  - [ ]Display delivery status
  - [ ]Display product acceptence status
  - [ ]Process and record registration form
  - [ ]Display login page
  - [ ]Process login input
  - [ ]Provide chat box between users
  - [ ]Send delivery notice to buyers
  - [ ]Send product acceptence notice to sellers
  - [ ]Send payment notice to sellers
  - [ ]Display threads in forum

---

## 2-tier Desktop Application
  - [ ]Search bar
  - [ ]Choose category
  - [ ]Choose tags
  - [ ]Choose price range
  - [ ]Display products thumbnail
  - [ ]Display product details
  - [ ]Display price trend
  - [ ]Input the callers information (name,contact,etc)
  - [ ]Input the sellers' product information
  - [ ]Display payment status
  - [ ]Display delivery status
  - [ ]Display product acceptence status
  - [ ]Display Login page
  - [ ]Process login input