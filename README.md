# Control-Flow-Integrity---PANDA-Plugin
Plugin to detect Control Flow Integrity Voilations


A common property most modern exploits leverage is the manipulation of control flow. In this paper, we present plugins for PANDA that enforce a system-wide control
flow integrity policy, using a combination of whitelist and shadow call stack based approaches that monitor control flow transfers and detect violations. Replays of a
simple stack exploits are created using PANDA and analyzed to identify when control flow integrity is broken. We test our plugins on benign replays as well as the replays
with successful stack exploitations.
