# CloudEvents (cloudevents)

CloudEvents is a CNCF Graduated specification for describing event data in a common way. It defines a vendor-neutral set of metadata attributes (id, source, type, specversion, time, datacontenttype, subject, etc.) that are present in every event, enabling consistent routing, filtering, and processing of events across services, platforms, message buses, and cloud providers. CloudEvents includes protocol bindings for HTTP, AMQP, Kafka, MQTT, and NATS, a JSON event format, the CloudEvents Subscriptions API, and the CloudEvents SQL (CESQL) filter language, alongside official SDKs in Go, JavaScript, Java, C#, Python, Ruby, PHP, Rust, and PowerShell.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/cloudevents/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** standard
- **Governance:** CNCF (Cloud Native Computing Foundation)
- **Status:** Graduated (January 25, 2024)
- **Spec Version:** 1.0.2 (released February 5, 2022)

## Tags

Cloud Native, Events, Graduated, Interoperability, Messaging, Specification

## APIs

### CloudEvents Specification
The core specification defining required and optional event attributes, content modes, and the abstract event data model that all bindings and SDKs implement.

- [Specification (v1.0.2)](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/spec.md)
- [JSON Schema](json-schema/cloudevents-event-schema.json)
- [AsyncAPI](asyncapi/cloudevents-http-asyncapi.yml)

### CloudEvents HTTP Protocol Binding
Maps CloudEvents to HTTP messages in either structured (entire event in body) or binary (attributes in headers) content modes, enabling REST APIs to produce and consume standardized events.

- [HTTP Binding](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/http-protocol-binding.md)

### CloudEvents Kafka Protocol Binding
Maps CloudEvents attributes to Apache Kafka headers and event payload to the message value for standardized event interchange over Kafka topics.

- [Kafka Binding](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/kafka-protocol-binding.md)

### CloudEvents AMQP Protocol Binding
Defines structured and binary content modes for OASIS AMQP 1.0, mapping attributes to AMQP message properties.

- [AMQP Binding](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/amqp-protocol-binding.md)

### CloudEvents MQTT Protocol Binding
Maps events to MQTT 3.1.1 and MQTT 5.0 messages for IoT and constrained-device environments.

- [MQTT Binding](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/mqtt-protocol-binding.md)

### CloudEvents NATS Protocol Binding
Maps events to NATS messages, supporting publish/subscribe and request/reply over the NATS messaging system.

- [NATS Binding](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/nats-protocol-binding.md)

### CloudEvents Subscriptions API
Vendor-neutral REST API for creating, listing, updating, and deleting subscriptions to event streams with filter criteria.

- [Subscriptions Spec](https://github.com/cloudevents/spec/blob/main/subscriptions/spec.md)
- [OpenAPI](openapi/cloudevents-subscriptions-openapi.yml)

### CloudEvents SQL (CESQL)
v1.0 standardized SQL-like query language for filtering and routing CloudEvents based on attributes.

- [CESQL Spec](https://github.com/cloudevents/spec/blob/main/cesql/spec.md)

### Official SDKs
Language SDKs maintained by the CloudEvents project:

- [Go SDK](https://github.com/cloudevents/sdk-go)
- [JavaScript SDK](https://github.com/cloudevents/sdk-javascript)
- [Java SDK](https://github.com/cloudevents/sdk-java)
- [Python SDK](https://github.com/cloudevents/sdk-python)

## Common Properties

- [Website](https://cloudevents.io)
- [Specification Repository](https://github.com/cloudevents/spec)
- [Primer / Getting Started](https://github.com/cloudevents/spec/blob/main/cloudevents/primer.md)
- [Blog](https://cloudevents.io/blog/)
- [GitHub Organization](https://github.com/cloudevents)
- [SDKs](https://github.com/cloudevents/spec/blob/main/cloudevents/SDK.md)
- [Change Log](https://github.com/cloudevents/spec/releases)
- [JSON Schema](json-schema/cloudevents-event-schema.json)
- [OpenAPI](openapi/cloudevents-subscriptions-openapi.yml)
- [AsyncAPI](asyncapi/cloudevents-http-asyncapi.yml)
- [JSON-LD](json-ld/cloudevents-context.jsonld)
- [Spectral](rules/cloudevents-rules.yml)
- [Naftiko Capabilities](capabilities/cloudevents-subscriptions-capabilities.yml)

## Maintainers

- **FN:** Kin Lane
- **Email:** kinlane@gmail.com
