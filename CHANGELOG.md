## [1.2.0] - 25/Sep/2020

- Supporting Apple sign in.

## [1.1.2] - 13/Aug/2020

- Removed codes that uses existing token for Kakao login.

## [1.1.1] - 12/Aug/2020

- Reverted retrieveToken() function to private. We can use AccessTokenStore.instance.fromStore() to fetch access token after logged in.

## [1.1.0] - 12/Aug/2020

- Made retrieveToken() function public so that we can use it for other Kakao APIs.

## [1.0.0] - 11/Aug/2020

- Switched Kakao SDK to the official package.

## [0.6.4] - 29/Jul/2020

- Added exception code on missing email for facebook auth.

## [0.6.3] - 29/Jul/2020

- Fixed typo of Kakao exception code.

## [0.6.2] - 20/Jul/2020

- Updated fierbase pacakge versions.

## [0.6.1] - 21/Apr/2020

- Updated getUserClaim() function to check null on user data.

## [0.6.0] - 20/Apr/2020

- Added unlink feature.

## [0.5.0] - 15/Apr/2020

- Fixed 'com.google.firebase.messaging.FirebaseMessagingService is inaccessible' erorr by updating firebase_auth package version.

## [0.4.4] - 2/Feb/2020

- Bug Fix.

## [0.4.3] - 1/Feb/2020

- Update document

## [0.4.2] - 30/Jan/2020

- Added information about app crash regarding Facebook package issue

## [0.4.1] - 30/Jan/2020

- Added example screenshots

## [0.4.0] - 29/Jan/2020

- Added Phone authentication
- Added Phone authentication example
- Added assertion for sign-in logic

## [0.3.3] - 29/Jan/2020

- Fixed bug that Kakao sign-in links automatically with existing e-mail. It will throw an error and only can be linked by using link function.
- Kakao sign-in will throw a new exception in regards to above issue.
- Added try-catch block for email authentication. It will now catch error correctly.
- Fixed bug at example code. It will now trim the white space before sending to the server.
- Fixed bug at example code. Sign-in/out dialog will be disappear as expected when sign-in/out is succeeded.

## [0.3.2] - 29/Jan/2020

- Minor bug fix

## [0.3.1] - 29/Jan/2020

- Added getUserClaim function so that we can get claim data from provider
- Changed logic of signing-out from 3rd party providers

## [0.3.0] - 28/Jan/2020

- Updated cloud function for verifiying/creating Kakao token
- Changed logic of Kakao sign in
- Refactoring Kakao sign in
- Refactoring other sign ins
- Added linking function
- Made email and password as a required field

## [0.2.0] - 27/Jan/2020

- Supporting Facebook sign in

## [0.1.0] - 27/Jan/2020

- Supporting Kakao sign in

## [0.0.1] - 25/Jan/2020

- Initial release with Firebase email and Gmail support
