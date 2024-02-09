# Card Release Note
| API                                                   | General Availability Release Date | Support End Date | Version        | Release Notes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|-------------------------------------------------------|-----------------------------------|------------------|----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Card v2.8.0                                           | November 2023                     | TBD              | Version 2.8.0  | Enhanced functionality for the following [Card API]() features:  <br> * Transaction Search  <br> * PAN Tokenization (Non-Transaction Token - NTT) expansion support for all endpoints Updated with a new version of the Lifecycle key field. <br> * Add  <br> * Optimization of request/response payload to support 'Card gen indicator, TPS flag and nonTransTokenFlag' . <br>Enabled to search with NTT.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Card v2.6.0                                           | October 2023                      | TBD              | Version 2.6.0  | Enhanced functionality for the following [Card API]() features:  <br> * Limits <br> * **PAN Tokenization** (Non-Transaction Token - NTT) expansion support for all endpoints                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Card v2.5.0                                           | August 2023                       | TBD              | Version 2.5.0  | Enhanced functionality for the following [Card API]() features: *New* Add endpoint to support  <br> * NTT: search of non-transaction token for an existing card number <br> * Details  <br> * Support of the following endpoints:  <br> * **Additional Info Search:** retrieve additional information of a cardholder. <br> * **Additional Info:** update the additional information of a cardholder. <br> * **ATM Preferences Search:** retrieve ATM preferences for a cardholder. Applies to debit card program. <br> * **ATM Preferences:** update ATM preferences for a cardholder. Applies to debit card program. <br> * PIN  <br> * Support of PAN Tokenization (Non-Transaction Token - NTT)  <br> * **Pin Offset:** Correction of documentation gap found of endpoint where PUT method corrected to POST                                                                                                                                                                                                                                                                     |
| Card v2.3.0                                           | May 2023                          | TBD              | Version 2.3.0  | Enhanced functionality for the following Card API features:  <br> * Demographics <br> * **PAN Tokenization** (Non-Transaction Token - NTT) expansion support for all endpoints <br> * Optimization of request/response payload for all endpoints support of new authentication field 'callerId' within demographics/search endpoint <br> * Details Optimization of response payload to support 'cardclass' identifier <br> * Related Accounts <br> * **PAN Tokenization** (Non-Transaction Token - NTT) expansion support <br> * Optimization of URL path for all endpoints <br> * **New** Replacement endpoint to support:  <br> * **Instant Issuance:** allows the institution to replace a plastic for an existing cardnumber without sending an order to the card producer                                                                                                                                                                                                                                                                                      |
| Card v2.2.0                                           | February Exception Install        | TBD              | Version 2.2.0  | Exception fix deployment to the following **Demographics** endpoints:  <br> * v1/cardholders/additionalInfo  <br> * Added memberNumber in the request payload <br> * Aligned the cardnumber example with sandbox Description update for all fields within:   <br> * 'UpdateAdditionalInfo' object <br> * 'UpdateNameDetails' array <br> * Example update for all fields within: <br> * 'UpdateAdditionalInfo' object <br> * 'UpdateNameDetails' array   <br> * /v1/cardholders/address  <br> * Added memberNumber in the request payload <br> * Aligned the cardnumber example with sandbox <br> * Updated the required fields for 'CardsAddress' array <br> * Description update for all fields within:   <br> * 'CardsAddress' array <br> * Example update for all fields within: <br> * 'CardsAddress' array   <br> * /v1/cardholders/search <br> * Change position of lastName in request field as lastName is one of primary search field Format and example update for dateOfBirth in request & response payload   <br> * /v2/cardholders/search  <br> * Format and example update for dateOfBirth in request & response payload |
| Card v2.1.0                                           | February 2023                     | TBD              | Version 2.1.0  | Enhanced functionality to support: <br> * Update Status feature allow clients to retrieve the status and reason codes for a debit card.   **PAN Tokenization:** Our PAN Token service replaces the use of actual card numbers with a token referred to as a Non-Transaction Token. Support is now available for use in the following features:  <br> * Activation <br> * Add Orders <br> * Replacement <br> * Details <br> * Update Status                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Card v1.10.0                                          | November 2022                     | TBD              | Version 1.10.0 | Enhanced functionality to support:  <br> * Audit allows users to retrieve the audit details of a given debit card enabling investigation of cardholder data and provides six months of cardholder audit history. <br> * Limits includes a new function which allows FIs to set card limits with expiry dates, after which they revert to the original limits.   <br> * Related Accounts allows clients to retrieve and maintain account details of a given debit card.  <br> * Orders allows retrieval of card order history as well as allows cardholders to update or cancel an pending card order.                                                                                                                                                                                                                                                                                                                                                                                                              |
| Card v1.9.0                                           | October 2022                      | TBD              | Version 1.9.0  | Enhanced functionality to support the following:  <br> * Demographics - Support of TCPA contact address                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Card v1.8.0                                           | August 2022                       | TBD              | Version 1.8.0  | Enhanced functionality to support:  <br> * Add feature allows Financial Institutions to add a new card record modeled on an existing card number, account number or FI defaults (logo, prefix, card class). <br> * Transaction Search retrieve card transactions history by search criteria of retrieval reference number (RRN) or sequence number.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Card v1.7.0                                           | July 2022                         | TBD              | Version 1.7.0  | Enhanced functionality to support following features:  <br> * Replacement - URL path update. <br> * Demographics - ability to update ATM preferences for a cardholder.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Card v1.6.0                                           | May 2022                          | TBD              | Version 1.6.0  | Enhanced functionality to support following feature:  <br> * Demographics - Search or set demographic information about cardholders. <br> * Transaction Terminal Search - Retrieve specific transaction information for a specified terminal. Applicable to debit card only program.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Card v1.5.2                                           | April 2022                        | TBD              | Version 1.5.2  | Enhanced functionality to support following feature:  <br> * Transaction - retrieve recent card transactions history as well as allow cardholders to search for multiple transactions by specific search criteria, multiple dates and multiple merchant.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Card v1.4.2                                           | February 2022                     | TBD              | Version 1.4.2  | Enhanced functionality to support following features:  <br> * Replacement - ability tp place a new card order with existing card number. Applicable to debit and credit card programs. Pin Offset - Applicable to debit card only program.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Card v1.3.0                                           | January 2022                      | TBD              | Version 1.3.0  | Enhanced functionality to support following features:  <br> * Limits - ability to maintain the daily online and offline limits that are applied to ATM and POS transactions for the selected cardholder <br> * Update to include resource header fields                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Card v1.2.0                                           | November 2021                     | TBD              | Version 1.2.0  | The **Card API** provides the ability to manage a card, digitally display card details, activate cards online through various channels and search for basic cardholder information using details other than a card number on the following platforms.<br>   * Debit Enhanced EPOC<br>  * Credit Gateway<br>  * Credit Select                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Controls and Alerts v1.0.3                            | June 2021                         | -                | Version 1.0.3  | **This API has been deprecated.**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Debit Processing: Add Cardholder v1.0.3               | October 2021                      | -                | Version 1.0.3  | **This API has been deprecated.** See Card [Add]() feature                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Debit Processing: Retrieve Card Details v1.0.2        | August 2021                       | -                | Version 1.0.2  | **This API has been deprecated.** See Card [Details]() feature                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Debit Processing: Query Cardholder Transaction v1.0.3 | September 2021                    | -                | Version 1.0.3  | **This API has been deprecated.** See Card [Transaction]() feature: responseSubCode responseSubCodeDescription                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Debit Processing: Query Cardholder Transaction v1.0.2 | October 2021                      | -                | Version 1.0.2  | **This API has been deprecated.** See Card [Transaction]() feature                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |