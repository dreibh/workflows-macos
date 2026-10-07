# MacOS Debugging Workflow

This repository contains a GitHub Workflow for debugging in a MacOS instance using SSH access via [Tailscale](https://tailscale.com/) VPN: [`.github/workflows/debug-tailscale.yaml`](.github/workflows/debug-tailscale.yaml).

The workflow performs the following steps:

1. Installation of Tailscale and setup of a Tailscale VPN tunnel to allow SSH access to the instance.
2. Installation of some build dependencies, particularly:

  - [HiPerConTracer](https://github.com/dreibh/hipercontracer/) (see [HiPerConTracer – High-Performance Connectivity Tracer](https://www.nntb.no/~dreibh/hipercontracer/)),
  - [NetPerfMeter](https://github.com/dreibh/netperfmeter/) (see [NetPerfMeter – A TCP/MPTCP/UDP/SCTP/DCCP Network Performance Meter Tool](https://www.nntb.no/~dreibh/netperfmeter/)),
  - [SubNetCalc](https://github.com/dreibh/subnetcalc/) (see [SubNetCalc – An IPv4/IPv6 Subnet Calculator](https://www.nntb.no/~dreibh/subnetcalc/)),
  - [BibTeXConv](https://github.com/dreibh/bibtexconv/) (see [BibTeXConv – A BibTeX File Converter](https://www.nntb.no/~dreibh/bibtexconv/)),
  - [FractGen](https://github.com/dreibh/fractgen/) (see [FractGen – An Extensible Fractal Generator](https://www.nntb.no/~dreibh/fractalgenerator/)),
  - [System-Tools](https://github.com/dreibh/system-tools/) (see [System-Tools – Tools for Basic System Management](https://www.nntb.no/~dreibh/system-tools/)),
  - as well as the [Virtual Machine Image Builder and System Installation Scripts](https://github.com/simula/nornet-vmimage-builder-scripts/) (see [Virtual Machine Image Builder and System Installation Scripts](https://www.nntb.no/~dreibh/vmimage-builder-scripts/)).

3. Configuration of the environment to make debugging more comfortable.
