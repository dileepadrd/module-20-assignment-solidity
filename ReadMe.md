# Join Saving Smart Contract

# Introduction

This document describes the testing process and the steps in order to test the smart contract implemented to maintain join saving accounts. 

> The following accounts has been used for this contract testing. 
> Account 1: 0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb and Account 2: 0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0
## Compiling the code

The following screenshot shows the output of the Remix editor after the code has been compiled successfully.

!["compile"](./Execution_Results/00_compile.png)

## Deployment

The following images shows the screen of the after the deployment.

### Deployment success log message

!["deployment"](./Execution_Results/01_deployment.png)

### Deployment success screen

!["deployment"](./Execution_Results/02_deployment.png)

## Set Accounts

The following image shows the screenshot after set account function call.

!["set account"](./Execution_Results/03_set_accounts.png)

## Deposit

The following image shows the screen of deposit steps.

### 1 Ether deposit started.

!["deposit"](./Execution_Results/04_deposit_start.png)

### 1 Ether deposit completed successfully.

!["deposit"](./Execution_Results/05_deposit_completed.png)

### 10 Ether deposit started

!["deposit](./Execution_Results/06_10_either_deposit.png)

### 10 Ether deposit completed successfully

!["deposit](./Execution_Results/07_10_either_deposit_completed.png)

### 5 Ether deposit started

!["deposit](./Execution_Results/08_5_either_started.png)

### 5 Ether deposit completed

!["deposit](./Execution_Results/09_5_either_transaction_completed.png)

### 5 Ether withdraw completed

The following screenshot shows the screen after successfully withdraw 5 eithers to account1.

!["withdraw](./Execution_Results/10_5_ether_withdraw_completed.png)

### 10 Ether withdraw completed

The following image shows the screen after withdrawing 10 ethers to account 2 successfully.

!["withdraw"](./Execution_Results/11_10_ether_withdraw_successful.png)

## Converting ether to wei 

The following image shows how the ether to wei conversion has been achieved. 

!["converting"](./Execution_Results/converting_wei_to_ether.png)