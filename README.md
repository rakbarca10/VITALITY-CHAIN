# VITALITY-Chain-BlockChain-Based-Health-Management-System presents
                                                     
                                                    SWASTHYA MITRA

The Project aims to utilize blockchain innovation to make a client centered electronic wellbeing 
record while keeping up a solitary genuine form of the client's information. This is a 
decentralized stage that empowers secure, quick and straightforward trade and utilization of 
clinical information. It will empower clients to give restrictive admittance to various human services specialists 
for example, specialists, emergency clinics, research centers, drug specialists and back up plans to cooperate as they see fit. 
Every collaboration with their clinical information is auditable, straightforward and secure, and will be 
recorded as an exchange on its dispersed record. During this cycle, the patient's security is ensured consistently. This project is based on the authorization based Hyperledger Fabric engineering which permits changing access levels; clients control who can see their records, the amount they see and for what period of time. By enabling clients, we can fabricate the eventual fate of social insurance together. This project will be a stage for other 
computerized wellbeing applications to create on; clients will have the option to finish paperwork for these applications also, administrations which are fueled by their wellbeing information and made sure about by shrewd agreements.
                   # VITALITY-Chain Solution
Swasthya mitra  ​: The Healthcare of Tomorrow

● Dual Blockchain: It is assembled utilizing a double blockchain structure. The first blockchain controls admittance to wellbeing records and is manufactured utilizing Hyperledger Fabric. 
The second blockchain is fueled by an ERC20 token on Ethereum and underlies all the applications and administrations for our foundation.
● The Hyperledger blockchain organize is consent based and expects clients to sign up to utilize it. Permissioning on the system is controlled utilizing Hyperledger demonstrating also, access control dialects. Hyperledger Fabric is a stage for conveyed record arrangements supported by a secluded design conveying high degrees of secrecy, versatility, adaptability and versatility.
Working of the Network
Participants Involved
1. Practitioner
a. Read/Write on permissioned EHRs
b. Request permission for other Practitioner/ Institutions to gain Read/Write
access
2. Patient
a. Read their EHR
b. Permission a Practitioner/Institution to Read/Write EHR or a portion of their
EHR
c. Revoke permission from Practitioners/Institutions
d. Permission next of kin/emergency contact to Read/Grant permission
e. Write certain attributes to EHR
i. Amount of tobacco consumed daily
ii. Alcohol consumed weekly
iii. Weekly exercise
f. Ability to integrate IoT data into EHR
Encryption Scheme 
To guarantee protection, wellbeing records are encoded utilizing symmetric key cryptography. The record will be scrambled and put away in an information store inside the fitting administrative locale. The symmetric key will be encoded with the open key of a 2048-piece RSA key pair. 
Exchanges 
Any associations with wellbeing records are recorded as exchanges on the system. To guarantee security, wellbeing records are encoded utilizing symmetric key cryptography. 
Exchanges are visible just to the members related with the exchange. Each patient and professional would have its own advantage which must be gotten to by the individual himself.
There would be 3 types of transactions:
1. Patient Granting Access
2. Patient Revoking Access
3. Practitioner Referring Patient
Patient Granting Access
● Patient A grants access to EHR to Practitioner A
● Practitioner A’s ID is added to Patient A’s authorised asset on the ledger
● Patient A’s ID is added to Practitioner A’s authorised asset on the ledger
● The Symmetric key for the EHR is decrypted with Patient A’s private key
● Symmetric key is then encrypted with Practitioner A’s public key
Patient Revoking Access
● Practitioner A’s ID is removed from Patient A’s authorised asset
● Patient A’s ID is removed from Practitioner A’s authorised asset
● Patient A’s private key is used to decrypt Symmetric key for EHR which is
used to decrypt the EHR
● The new Symmetric key of EHR is encrypted with Patient A’s public key and
the public keys of all the remaining IDs that have permission
Practitioner referring Patient
● Practitioner A updates the permissions to allow Practitioner B to access the
Patient’s EHR.
● Chaincode will check that Practitioner A has permission on the EHR.
● Practitioner A uses its private key to decrypt the EHR’s symmetric key
● Practitioner B’s public key is used to encrypt the Symmetric key
● Practitioner B’s ID is added to Patient A’s authorised asset
● Patient A’s ID is added to Practitioner B’s authorised asset

1. BENEFITS
1.1 Data Science : Using the health data of every person , we would provide healthcare
inferences to the government.Government can use it to design better health schemes
in effective manner. Area specific schemes
1.2 AI : Based on the data from Chhattisgarh and similar data from all over the world ,
we can predict any health complications in any area . It could help to prevent epidemic
breakout.
1.3 It could help government to prevent delays in the Treatment as it would have Real
time data from all over the state. I.e. thereby removing corruption and delays in
healthcare.
1.4 Send notifications for ongoing health problems in the area and also for vaccinations
of child.

2. BENEFITS FOR AN INDIVIDUAL/CITIZENS
2.1 The entire health history of a person would be stored which would be reflected in
the Person’s Digital Health Card.
2.2 Now no need to carry all previous prescriptions , any doctor can directly see the
health card of that person and recommend the solutions based on that and it would be
very effective
2.3 Person living in remote villages can directly call the health expert and get all expert
solutions based on his UID.
2.4 Appointment booking
2.5 All DBT related to healthcare would be directly transferred to that account.
2.6 Newly born babies would be enrolled in and their vaccination schedule could be
tracked and regular and timely notification for vaccines can be provided

3. BENEFITS FOR HOSPITALS/DOCTORS
3.1 Doctors would have all previous data of the concerned patient & it can help the
doctor to better predict the disease.
3.2 Hospital can better manage the medicine stock.

# A Better System
● User Control
  ○ In the current human services framework, patients have their wellbeing data spread over various frameworks, clinics, systems and conceivably nations. There are various divided records from a similar patient, held at various establishments all with their own depiction of the patient's wellbeing at the purpose of their communication with them, for example, blood tests, imaging and facility letters. The undertaking will sequentially mastermind these records and channel them into the particular classifications above to help information taking care of. Such a categorisation would make the records more available and reasonable for patients and it will likewise encourage scientists in looking for the 
data applicable to them

● Clinical Communication
  ○ Alongside expanded admittance to crisis data, The project permits clinicians to speak effortlessly. At the point when an approved medicinal services proficient updates a patient wellbeing record, the framework will refresh that record on the page . Any clinician with approved admittance to that record will see the update continuously. As wellbeing records are refreshed by means of Swasthya Mitra for every approved gathering, there is no requirement for persistent information to be physically moved from framework to framework. The project will be usable in any program on any PC. Subsequently, any specialist with a program and a web association will have the option to get to the clients' reports imparted to them. Issues as of now connected with interoperability are settled thusly and costs that are related with the transportation of notes right now embraced by junior clinicians or 
regulatory staff are eliminated.

**ALL CREDITS TO RESPECTIVE OWNERS IF INTENDED
