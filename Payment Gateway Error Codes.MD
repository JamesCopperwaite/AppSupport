| Error Code	| Description	| Approved	| Explanation |
| :---: | --- | :---: | --- |
| 00	Transaction Approved	| Yes		| The transaction was successful |
| 01	Refer to Issuer	| No	| Card Number	The customer’s bank (Card Issuer) has indicated there is a problem with the credit card number. The customer should contact their bank. The customer should use an alternate credit card. |
| 02	Refer to Issuer, special	| No	| Card Number	The customer’s bank (Card Issuer) has indicated there is a problem with the credit card number. The customer should contact their bank. The customer should use an alternate credit card. |
| 03	No Merchant	| No	| Business ID	The Merchant ID is invalid, you should contact your Bank and ensure you have provided the correct Merchant Account Number to PayChoice |
| 04	Pick Up Card	| No	| Suspect	The customer’s bank (Card Issuer) has declined the transaction and requested that your customer’s credit card be retained. (card reported lost or stolen). The customer should use an alternate credit card. |
| 05	Do Not Honour	| No	| Blocked	The customer’s bank has declined the transaction as the credit card number has failed a security check, or the funds have been frozen or depleted. The customer should use an alternate credit card. |
| 06	Error	| No	| Card Number	The customer’s bank (Card Issuer) has declined the transaction as there is a problem with the credit card number. The customer should contact their bank. The customer should use an alternate credit card. |
| 07	Pick Up Card, Special	| No	| Suspect	The customer’s bank (Card Issuer) has declined the transaction and requested that your customer’s credit card be retained. (card reported lost or stolen) The customer should use an alternate credit card. |
| 08	Honour With Identification	| Yes		| The transaction was successful |
| 09	Request In Progress	| No	| Card Number	The customer’s bank (Card Issuer) has indicated there is a problem with the credit card number. The customer should contact their bank. The customer should use an alternate credit card. |
| 10	Approved For Partial Amount	| Yes		| The transaction was successful |
| 11	Approved, VIP	| Yes		| The transaction was successful |
| 12	Invalid Transaction	| No| 	Data	The customer’s bank (Card Issuer) has declined the transaction because of an invalid format or field. Check the transaction information and try processing the transaction again. |
| 13	Invalid Amount	| No	Data	An invalid character (e.g. a dollar sign or a space) may be being passed to the gateway. Check your website’s code. |
| 14	Invalid Card Number	| No	| Card Number	The customer’s bank (Card Issuer) has declined the transaction as the Credit Card number does not exist. Check the credit card information and try processing the transaction again. |
| 15	No Issuer	| Yes		| The customer’s bank (Card Issuer) does not exist. Check the credit card information and try processing the transaction again. |
| 16	Approved, Update Track 3	| No	| 	The transaction was successful |
| 19	Re-enter Last Transaction	| No	| Connection fail	The transaction has not been processed and the customer should attempt to process the transaction again. |
| 21	No Action Taken	| No	| Card Number	The customer’s bank (Card Issuer) has indicated there is a problem with the credit card number. The customer should contact their bank. The customer should use an alternate credit card. |
| 22	Suspected Malfunction	| No| 	Connection fail	The customer’s bank (Card Issuer) cannot be contacted during the transaction. The customer should check the credit card information and try processing the transaction again. |
| 23	Unacceptable Transaction Fee	| No	| Unknown	An unspecified error has occurred. |
| 25	Unable to Locate Record On File	| No	| Card Number	The customer’s bank (Card Issuer) does not recognise the credit card details. The customer should check the credit card information and try processing the transaction again. |
| 30	Format Error	| No	| 	The customer’s bank (Card Issuer) does not recognise the transaction details. The customer should check the transaction information and try processing the transaction again. |
| 31	| Bank Not Supported By Switch	| No	| 	The customer’s bank (Card Issuer) has declined the transaction as it does not allow transactions originating through mail / telephone, fax, email or Internet orders. This error is associated customers attempting to use a Discover Card. The customer should use an alternate credit card. |
| 33	| Expired Card, Capture	| No	| 	The customer’s bank (Card Issuer) has declined the transaction as Credit Card has expired or the date is incorrect. Check the expiry date in the transaction and try processing the transaction again. |
| 34	| Suspected Fraud, Retain Card	| No		| The customer’s bank (Card Issuer) has declined the transaction as there is a suspected fraud on this Credit Card number. |
| 35	| Card Acceptor, Contact Acquirer, Retain Card	No		The customer’s bank (Card Issuer) has declined the transaction and requested that the customer’s credit card be retained (card reported lost or stolen). The customer should use an alternate credit card. |
| 36	| Restricted Card, Retain Card	| No		| The customer’s bank (Card Issuer) has declined the transaction and requested that the customer’s credit card be retained. (card reported lost or stolen) The customer should use an alternate credit card. |
| 37	| | Contact Acquirer Security Department, Retain Card	| No		| The customer’s bank (Card Issuer) has declined the transaction and requested that your customer’s credit card be retained. (card reported lost or stolen) The customer should use an alternate credit card. |
| 38	| PIN Tries Exceeded, Capture	| No		| The customer’s bank (Card Issuer) has declined the transaction as the customer has entered the incorrect PIN three times. The customer’s bank (Card Issuer) has requested you retain the credit card. The customer should use an alternate credit card and contact their bank. |
| 39	| No Credit Account	| No		| The customer’s bank has declined the transaction as the Credit Card number used is not a credit account. The customer should use an alternate credit card. |
| 40	| Function Not Supported	| No		| The customer’s bank (Card Issuer) has declined the transaction as it does not allow this type of transaction. The customer should use an alternate credit card. |
| 41	| Lost Card	| No		| The customer’s bank (Card Issuer) has declined the transaction as the card has been reported lost. The customer should use an alternate credit card. |
| 42	| No Universal Account	| No		| The customer’s bank (Card Issuer) has declined the transaction as the account type selected is not valid for this credit card number. The customer should use an alternate credit card. |
| 43	| Stolen Card	| No		| The customer’s bank (Card Issuer) has declined the transaction as the card has been reported stolen. The customer should use an alternate credit card. |
| 44	| No Investment Account	| No		| The customer’s bank (Card Issuer) has declined the transaction as the account type selected is not valid for this credit card number. The customer should use an alternate credit card. |
| 51	| Insufficient Funds	| No		| The customer’s bank (Card Issuer) has declined the transaction as the credit card does not have sufficient funds. The customer should use an alternate credit card. |
| 52	| No Cheque Account| 	| No		| The customer’s bank (Card Issuer) has declined the transaction as the credit card number is associated to a cheque account that does not exist. The customer should use an alternate credit card. |
| 53	| No Savings Account	| No		| The customer’s bank (Card Issuer) has declined the transaction as the credit card number is associated to a savings account that does not exist. The customer should use an alternate credit card. |
| 54	| Expired Card	| No		| The customer’s bank (Card Issuer) has declined the transaction as the credit card appears to have expired. The customer should check the expiry date entered and try again, or use an alternate credit card. |
| 55	| Incorrect PIN	| No		| The customer’s bank (Card Issuer) has declined the transaction as the customer has entered an incorrect PIN. The customer should re-enter their PIN, otherwise use an alternate credit card. |
| 56	| No Card Record	| No		| The Customer’s bank has declined the transaction as the credit card number does not exist. The customer should use an alternate credit card. |
| 57	| Function Not Permitted to Cardholder	| No		| The Customer’s bank has declined the transaction as this credit card cannot be used for this type of transaction. The customer should use an alternate credit card. |
| 58	| Function Not Permitted to Terminal	| No	| 	The Customer’s bank has declined the transaction as this credit card cannot be used for this type of transaction. This may be associated with a test credit card number. The customer should use an alternate credit card. |
| 59	| Suspected Fraud	| No		| The customer’s bank has declined this transaction as the credit card appears to be fraudulent. |
| 60	| Acceptor Contact Acquirer	| No		| The customer’s bank (card issuer) has declined the transaction. The customer should contact their bank and retry the transaction. |
| 61	| Exceeds Withdrawal Limit	| No		| The customer’s bank has declined the transaction as it will exceed the customer’s card limit. The customer should use an alternate credit card. |
| 62	| Restricted Card	| No		| The customer’s bank has declined the transaction as the credit card has some restrictions. The customer should use an alternate credit card. |
| 63	| Security Violation	| No		| The customer’s bank has declined the transaction. The customer should use an alternate credit card. |
| 64	| Original Amount Incorrect	| No		| The customer’s bank has declined the transaction due to the amount attempting to be processed. The customer should check the transaction amount and try again. |
| 66	| Acceptor Contact Acquirer, Security	| No		| The customer’s bank has declined the transaction and request the Merchant to contact the bank. The customer should use an alternate credit card. |
| 67	| Capture Card	| No		| The customer’s bank has declined the transaction as the card is suspected to be counterfeit. The customer’s bank (Card Issuer) has requested that your customer’s credit card be retained. The customer should use an alternate credit card. |
| 75	| PIN Tries Exceeded	| No		| The customer’s bank has declined the transaction as the customer has entered the incorrect PIN more than three times. The customer should use an alternate credit card. |
| 82	| CVV Validation Error	| No		| The customer’s bank has declined the transaction as the CVV is incorrect. The customer should check the CVV details and try again. If not successful, the customer should use an alternate credit card. |
| 90	| Cutoff In Progress	| No		| The customer’s bank is temporarily not able to process this customer’s credit card. The customer should attempt to process this transaction again. |
| 91	| Card Issuer Unavailable	| No		| The customer’s bank is unable to be contacted to authorise the transaction. The customer should attempt to process this transaction again. |
| 92	| Unable To Route Transaction	| No | The customer’s bank cannot be found for routing. This response code is often returned when the customer is using a test credit card number. The customer should attempt to process this transaction again. |
| 93	| Cannot Complete, Violation Of The Law	| No | The customer’s bank has declined the transaction and request the customer to contact their bank. The customer should use an alternate credit card. |
| 94	| Duplicate Transaction	| No		| The customer’s bank has declined the transaction as this transaction appears to be a duplicate transmission. No action required. |
| 96	| System Error	| No		| The customer’s bank was not able to process the transaction. The customer should attempt to process this transaction again. |
