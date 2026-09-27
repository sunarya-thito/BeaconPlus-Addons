# Contributing

Use the issue forms and remove secrets, IP addresses, and paid plugin JARs from
attachments. Addons must depend only on a published BeaconPlus API/addon SPI,
keep third-party calls isolated in their own module, include tests, and update
`catalog.json`. A not-yet-ready dependency must produce a waiting state rather
than partial registration.
