# SuperJupiter

**Physical AI, connected hardware and software that brings operations together.**

We are a technology company based in Somerset West, South Africa. We primarily develop our own physical AI products, combining AI, software, connected hardware and sensors.

We also build custom solutions for businesses, connecting existing software, equipment, devices and sensors, and developing custom hardware, sensors and gateways where needed. Our web and mobile applications bring operations together, with staff and client portals tailored to different roles across sites and regions.

[Explore SuperJupiter](https://www.superjupiter.net/) · [LinkedIn](https://www.linkedin.com/company/superjupiter-tech/) · [Contact us](mailto:info@superjupiter.net)

## Open-source libraries

Reusable MIT-licensed C++11 components for Arduino, ESP32 and host applications. Install the library you need and select individual modules. Neither requires a SuperJupiter account or cloud service.

| Library | What it helps you build |
| --- | --- |
| **[SuperJupiter Sensor Toolkit](https://github.com/Super-Jupiter/superjupiter-sensor-toolkit)** | Check measurement quality, preserve timestamped readings, align sensors, process signals and capture events. Includes 15 modules, with optional synthetic replay tooling. |
| **[SuperJupiter Embedded Reliability](https://github.com/Super-Jupiter/superjupiter-embedded-reliability)** | Manage record journals, configuration storage, acknowledged queues and device health. Includes 5 modules, with a power-budget utility. Real persistence requires an appropriate storage adapter. |

> **Hardware validation pending.** These are preview releases. Software tests and board compilation are separate from physical testing and do not establish sensor accuracy, storage durability or safety certification. Read each library's validation record and limitations.

### Start building

- [Check sensor readings](https://github.com/Super-Jupiter/superjupiter-sensor-toolkit/tree/main/examples/CheckReadings), keeping raw values and quality flags visible.
- [Explore recoverable record protocols](https://github.com/Super-Jupiter/superjupiter-embedded-reliability/tree/main/examples/RecoverableRecords) using explicitly labelled RAM storage.
- [Try the combined measurement pipeline](https://github.com/Super-Jupiter/superjupiter-sensor-toolkit/tree/main/extras/MeasurementPipeline) with both libraries. It exercises twenty components using synthetic data and RAM storage.

### Existing projects

The [standalone library catalogue](https://github.com/Super-Jupiter/.github/blob/main/profile/LEGACY-LIBRARIES.md) remains available. Existing packages and release tags are preserved. Migration is optional; follow the new include-path guidance and use one implementation per component per application.

### Contributing

Report reproducible issues in the relevant repository, including the version, configuration, expected behaviour and a small example. Keep credentials and client information out of public reports. For private security reports, contact **info@superjupiter.net**.

Client work, customer data and proprietary product implementations remain private.
