# CloudEvents (cloudevents)

CloudEvents is a CNCF graduated specification for describing event data in a common way. It provides a consistent format for event metadata across services, platforms, and systems, enabling interoperability between event producers and consumers. The specification includes protocol bindings for HTTP, AMQP, Kafka, MQTT, and NATS, along with SDKs in multiple languages.

**APIs.json:** [https://cloudevents.io](https://cloudevents.io)

## Scope

- **Type:** Index

## Tags

- Cloud Native
- Events
- Graduated
- Interoperability
- Messaging
- Specification

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### CloudEvents Specification

The CloudEvents specification defines a set of metadata attributes that must be present in every event, including source, type, id, and specversion. It provides a vendor-neutral way to describe events that enables consistent routing, filtering, and processing across different systems and cloud providers.

- **Human URL:** [https://cloudevents.io/](https://cloudevents.io/)

#### Tags

- Events
- Specification
- Standards

#### Properties

- [Documentation](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/spec.md)
- [Reference](https://github.com/cloudevents/spec/blob/main/cloudevents/spec.md)
- [GitHub Repository](https://github.com/cloudevents/spec)
- [Changelog](https://github.com/cloudevents/spec/releases)
- [JSON Schema](json-schema/cloudevents-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [AsyncAPI](asyncapi/cloudevents-http-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents HTTP Protocol Binding

The HTTP protocol binding defines how CloudEvents are transported using HTTP, including structured content mode where the entire event is in the HTTP body, and binary content mode where event attributes are mapped to HTTP headers. This enables REST APIs to produce and consume standardized events.

- **Human URL:** [https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/http-protocol-binding.md](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/http-protocol-binding.md)

#### Tags

- HTTP
- Protocol Binding
- REST

#### Properties

- [Documentation](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/http-protocol-binding.md)
- [Reference](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/http-protocol-binding.md)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents Kafka Protocol Binding

The Kafka protocol binding for CloudEvents defines how events are mapped to Apache Kafka messages. It specifies how CloudEvents attributes are encoded as Kafka message headers and how the event payload is placed in the Kafka message value, enabling standardized event interchange over Kafka topics.

- **Human URL:** [https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/kafka-protocol-binding.md](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/kafka-protocol-binding.md)

#### Tags

- Kafka
- Messaging
- Protocol Binding

#### Properties

- [Documentation](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/kafka-protocol-binding.md)
- [Reference](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/kafka-protocol-binding.md)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents AMQP Protocol Binding

The AMQP protocol binding for CloudEvents defines how events are mapped to OASIS AMQP 1.0 messages. In structured content mode, event attributes and data are placed in the AMQP message application data section; in binary content mode, event data is placed as-is with attributes mapped to AMQP message properties.

- **Human URL:** [https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/amqp-protocol-binding.md](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/amqp-protocol-binding.md)

#### Tags

- AMQP
- Messaging
- Protocol Binding

#### Properties

- [Documentation](https://github.com/cloudevents/spec/blob/v1.0.2/cloudevents/bindings/amqp-protocol-binding.md)
- [Reference](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/amqp-protocol-binding.md)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents MQTT Protocol Binding

The MQTT protocol binding for CloudEvents defines how events are mapped to MQTT 3.1.1 and MQTT 5.0 messages. It supports both structured and binary content modes for IoT and constrained device environments that use MQTT as their messaging protocol.

- **Human URL:** [https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/mqtt-protocol-binding.md](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/mqtt-protocol-binding.md)

#### Tags

- IoT
- MQTT
- Protocol Binding

#### Properties

- [Documentation](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/mqtt-protocol-binding.md)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents NATS Protocol Binding

The NATS protocol binding for CloudEvents defines how events are mapped to NATS messages. It enables CloudEvents to be produced and consumed over the NATS messaging system, supporting both publish/subscribe and request/reply patterns.

- **Human URL:** [https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/nats-protocol-binding.md](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/nats-protocol-binding.md)

#### Tags

- Messaging
- NATS
- Protocol Binding

#### Properties

- [Documentation](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/nats-protocol-binding.md)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents Subscriptions API

The CloudEvents Subscriptions API specification defines a standard REST API for managing subscriptions to event streams. It enables clients to create, list, update, and delete subscriptions with filter criteria, providing a vendor-neutral way to manage event delivery configurations across different event brokers and message systems.

- **Human URL:** [https://github.com/cloudevents/spec/blob/main/subscriptions/spec.md](https://github.com/cloudevents/spec/blob/main/subscriptions/spec.md)

#### Tags

- REST
- Specification
- Subscriptions

#### Properties

- [Documentation](https://github.com/cloudevents/spec/blob/main/subscriptions/spec.md)
- [OpenAPI](openapi/cloudevents-subscriptions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents SQL (CESQL)

CloudEvents SQL (CESQL) is a v1.0 specification that defines a standardized query language for filtering and routing CloudEvents based on their attributes. It provides a SQL-like syntax for writing event filter expressions that can be used across different event processing platforms and systems.

- **Human URL:** [https://github.com/cloudevents/spec/blob/main/cesql/spec.md](https://github.com/cloudevents/spec/blob/main/cesql/spec.md)

#### Tags

- Filtering
- Specification
- SQL

#### Properties

- [Documentation](https://github.com/cloudevents/spec/blob/main/cesql/spec.md)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents Go SDK

The official Go SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Go applications. It supports all CloudEvents protocol bindings and content modes, and includes client implementations for HTTP, Kafka, and other transports.

- **Human URL:** [https://github.com/cloudevents/sdk-go](https://github.com/cloudevents/sdk-go)

#### Tags

- Client Library
- Go
- SDK

#### Properties

- [Documentation](https://cloudevents.github.io/sdk-go/)
- [GitHub Repository](https://github.com/cloudevents/sdk-go)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents JavaScript SDK

The official JavaScript SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Node.js and browser environments. It supports structured and binary content modes over HTTP and other transports.

- **Human URL:** [https://github.com/cloudevents/sdk-javascript](https://github.com/cloudevents/sdk-javascript)

#### Tags

- Client Library
- JavaScript
- SDK

#### Properties

- [Documentation](https://github.com/cloudevents/sdk-javascript/blob/main/README.md)
- [GitHub Repository](https://github.com/cloudevents/sdk-javascript)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents Java SDK

The official Java SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Java applications. It includes support for HTTP, Kafka, and other transports, and integrates with popular Java frameworks.

- **Human URL:** [https://github.com/cloudevents/sdk-java](https://github.com/cloudevents/sdk-java)

#### Tags

- Client Library
- Java
- SDK

#### Properties

- [Documentation](https://github.com/cloudevents/sdk-java/blob/main/README.md)
- [GitHub Repository](https://github.com/cloudevents/sdk-java)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents Python SDK

The official Python SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Python applications. It supports HTTP transport bindings and both structured and binary content modes.

- **Human URL:** [https://github.com/cloudevents/sdk-python](https://github.com/cloudevents/sdk-python)

#### Tags

- Client Library
- Python
- SDK

#### Properties

- [Documentation](https://github.com/cloudevents/sdk-python/blob/main/README.md)
- [GitHub Repository](https://github.com/cloudevents/sdk-python)
- [Postman Collection](collections/cloudevents-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudevents-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://cloudevents.io)
- [Documentation](https://github.com/cloudevents/spec)
- [Getting Started](https://github.com/cloudevents/spec/blob/main/cloudevents/primer.md)
- [Blog](https://cloudevents.io/blog/)
- [GitHub Organization](https://github.com/cloudevents)
- [S D Ks](https://github.com/cloudevents/spec/blob/main/cloudevents/SDK.md)
- [Changelog](https://github.com/cloudevents/spec/releases)
- [JSON Schema](json-schema/cloudevents-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [OpenAPI](openapi/cloudevents-subscriptions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/cloudevents-http-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON-LD](json-ld/cloudevents-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/cloudevents-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
