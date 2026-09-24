# Security and support policy

The current release is a beta and has not yet completed a physical Karoo 2 ride test.

Report a suspected security or privacy problem privately through the repository owner's GitHub profile before opening a public issue. Do not include routes, account details, device serial numbers, or private ride logs in a public report.

The private Hammerhead Binder connection and Ki2 15.0 integration are experimental compatibility features. They may stop working after device or app updates. Ride Sounds does not request network access and does not modify Karoo or Ki2 settings.

The Android extension service is exported only because the Karoo host must discover and bind to extensions. The upstream extension contract does not provide a host-only permission that this app can safely require. The service publishes no custom data types, device scanning, map layer, FIT writer, or bonus actions, so its inherited binder entry points return no Ride Sounds data. Residual risk: another app installed on the same device can bind to and start the service; it cannot read the private settings or diagnostic files through that binder. This remains part of the beta risk until physical-device testing confirms that a stricter caller check would not break Karoo discovery.
