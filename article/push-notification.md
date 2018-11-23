# Push Notification
This article contains anything about push notification on iOS.

## Troubleshooting
### Client is not able to receive push notification
#### Check target environment
The provider server must send the push request to the correct target environment. Apple documentation states:
'''
 There is a separate persistent connection to the push service for each environment. The operating system establishes a persistent connection to the sandbox environment for development builds, while ad hoc and distribution builds connect to the production environment.

'''