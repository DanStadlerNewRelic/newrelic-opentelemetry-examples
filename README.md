[![Example Code header](https://github.com/newrelic/opensource-website/raw/develop/src/images/categories/Example_Code.png)](https://opensource.newrelic.com/oss-category/#example-code)

# New Relic OpenTelemetry Examples

This project contains examples illustrating usage of OpenTelemetry with New Relic.

## Getting Started

1. Clone this repo.
2. Follow the directions in the README of the example that you are interested in.

## Examples Index

* Collector
  * [OpenTelemetry Collector with New Relic Exporter](./collector/nr-exporter-docker): Run the OpenTelemetry Collector with the New Relic exporter.
  * [Kubernetes Collector Tail Based Sampling](./collector/k8s-collector-tail-sampling): Configure a Kubernetes environment to do tail based sampling with the Collector before exporting to New Relic.
  * [OpenTelemetry Collector with New Relic Exporter](./collector/nr-exporter-docker): Run the OpenTelemetry Collector with the New Relic exporter. 
* Go
  * [Sending metrics with the OpenTelemetry Go SDK](./go/go-metrics): Demonstrates how to configure the Go metrics SDK to send metrics to New Relic.
* Java
  * [OpenTelemetry Agent New Relic Config](./java/agent-nr-config): A Java application with the OpenTelemetry Agent configured for New Relic.
  * [OpenTelemetry with New Relic Distributed Tracing](./java/otel-nr-dt): Demonstrate distributed tracing for applications instrumented with OpenTelemetry and the New Relic java agent.
  * [OpenTelemetry SDK New Relic Config](./java/sdk-nr-config): A Java application with custom OpenTelemetry instrument configured for New Relic via the SDK.
  * [OTLP Load Generator](./java/otlp-load-generator): A Java application that generates OTLP span and metric data. 

## Contribute

We encourage your contributions to improve `newrelic-opentelemetry-examples`! Keep in mind that when you submit your pull request, you'll need to sign the CLA via the click-through using CLA-Assistant. You only have to sign the CLA one time per project.

If you have any questions, or to execute our corporate CLA (which is required if your contribution is on behalf of a company), drop us an email at opensource@newrelic.com.

**A note about vulnerabilities**

As noted in our [security policy](../../security/policy), New Relic is committed to the privacy and security of our customers and their data. We believe that providing coordinated disclosure by security researchers and engaging with the security community are important means to achieve our security goals.

If you believe you have found a security vulnerability in this project or any of New Relic's products or websites, we welcome and greatly appreciate you reporting it to New Relic through [HackerOne](https://hackerone.com/newrelic).

If you would like to contribute to this project, review [these guidelines](./CONTRIBUTING.md).

To all contributors, we thank you!  Without your contribution, this project would not be what it is today.

## License
`newrelic-opentelemetry-examples` is licensed under the [Apache 2.0](http://apache.org/licenses/LICENSE-2.0.txt) License.

`newrelic-opentelemetry-examples` also uses source code from third-party libraries. You can find full details on which libraries are used and the terms under which they are licensed in the third-party notices document.
