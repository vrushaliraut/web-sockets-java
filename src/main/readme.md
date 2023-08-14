# Websockets playaround 

# For testing - Main Branch 
- start the server 
- for client 
  - use chrome browser 
  - click on more tool -> developer tool 
  - let ws = new WebSocket("ws://localhost:8080/user") 


# For testing - Redis Branch
``` let ws = new WebSocket('ws://localhost:8080/user/channelId');
    ws.onmessage = message => {
    console.log(message.data);
    }
    ws.send("reciverId->Hi");
   ```

#Reference - https://www.youtube.com/watch?v=sj9kJdFAVDY&list=PL1F54YqZCTdwN_IczVEHrAIDRo-nUNwzA&index=3 