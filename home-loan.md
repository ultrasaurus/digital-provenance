In order to refinance a loan, there is a complex network of actors who review multiple inputs to assess the creditworthiness of the investment.

**Actors**

1) Homeowner- Owns the home and is submitting a request for refinancing.
2) Bank- Organization which owns the loan
3) Loan processor Pete- 3rd party organization working on behalf of bank to assess if house meets code requirements to get loan

**Objects**
1) Loan application
2) House photos- Pete takes photos to validate that the house meet the criteria for the loan
3) Loan evaluation- qualitative commentary and photo evidence

**Flow**
Homeowner-->Loan Application-->Bank--> Loan Processor Pete-->Photos taken by Pete-->Loan application

**How do you know that the content in the photos is authentic?**
Example-- to pass the loan criteria need a carbon monoxide detector but homeowner doesn't have one. But Pete is incented to get the loans approved and finished so he pull a detector out of his pocket, plugs it in and takes a picture. 
Or he photoshops it? 

**If later we suspect fraud, how would we pinpoint that fraud?**

Most information about who is asserting what so that we can find where the
fraud happened?  Who might be responsible?

* Home owner "Wendall"
* Loan processor "Pete"


Pete is issued a credential that he is qualified to inspect the home.

When Pete inspects the home, he uses his credential to issue a claim.


What credentials do they need to perform the role?
What is the chain of events?

## Verifiable Credentials issues to humans / real-world entities

1. Bank asserts that Pete is authorized to take photos for the loan documents
   * issuer: bank
   * subject: Pete
   * holder: Pete's Photography Co. (could be Pete)
   * claim: 

Possible option: Bank provides Pete a digital camera >

## Transactions

2. Pete takes photo and generates a report
   1. Pete creates a report (which is a verifiable credential)
   * issuer: Pete
   * subject: <house or photo (could be two subjects)>
   * holder: Pete's Photography Co. (could be Pete)
   * claim: 

3. Pete provides the report to the bank. The bank can verify the report (VC)
to ensure that it was created by the entity that was authorized by the bank.

## Open questions

* ontology for the issuer/subject/holder fields need to be determined
* what happens in real world / real time?  what are the digital parallels?
* what are the implications of this?  does it reduce / increase trust in informal systems?




Outcome: there is a chain of verifiable credentials