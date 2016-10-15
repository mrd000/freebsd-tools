# freebsd-tools
Different things for FreeBSD

## gptid-to-dev
Converts gpt ID or /dev/gptid/<id> to device name of the partition

Usage: `gptid-to-device <gptid>`

Examples:

```# gptid-to-device e5d96c20-2f6d-11e5-9aed-003048806658
da0p1```

```#gptid-to-device gptid/e5d96c20-2f6d-11e5-9aed-003048806658
da1p1```
