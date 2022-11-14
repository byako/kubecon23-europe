---

What is the title of your presentation?

Implementing resource-driver for K8s Dynamic Resource Allocation (DRA)

---

Submission format:

Dual Presentation: 35-minute presentation, limited to 2 speakers

---

Who's presenting (email address)? 

email1, email2

---

Primary topic:

Runtime Performance + Constrained Environments

---

Detailed and focused description:

Dynamic Resource Allocation (DRA) is new approach for allocating HW resource in K8s. It gives much more flexibility and control over resources allocation to the component responsible for particular resource - "resource-driver". This session will show how to create such a resource-driver to utilize K8s DRA: custom resource definitions, API and sequence of event from DRA resource-driver point of view, as well as demo two existing DRA drivers in several use-cases: Nvidia GPU resource-driver, Intel GPU resource-driver and community example implementation of abstract resource-driver for /dev/null device.

---

Top 1-3 key takeaways or "Benefits for Ecosystem"

We will walk through the core parts of the Dynamic Resource Allocation (DRA) resource-driver creation, its operations and expectations with two existing resource-driver examples: GPU resource driver from Nvidia, and GPU resource driver from Intel, and a community example driver (TBD) that can be easily forked as a base for resource-driver implementation. This is supposed to bring to K8s community the knowledge and experience sharing of DRA from vendor and user perspective - how HW vendors and community in general can make usage of HW resources more flexible, more granular.
