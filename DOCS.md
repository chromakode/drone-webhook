Use the Webhook plugin to notify services via Webhook when a build completes.
You will need to supply Drone with outgoing Webhook URLs.

The following parameters are used to configuration the notification:

* **urls** - json payloads are sent here

The following is a sample Webhook configuration in your .drone.yml file:

```yaml
notify:
  webhook:
    urls:
      - https://your.webhook/...
      - https://your.other.webhook/...
```
