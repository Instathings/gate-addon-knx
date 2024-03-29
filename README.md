# Gate addon for KNX protocol

This addon extends [Instathings Gate](https://github.com/Instathings/gate) for supporting KNX protocol.

### Get started

This addon is meant to be used inside the gate Docker container and will be installed automatically once the device pairing procedure is launched from the [Editor](https://editor.instathings.io).

### Events

This addon extends the EventEmitter class, you can listen to the following events: 

- `data`: emitted when a device sends information (e.g.: a temperature sensor sends new data)

### License
gate-addon-knx is [fair-code](http://faircode.io/) licensed under [Apache 2.0 with Commons Clause](./LICENSE.md)

