# SocialSecurityNumberEncryptionConcept

This module shows how best to encrypt and secure select PII data. In the US certain data pieces have to be encrypted and secured from usage by unauthorized users. This module demonstrates a working example on how best to secure an American Social Security Number. 

The functionality in this module is compatible with legislation of all US States, but compliance will depend on how this logic is implemented. Please review the individual policies of all states applicable for your application.


The primary purpose of this module is as a demonstration on how to develop this, however the implementation is solid and secure. You can choose to move all logic from this module into your own project. This module will be upgraded along with later platform releases to adopt the latest features, but it's not likely that this module will be extended with many more features.

# Functionality:
The module has an example Person_Edit page that shows the use of the snippet. 
The snippet contains all logic to show the Social Security Number field twice, as soon as the user completes the field the SSN is encrypted and hidden from view.

The encrypted SSN is never shared with the user, unless the Decryption microflow is executed. When the SSN is decrypted this action is logged to trace access to the SSN field. 

# Applying this in your own project
When storing PII such as a SSN in your project it is necessary to incorporate all the demonstrated logic in the application in order to have a fully secure and compliant solution. 
