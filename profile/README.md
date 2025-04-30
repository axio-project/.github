# Axio: Accelerated Network I/O Framework

**Axio** is a high-performance, programmable, and extensible framework for building **NIC-centric network I/O systems** on modern DPU platforms. It is designed to push the limits of datacenter networking by combining cutting-edge I/O techniques, modular offloads, and developer-friendly toolkits into one unified framework.

---

## What is Axio?

Axio is a comprehensive framework that enables efficient construction of next-generation DPU-based networking stacks.  
It targets **400Gbps+ performance**, **cross-layer programmability**, and **scalable extensibility**, making it suitable for emerging datacenter workloads that demand low latency, high throughput, and deep customization.

---

## Axio Components

### Axio Runtime
A collection of pre-compiled, optimized I/O runtimes built using advanced dataplane techniques like **CEIO**, **RhyR**, and **Enso**.  
Future support will include **HBM-free I/O** to further improve resource efficiency.

### Axio Offloads
A set of portable and reusable **offloading engines** designed to accelerate dataplane processing.  
The roadmap includes **control-plane offloads** to further decouple CPU responsibilities and improve system responsiveness.

### Axio Platform Express
An optimization layer for **BlueField-3** DPU platforms, integrating DPU-specific innovations such as:
- **EDDoS**: Elastic dataplane scheduling
- **ZeroNIC**: Minimal host NIC interaction model  
This layer maximizes DPU-native performance and supports **programmable RDMA datapaths**.

### Axio Library & Toolkit
A full-featured SDK that provides:
- **Runtime deployment tools**
- **Offload development APIs**
- **Diagnostic utilities**  
This toolkit simplifies development, debugging, and deployment of customized dataplane logic.

---

## Key Features

| Feature | Description |
|--------|-------------|
| **High Performance** | Built for 400Gbps+ data rates with zero-copy techniques, NIC-native acceleration, and HBM-free support. |
| **Programmable** | Enables flexible dataplane programming, supporting custom offloads and RDMA pipelines. |
| **Extensible** | Modular architecture supports adding new runtimes, platforms, and toolkits to adapt to future networking workloads. |

---

## Use Cases

- DPU-native RPC acceleration
- Programmable RDMA communication
- GPU-to-GPU data movement pipelines
- Offloaded control and dataplane coordination
- Scalable network functions without host CPU dependency

---

## Contact

For collaboration, feedback, or contribution inquiries, please contact us via GitHub Issues or email.
