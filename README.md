# smart-contract-on-basic-lending-protocol
•	Users are required to keep at least 50% of the loan balance in their deposit balance as security. This guarantees that the procedure reduces the possibility of delinquent loans.

•	By keeping track of each user's active loans, the protocol guards against misuse of flash loans and guarantees appropriate repayment prior to taking out additional loans.

•	Reentrancy attacks are less likely because ether transfers are handled after state updates.

•	In order to prevent users from removing money at will, borrowing is limited to the protocol's available liquidity.


•	Actions related to deposits, loans, and repayments are recorded, which promotes openness and makes audits simpler. 

