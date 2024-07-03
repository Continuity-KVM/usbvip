USB (via) IP
==========

## About USB (via) IP:

This is part of the Continuity KVM Suite, but it is usable by any other
project or tool as well. It's written in Rust, but I think a combination
of Rust and C/C++ may be needed, via FFI.

It provides a network-based interface over encrypted TLS, serialised in the
Msgpack serialisation format.

The server will have a secure link with the client machine, and makes USB
devices 'available', but only to one machine at a time. 

The client will be able to choose which USB devices to accept from the available
devices.

## Why do we need yet another USB over IP project?

The 'USB/IP' project hosted [here][usbslaship] hasn't been updated since 2011.

I also don't think it has encryption available. USB (via) IP aims for a modern
solution, with memory safety, encryption, and performance .

## How do I install this?

Unfortunately, it's nowhere near ready yet.

I will be soon be creating a contribution guide, ways to get started, issues
to be tackled, etc.

## How can I donate?

Donations aren't setup yet, but check back later! I plan to set up a Pateron
at some point.

## License

This project is hosted under the MIT [license][license].

[usbslaship]: http://usbip.sourceforge.net/
[license]: /LICENSE
