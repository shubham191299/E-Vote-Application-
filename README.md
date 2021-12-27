# E-Vote-Application-

## Problem Statement.

In India, elections are conducted using EVM's (Electronic Voting Machine), which emerged in the preceding two decades by government-owned companies associations [4]. EVMs commit towards the more agile counting, vote fitting and distribution of votes on the results despite that the EVM machine receives input information from citizens or voters and generates results in a manner that external spectators and election officials cannot testify or witness[5]. Consequently, the EVM is lacking in transparency and integrity.
The Council of Europe's handbook on e-voting states, "It has become clear that e‑voting systems cannot be introduced unless citizens and other stakeholders trust their political and administrative systems" [5]. The population requires a transparent and honest voting system to restore their rights to choose and elect the leader of their preference. The existing EVM has several allegations. There is a necessity to consider the issues and demands of Provable studies, which reduce malpractices [6] as hacking has taken over the ability to hold a clear and transparent election.


## Methodology 

A fair E-voting web app is created in which the voters can register themselves using their name, state and aadhaar card number, and get an exclusive voterId which is used to login to the app, and cast the vote. The system uses blockchain and cloud technology for authentication and to make the voting system transparent and integrated.

## Voting Procedure

Initially, the user registers to cast a vote by providing their Name, State and Aadhaar card number. In this step, we authenticate the user with the help of a PHP file by checking these details in the database situated on the AWS. If the entries are valid and have not been registered yet, only then the voterID is displayed.
Subsequently, we use the voterID to present our vote, through which the application tests if the voter's voterID has voted already and confers if the user has earlier cast a vote. The political party the voter has chosen is given a vote, a new block node is added to the blockchain, and the hash code of that block is stored in the database. Since every vote or transaction has a signature from a right pair, we can follow back any transaction to any voter of the application in the state of an inspection.

![image](https://user-images.githubusercontent.com/52815570/147461970-4a298e62-85b6-4a3c-b92d-ac28d58cffef.png)

The above image shows the flow of the web application in the registration phase: voters get the voterID to vote only if the user is found authenticated, and after voting securely a new block is created, and hash code is stored in the database on the AWS.
