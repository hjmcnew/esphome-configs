# ESPHome Uplift Desk Component

An [ESPHome](https://esphome.io) external component for controlling [Uplift Desk](https://www.upliftdesk.com/) standing desks via the RJ12 port on the control box. This is the same port used by the official [bluetooth adapter](https://www.upliftdesk.com/bluetooth-adapter-for-uplift-desk/).

## Quick Start

Add the following to your ESPHome configuration:

```yaml
external_components:
  - source: github://hjmcnew/esphome-configs@master
    components: [uplift_desk]
```

See the [full documentation](uplift_desk) for hardware wiring, supported commands, and configuration details.
