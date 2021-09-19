<!-- Reddis CLI kholne ka hoga to bas simple wsl mein reddis-cli kholne ka -->
How to make a silly chat app in redis:

Take a chill pill.

STEP 1: OPEN 2 wsls

2: type in redis-cli to check if it is working
 3. go to upstash to make a redis cli sasta waala : https://console.upstash.com/pages/

 4. create a redis database and connect both the sides

 5. copy the command which is given in the upstash website, it'll look like : 
  ```

redis-cli -u <upstash link>
    
  ```
  
  6. Then simply write: 
  SUBSCRIBE devnest 

  7.Then write to chat:
  PUBLISH devsnest message