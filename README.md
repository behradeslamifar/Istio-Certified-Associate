# Istio-Certified-Associate

## Prepare a Lab
- [Istio Lab](labs/README.md)

## Exam Objectives

These are the exam objectives you review and understand in order to pass the test.

* [github.com: CNCF Exam Curriculum repository ](https://github.com/cncf/curriculum)
* [linuxfoundation.org: ICA Home Page](https://training.linuxfoundation.org/certification/istio-certified-associate-ica/)
* [Resources allowed during the examp](https://docs.linuxfoundation.org/tc-docs/certification/certification-resources-allowed#istio-certified-associate-ica)

<details><summary>Istio Installation, Upgrade & Configuration 7%</summary>
<p>

- [Using the Istio CLI to install a basic cluster](https://istio.io/latest/docs/setup/install/istioctl/)
  - [youtube.com: Mesh Week (Session 1)](https://www.youtube.com/watch?v=w_8Gg_jsAbU)
  - [istio.io: Installation Configuration Profiles](https://istio.io/latest/docs/setup/additional-setup/config-profiles/)
- [Customizing the Istio installation with the IstioOperator API](https://istio.io/latest/docs/reference/config/istio.operator.v1alpha1/)
- [Using overlays to manage Istio component settings](https://istio.io/latest/docs/setup/additional-setup/customize-installation/#identify-an-istio-component)

</p>
</details>

<details><summary>Traffic Management 40%</summary>
<p>

- [Controlling network traffic flows within a service mesh](https://istio.io/latest/docs/tasks/traffic-management/request-routing/)
  - [youtube.com: Mesh Week (Session 2)](https://www.youtube.com/watch?v=Q-l1z3ejc8Q)
  - [solo.io: Istio Networking in Depth](https://www.solo.io/blog/istios-networking-in-depth/)
- [Configuring sidecar injection](https://istio.io/latest/docs/setup/additional-setup/sidecar-injection/)
- [Using the Gateway resource to configure ingress and egress traffic](https://istio.io/latest/docs/reference/config/networking/gateway/)
  - [istio.io: Egress Gateway](https://istio.io/latest/docs/tasks/traffic-management/egress/egress-gateway/)
  - [istio.io: Virtualservice](https://istio.io/latest/docs/reference/config/networking/virtual-service/)
- [Understanding how to use ServiceEntry resources for adding entries to internal service registry](https://istio.io/latest/docs/reference/config/networking/service-entry/)
  - [solo.io: Istio multi-cluster traffic](https://www.solo.io/blog/istio-multi-cluster-traffic-debugging/)
- [Define traffic policies using DestinationRule](https://istio.io/latest/docs/reference/config/networking/destination-rule/)
- [Configure traffic mirroring capabilities](https://istio.io/latest/docs/tasks/traffic-management/mirroring/)
  - [envoyproxy.io: HTTP route components](https://www.envoyproxy.io/docs/envoy/latest/api-v3/config/route/v3/route_components.proto#config-route-v3-routeaction-requestmirrorpolicy)

</p>
</details>

<details><summary>Resilience and Fault Injection 20%</summary>
<p>

- [Configuring circuit breakers (with or without outlier detection)]()
- [Using resilience features]()
- [Creating fault injection]()

</p>
</details>

<details><summary>Securing Workloads 20%</summary>
<p>

- [Understand Istio security features]()
- [Set up Istio authorization for HTTP/TCP traffic in the mesh]()
- [Configure mutual TLS at mesh, namespace, and workload levels]()

</p>
</details>

<details><summary>Advanced Scenarios 13%</summary>
<p>

- [Understand how to onboard non-Kubernetes workloads to the mesh]()
- [Troubleshoot configuration issues]()

</p>
</details>

## Other resources
- [academy.solo.io: ServiceMesh and CNI  free courses](https://academy.solo.io/learn)
- [academy.tetrate.io: ServiceMesh free cources](https://academy.tetrate.io/collections)
- [github.com: Mesh Week Videos](https://github.com/solo-io/mesh-week)
- [github.com: Blog posts about ICA](https://github.com/yuyatinnefeld/istio?tab=readme-ov-file)
