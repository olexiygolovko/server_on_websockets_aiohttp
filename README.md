Write a server on aiohttp that:

         Allows clients to connect via websockets to messages (news).
         It can receive new news using the POST/news method (assuming that this request is sent to us by another service) and send it to all connected clients.
         Allows you to periodically check the connection between the client and the server using queries that do not change anything.

Make a page that can display messages received from this service.

The project is available at - http://127.0.0.1:8081/news

