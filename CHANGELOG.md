# CHANGELOG

# 0.6.3

* Added support for wasm32-wasip2.
* Added `Socket::(set_)ip_transparent_v6`.
* Added `Socket::set_tcp_ack_frequency`.
* Support windows-sys v0.61 in addition to v0.60.

**POTENTIALLY BREAKING** The MSRV of windows-sys v0.61 is 1.71. To use socket2
with its MSRV of 1.70, please downgrade windows-sys to v0.60.x. This can be done
using: `cargo update windows-sys --precise 0.60.2`

# 0.6.2

* `MsgHdr` and `MsgHdrMut` are marked as transparent meaning both have the same
