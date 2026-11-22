## v1.3.0 — 2026-11-23

- Every tap now represents a distinct approval request, including rapid taps.
- Queue taps received while another request is in flight, and submit them in order after each response.
- Do not impose an active-approval cooldown.
- This does not override MyGate backend rejection or guarantee a successful response to a second request.

