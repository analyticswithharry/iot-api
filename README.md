# IoT API Lab

Build device-to-cloud APIs for telemetry ingestion and command/control workflows.

## Core concepts

- Device identity and registration
- Telemetry ingestion design
- Command dispatch + acknowledgment
- Offline buffering and delayed sync
- Device key rotation and revocation

## Suggested Stack

- MQTT broker and optional HTTP gateway

## Learning Tasks

- Simulate telemetry stream from devices
- Add command dispatch endpoint
- Track command acknowledgment status
- Implement offline buffer replay behavior
- Add identity and key lifecycle handling

## Validation checklist

- [ ] Device auth is required for publish
- [ ] Telemetry schema is validated
- [ ] Command ack flow is recorded
- [ ] Offline replay works predictably
