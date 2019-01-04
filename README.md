# FirebaseTest
Learn Firebase

Firebase connection problem.
When i try to connect Realtime Database
  then it connect successfully but show a error maggege (Failed to resolve: firebase-database-15.0.0) ; 
  
 and then i try to fix it by rhis way
 implementation 'com.google.firebase:firebase-database:16.0.1:15.0.0'
 replace by
 implementation 'com.google.firebase:firebase-database:16.0.1'
 
 and then error massege is closed but problem is then autometicaly Realtime Database disconnected.
