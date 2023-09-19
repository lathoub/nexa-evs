A developer friendly REST-API for EVS Live Production Servers.

# Pynch Nexa for EVS Live Production Severs

The Pynch Nexa application exposes an [HTTP RESTful API](https://github.com/lathoub/nexa-api) to help with the automation of the [EVS Live Production Severs](https://evs.com/products/live-production-servers) suite. Nexa run on top of the EVS technology stack and does not alter nor does it interfere with its (inner) working.

The Pynch Nexa for EVS is a **Windows** only application, a limitation inherited from the underlying software. The exposed HTTP service however can be used by all operating systems, browsers and HTTP clients.

## Compatible EVS Products

- [XT-VIA](https://evs.com/products/live-production-servers/xt-via)
- [XT-GO](https://evs.com/products/live-production-servers/xt-go)
- [XS-VIA](https://evs.com/products/live-production-servers/xs-via)
- [XS-NEO](https://evs.com/products/live-production-servers/xt-neo)

## Installation and prerequisites
Described in the [wiki section](https://github.com/lathoub/nexa-evs/wiki/Installation).

## How does it work?

The Pynch Nexa application interacts with the underlying EVS software and exposes it through a [RESTful API](https://github.com/lathoub/nexa-api). No need to deal with the inner workings of the EVS machines, but use the very familar HTTP protocol to control all the functions of the EVS servers.

The [RESTful API](https://github.com/lathoub/nexa-api) definition is agnostic of the underlying (EVS) hardware.

<img width="1435" alt="Screenshot 2023-09-18 at 08 43 27" src="https://github.com/lathoub/nexa-evs/assets/4082369/429b5ad0-a1af-4a9e-87be-30627acf54cf">
