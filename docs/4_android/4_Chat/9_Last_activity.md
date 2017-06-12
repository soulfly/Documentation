===Last activity===

It is often helpful to know the time of the last activity for user whether he is in your contact list or no. You can use methods below to discover when a disconnected user last accessed its server.

```java
QBUser targetUser = ...;
try {
    long lastUserActivity = QBChatService.getInstance().getLastUserActivity(targetUser.getId()); //returns last activity in seconds or 0 if user online or error (e.g. user never loggedin chat)
} catch (XMPPException.XMPPErrorException | SmackException.NotConnectedException e) {
     //handle error
}
```