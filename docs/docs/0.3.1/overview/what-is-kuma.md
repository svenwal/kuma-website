# What is Kuma?

Kuma is a universal open-source control plane for Service Mesh and Microservices. It can run and be operated natively across both Kubernetes and VM environments, making it easy to adopt by every team in the organization.

Built on top of [Envoy](https://envoyproxy.io/), Kuma can instrument any L4/L7 traffic to secure, observe, route and enhance connectivity between any service or database. It can be used natively in Kubernetes via CRDs or via a RESTful API across other environments, and it doesn't require a change to your application's code in order to be used.

While being simple to use for most use-cases, Kuma also provides policies to configure the underlying Envoy data-planes in a more fine-grained manner. By doing so, Kuma can be used by both first-time users of Service Mesh, as well as the most experienced ones.

<center>
<img src="/images/docs/0.2.0/diagram-01.jpg" alt="" style="width: 500px; padding-top: 20px; padding-bottom: 10px;"/>
</center>

Kong built Kuma with feedback from 150+ enterprise organizations running Service Mesh in production. Kuma implements a pragmatic approach that is very different from the first-generation control planes:  

- **Universal**: Kuma runs on every platform, including Kubernetes and VMs.
- **Simple**: Kuma provides easy to use policies to get up and running in minutes.
- **Envoy-based**: Kuma is built on top of Envoy, the most adopted proxy for Service Mesh.

Built by Envoy contributors at Kong 🦍.

::: tip
**Need help?** Don't forget to check the [Community](/community) section! 
:::