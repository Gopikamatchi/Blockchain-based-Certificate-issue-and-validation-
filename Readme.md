                          CERTIFICATE ISSUING AND VERIFICATION USING BLOCKCHAIN 
#INTRODUCTION
The Blockchain is the backbone Technology of CryptoCurrency such as BitCoin. The blockchain is an immutable distributed database 
of records of all transactions or digital event that have been executed
and shared among participating parties. 
The smart contracts are self-executing contracts when predefined conditions met which change their state.
IPFS a protocol and network with content-based addressing allows us to store and share files in a distributed manner.

#ABSTRACT 
A Certificate is a report that guarantees that an individual has gotten explicit training or has breezed through 
a test or arrangement of tests. 
Counterfeit testaments is a gigantic issue in our Nation. Even a unique paper testament can be forged easily. 
Verification check is a tiresome and time-consuming process for Organizations/Institutions. 
We propose a Blockchain(Distributed Ledger Technology) based solution for this problem with Distributed storage(IPFS).
Thus certificates will be tamperproof, confidential and secure. Hash of the certificate is stored in the blockchain.
the certificate is encrypted with recipient public key, store it in IPFS and send the hash to the recipient.

#PROBLEM STATEMENT
Storing the institute and organization certificates is a recurring process. For the Organization, 
verifying the authenticity of the certificates is tedious and cumbersome.
The hard copy of the certificate can get damage or loss and it takes a lot of time to validate 
or check the authentication of the certificate.
If a person lost his/her certificate then reissuing of the certificate take some time and a long process
.Even though some platform issue digital certificates there are certain problems associated like hosting server, 
single point failure, etc.,

#MODULES 
1   RECIPIENT MODULE
2   ISSUER MODULE 
3   VALIDATOR MODULE

RECIPIENT MODULE
    Recipient module which is used by the recipient in order to see all the certificates they received as a transaction 
    from the different Issuers.
    All the available certificate hashes will be displayed once he logged into the Metamask.
    All these hashes are calculated after the certificate are encrypted with the user public key. The IPFS was content 
    based searching method.

ISSUER MODULE 
    In Issuer module issuer can able to issue the certificate that he wants to a receiver he needs to specify the recipient 
    public key and address. 
    First hash of certificate is generated and stored in the blockchain. 
    Then the certificate will be encrypted with recipient public key and added to the IPFS and this IPFS hash will be received
    by the Recipient
VALIDATOR MODULE
    Verification module in which the Verifier (the person who wants to verify certificate) can able to upload
    the certificate they received from the recipients.Then they can able to verify the certificate by calculating the hash of the 
    certificate 
    and checking the certificate authentication in the blockchain. 
    The verification process only takes seconds to verify the certificate. Verifier need not to login in order to verify the 
    Certificates.
    
    Project status
    
          Recipient module (80% completed)
          Issuer module (80% completed)
          Validator module (90%completed)
          Crypto Module (80% completed)
          IPFS Module (working successfully)
    Pending works
            Validator module (connecting to blockchain)
            User interface 
            

