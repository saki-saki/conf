


```
#Mem:2g
-Xmx1g -Xms1g -XX:+UseG1GC -XX:MaxGCPauseMillis=200

#Mem:8g
-Xmx6g -Xms6g -XX:+UseG1GC -XX:MaxGCPauseMillis=200

```



>
    Do not Set Young Generation Size(-Xmn)
    G1 will no longer respect the pause time target for collections. So in essence, setting the young generation size disables the pause time goal.
    G1 is no longer able to expand and contract the young generation space as needed. Since the size is fixed, no changes can be made to the size.



[http://www.oracle.com/webfolder/technetwork/tutorials/obe/java/G1GettingStarted/index.html)](http://www.oracle.com/webfolder/technetwork/tutorials/obe/java/G1GettingStarted/index.html)

