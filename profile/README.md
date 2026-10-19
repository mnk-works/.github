# mnk-works

Security research and tooling: offline-first utilities, cryptographic
post-mortems, and reproducibility-focused proof-of-concepts.

## Projects

| Repository | Description |
| --- | --- |
| [non-csrng](https://github.com/mnk-works/non-csrng) | PoC showing `Math.random()` is not a CSPRNG — recover the V8 xorshift128+ state from 4 outputs with z3 and predict every future value. |
| [check-seed](https://github.com/mnk-works/check-seed) | Offline-first BIP39 seed phrase validation and local address derivation with balance lookup. |
| [qubic-incident](https://github.com/mnk-works/qubic-incident) | Forensic teardown of the October 2026 Qubic wallet drain caused by `Math.random()`-generated seeds. |

---

## Donate

Monero (XMR) — mainnet subaddress:

```
85ifMryXKt79vSwCojDbFGUd3wM9MrSHUDegKthugb62PNbRv914nDKZzZFS8zBKuwArQTipVgJeoGo8gcYBeZQ4F19Z8im
```

<img src="https://raw.githubusercontent.com/mnk-works/.github/main/profile/monero-donation-qr.avif" width="320" alt="Monero donation QR code (monero: URI)" />
