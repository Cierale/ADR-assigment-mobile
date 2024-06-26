# Subject: Permissions
Status: Proposed
Context:
The app needs to access user’s location, send push notifications, and access user’s payment information.

Decision:
We request permission from the user to access location data, send notifications, and access payment information. We will only ask for the permission necessary for the app's functionality.
Consequences:
Requesting permission means that some users may refuse to grant some permissions, which could limit the functionality of the app for those users.
