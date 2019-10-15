# Meeting of Software Engineering in Construction Information Systems
---
> [TOC]
---

## Meeting 4 -2019/10/16

### Before meeting:
Topic:
- Means of specify Nouns:
  - https://alvinalexander.com/FunctionPoints/node11.shtml

| Function Points Analysis | |
| ---------------------- | ----------------------------- |
| **Transaction**       | **Files**                     |
| External Input(EI)     | External Interface Files(EIF) |
| External Output(EO)    | External Logic Files(ILF)     |
| External Inquiries(EQ) |                               |

- External Input(EI)
> An external input (EI) is an elementary process that processes data or control information that comes from outside the application boundary. The primary intent of an EI is to maintain one or more ILFs and/or to alter the behavior of the system. 
>> 外部輸入（EI）是處理來自應用程序邊界之外的數據或控制信息的基本過程。 EI的主要目的是維護一個或多個ILF和/或更改系統的行為。

- External Output(EO)
> An external output (EO) is an elementary process that sends data or control information outside the application boundary. The primary intent of an external output is to present information to a user through processing logic other than, or in addition to, the retrieval of data or control information . The processing logic must contain at least one mathematical formula or calculation, create derived data maintain one or more ILFs or alter the behavior of the system. 
>> 外部輸出（EO）是在應用程序邊界之外發送數據或控制信息的基本過程。外部輸出的主要目的是通過除數據或控制信息的檢索之外或之外的處理邏輯，向用戶呈現信息。處理邏輯必須包含至少一個數學公式或計算，創建派生數據以維護一個或多個ILF或更改系統的行為。

- External Inquiries(EQ)
> An external inquiry (EQ) is an elementary process that sends data or control information outside the application boundary. The primary intent of an external inquiry is to present information to a user through the retrieval of data or control information from an ILF of EIF. The processing logic contains no mathematical formulas or calculations, and creates no derived data. No ILF is maintained during the processing, nor is the behavior of the system altered.
>> 外部查詢（EQ）是一個基本過程，它在應用程序邊界之外發送數據或控制信息。外部查詢的主要目的是通過從EIF的ILF檢索數據或控制信息向用戶呈現信息。處理邏輯不包含數學公式或計算，也不創建任何派生數據。在處理期間不維護ILF，也不會更改系統的行為。

- External Interface Files(EIF)
> An external interface file (EIF) is a user identifiable group of logically related data or control information referenced by the application, but maintained within the boundary of another application. The primary intent of an EIF is to hold data referenced through one or more elementary processes within the boundary of the application counted. This means an EIF counted for an application must be in an ILF in another application.
> >外部接口文件（EIF）是用戶可識別的一組邏輯相關數據或應用程序引用的控制信息，但保持在另一個應用程序的邊界內。 EIF的主要目的是將通過一個或多個基本過程引用的數據保存在所計數的應用程序範圍內。這意味著為一個應用計算的EIF必須在另一個應用的ILF中。

- External Logic Files(ILF)
> An ILF is a user-identifiable group of logically related data or control information maintained within the boundary of the application. The primary intent of an ILF is to hold data maintained through one or more elementary processes of the application being counted.
> >ILF是在應用程序範圍內維護的用戶可識別的邏輯相關數據或控制信息組。 ILF的主要目的是保存通過計數的應用程序的一個或多個基本過程維護的數據。


---

## Meeting 3 -2019/10/09

Topic:
- 1. Assignments#2 discuss
  - [ ] What means Function points and Function Points Analysis(FPA).
  - [ ] Try to lists all function of our website.

---

## Meeting 2 -2019/10/03

Topic:
- [x] 1. [Business Model](https://canvanizer.com/canvas/wP7YO1CISmRJS) (complete)
- [x] 2. [Proposal](https://hackmd.io/mPzG4JFiS1SXSFM0dzv8Jg) (complete)

### Sort out
- a. Philosophy
  > Our vision is to extend the life-cycle of used electronics. 
- b. Feature
  > "Price Trends", "Score", "Tag", "Compare", "Forum", "WebApp", "Consultation"
- c. Scope of Service
  > 2-tier desktop application and 3-tier web application
- d. Profit
  > "Selling service charge" and "Advertisement"

---

## Meeting 1 -2019/10/02

Topic:
- [ ] 1. [Business Model](https://canvanizer.com/canvas/wP7YO1CISmRJS) (almost)
- [ ] 2. [Proposal](https://hackmd.io/mPzG4JFiS1SXSFM0dzv8Jg) (15%)

Refrence:
> 1. https://www.bnext.com.tw/article/46023/business-model-you
> 2. https://www.slideshare.net/lrq20501/business-plan-1071220

### Discuss about Business Model:
- a. Revenue streams ?
    > By service charge and Advertisements.
    > Service charge will be taken from seller as a static charge. 

- b. Will price trend not suit on "Brand New stuff" ?
    > Price trend is just for refer, if the stuff is expensive because it's brand new, buyer will know that. 

- c. What "front end" we are going to use ?
    > We want a WebAPP that can fit all device. 

- d. Community?
    > At first, each board's administrator are our staff, for solving problem and post some NEWS about the board topic, if number of USER is grown enough, USERs can vote for their own administrator. 

- e. Filter?
    > For both buyer and seller, they can set filter about their customer by location. It's set for better experience of using.