# websocket-echo-falcon

A simple WebSocket chat server using Ruby, `async-websocket`, and `falcon`. Note that because the example was for chat instead of echo, that was retained.

Also note that it's not compatible with `websocket-echo-*` clients because they send text but `async-websocket` requires messages to be JSON.

## Requirements

Ruby

## Installation

```bash
$ bin/setup
```

## Running

```bash
$ bin/serve
```

Access `ws://localhost:3000`

## Testing

```bash
$ npm install -g wscat
$ wscat -c ws://localhost:3000
```
