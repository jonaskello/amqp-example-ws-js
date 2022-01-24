# rabbit-web

Trying to make rabbit work in the browser.

```bash
yarn # install deps
docker compose up -d
yarn start
```

Goto localhost:8080

The output in the Chrome console is:

```
WebSocket connection to 'ws://localhost:15670/' failed:
localhost/:1 Uncaught Event {isTrusted: true, type: 'error', target: WebSocket, currentTarget: WebSocket, eventPhase: 2, …}
error (async)
(anonymous) @ amqp-websocket-client.mjs:2017
connect @ amqp-websocket-client.mjs:2014
(anonymous) @ (index):12
```
