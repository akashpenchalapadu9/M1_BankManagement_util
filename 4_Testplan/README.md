# TEST PLAN:

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** |    
|-------------|--------------------------------------------------------------|------------|-------------|
|  HLR1       |Creation of new account| Name:abc  Account Number:123456789 Initia Deposit:1000|Congratulations... Your account has been created.|
|  HLR2       |Deposit Amount|1000 |Your current available bank balance is 2000|
|  HLR3       |withdraw Amount|3000| Sorry, You dont have enough money in your account| 
|  HHR4       |Entering Password| qqqrdfcf|Wrong Password|
|  HHR4       |Entering Password| ankitalnt|password match|

## Table no: Low level test plan

| **Test ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  LLR1       |If user enters wrong Account Number. | 000000000| Wrong account number...| Wrong account number...|Requirement based |
|  LLR2       |If wrong choice choosen| 7|Invalid choice|Exit|Scenario based    |

