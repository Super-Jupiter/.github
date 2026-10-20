# Standalone SuperJupiter libraries

These original packages and their published versions remain available for existing projects. For new projects, start with [SuperJupiter Sensor Toolkit](https://github.com/Super-Jupiter/superjupiter-sensor-toolkit) or [SuperJupiter Embedded Reliability](https://github.com/Super-Jupiter/superjupiter-embedded-reliability).

Migration is optional. Follow the consolidated library's migration guide and use one implementation of each component per application. No old repository or release has been deleted or archived as part of consolidation.

**Hardware validation pending.** Software tests and board compilation are distinct from physical testing.

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

