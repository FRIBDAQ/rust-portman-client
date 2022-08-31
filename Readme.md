This package provides minimal RUST support for the port manager.
Using this crate, rust programs can request service ports of the
local port manager as well as get a listing of the ports that
are already in use.

==== History

This was hoisted from the development project for the NSCLDAQ
RingMaster but is needed by ring master client crates as well
since the RingMaster must be located via the port manager.
