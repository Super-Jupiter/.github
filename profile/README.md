# SuperJupiter

**Physical AI, connected hardware and software that brings operations together.**

We are a technology company based in Somerset West, South Africa. We primarily develop our own physical AI products, combining AI, software, connected hardware and sensors.

We also build custom solutions for businesses, connecting existing software, equipment, devices and sensors, and developing custom hardware, sensors and gateways where needed. Our web and mobile applications bring operations together, with staff and client portals tailored to different roles across sites and regions.

[Explore SuperJupiter](https://www.superjupiter.net/) · [LinkedIn](https://www.linkedin.com/company/superjupiter-tech/) · [Contact us](mailto:info@superjupiter.net)

## Open source for sensor and embedded projects

Our public libraries are small, reusable C++11 components for Arduino, ESP32 and host C++ applications. They cover measurement quality, time handling, signal processing, recording and device behaviour. The libraries are MIT licensed and can be used without a SuperJupiter account or cloud service.

> **Hardware validation pending across this portfolio.** Software tests and board compilation are separate from physical testing. Check each repository's validation record, supported builds and release notes before relying on it in your application. These previews do not establish sensor accuracy or safety certification.

### Start here

- **[SuperJupiter SensorQuality](https://github.com/Super-Jupiter/superjupiter-sensor-quality):** Flag suspicious readings while preserving raw measurements.
- **[SuperJupiter SampleWindow](https://github.com/Super-Jupiter/superjupiter-sample-window):** Keep timestamped observations with explicit gaps and overwrite reporting.
- **[SuperJupiter SensorReplay](https://github.com/Super-Jupiter/superjupiter-sensor-replay):** Replay synthetic measurements and faults without sensor hardware. Its optional [PortfolioPipeline example](https://github.com/Super-Jupiter/superjupiter-sensor-replay/tree/main/extras/PortfolioPipeline) demonstrates all twenty components together using synthetic data and RAM storage.

### Measurement quality and time

| Library | Purpose |
| --- | --- |
| [SuperJupiter SensorQuality](https://github.com/Super-Jupiter/superjupiter-sensor-quality) | Reading quality, sample gaps and staleness flags. |
| [SuperJupiter SampleWindow](https://github.com/Super-Jupiter/superjupiter-sample-window) | Bounded timestamped sample windows and finite statistics. |
| [SuperJupiter Calibration](https://github.com/Super-Jupiter/superjupiter-calibration) | Piecewise-linear calibration with explicit bounds and provenance. |
| [SuperJupiter TimeAnchor](https://github.com/Super-Jupiter/superjupiter-time-anchor) | Device-to-UTC mapping with uncertainty and expiry. |
| [SuperJupiter ChannelAlign](https://github.com/Super-Jupiter/superjupiter-channel-align) | Bounded interpolation and stale-value handling across channels. |
| [SuperJupiter SensorAgreement](https://github.com/Super-Jupiter/superjupiter-sensor-agreement) | Age-aware comparisons between redundant sensors. |

### Signals, summaries and events

| Library | Purpose |
| --- | --- |
| [SuperJupiter SignalFilter](https://github.com/Super-Jupiter/superjupiter-signal-filter) | Elapsed-time smoothing with explicit input and gap handling. |
| [SuperJupiter Trend](https://github.com/Super-Jupiter/superjupiter-trend) | Timestamp-aware slopes with coverage and gap reporting. |
| [SuperJupiter ThresholdEvents](https://github.com/Super-Jupiter/superjupiter-threshold-events) | Persistent threshold events with hysteresis and an unknown state. |
| [SuperJupiter PulseMetrics](https://github.com/Super-Jupiter/superjupiter-pulse-metrics) | Pulse counts and interval-derived rates with bounce and timeout reporting. |
| [SuperJupiter TimeAggregate](https://github.com/Super-Jupiter/superjupiter-time-aggregate) | Fixed-period summaries with explicit empty buckets and coverage. |
| [SuperJupiter Integration](https://github.com/Super-Jupiter/superjupiter-integration) | Gap-aware numerical integration of timestamped observations. |
| [SuperJupiter EventCapture](https://github.com/Super-Jupiter/superjupiter-event-capture) | Bounded samples from before and after a sensor event. |

### Recording, configuration and device operation

| Library | Purpose |
| --- | --- |
| [SuperJupiter RecordJournal](https://github.com/Super-Jupiter/superjupiter-record-journal) | Append-only records with integrity checks and interrupted-write recovery. |
| [SuperJupiter StoreForward](https://github.com/Super-Jupiter/superjupiter-store-forward) | Acknowledged upload queues with explicit record identities and retry timing. |
| [SuperJupiter ConfigStore](https://github.com/Super-Jupiter/superjupiter-config-store) | Versioned configuration with integrity checks and recoverable writes. |
| [SuperJupiter DeviceHealth](https://github.com/Super-Jupiter/superjupiter-device-health) | Observable gaps, queue pressure and bounded failure counters. |
| [SuperJupiter MachineState](https://github.com/Super-Jupiter/superjupiter-machine-state) | Equipment states and observed runtime from scalar signals. |
| [SuperJupiter PowerBudget](https://github.com/Super-Jupiter/superjupiter-power-budget) | Battery current, duty-cycle and runtime estimates. |
| [SuperJupiter SensorReplay](https://github.com/Super-Jupiter/superjupiter-sensor-replay) | Deterministic sample replay with explicit dropped or replaced readings. |

## Using and contributing

Start with the selected repository's README, examples, release and validation documentation. Keep raw observations and timestamps alongside derived results. Storage adapters, networking and application decisions remain explicit responsibilities of the application where documented.

For bugs and suggestions, open an issue in the relevant library with its version, configuration, expected behaviour and a small reproducible example. Keep credentials and private customer information out of public issues. For private security reports, contact **info@superjupiter.net**.

Our public projects focus on reusable engineering components. Client work, client data and proprietary product implementations remain private.
