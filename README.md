<!-- # IPGS: Importance-Preserving Progressive Gaussian Splatting -->

<!-- > **Progressive reconstruction for dynamic scenes under constrained storage and bandwidth.**

IPGS is a progressive representation for 4D Gaussian Splatting designed to support flexible reconstruction quality across heterogeneous device and network conditions. Rather than requiring a separate model for each target budget, IPGS organizes a single representation into ordered prefixes and optimizes these prefixes jointly, enabling graceful quality scaling as more data becomes available. -->

## Qualitative Results

### cut_roasted_beef
<video controls muted loop playsinline width="100%"> <source src="./asserts/video/cut_roasted_beef.mp4" type="video/mp4"> Your browser does not support HTML video. </video>

### coffee_martini

<video controls muted loop playsinline width="100%"> <source src="./asserts/video/coffee_martini.mp4" type="video/mp4"> Your browser does not support HTML video. </video>

### flame_salmon_1

<video controls muted loop playsinline width="100%"> <source src="./asserts/video/flame_salmon_1.mp4" type="video/mp4"> Your browser does not support HTML video. </video>


<!-- ## Why IPGS?

- **Progressive representation learning.** A single optimized representation supports multiple prefix budgets, avoiding the need to train an independent model for every target size.
- **Importance-aware ordering.** Gaussians are arranged using canonical opacity, providing a global order suitable for progressive delivery across time.
- **Progressive quantization.** Precision is allocated according to importance to reduce storage while preserving reconstruction quality.
- **Bandwidth-adaptive delivery.** The progressive structure supports reconstruction at different data budgets, making it suitable for heterogeneous network conditions.

## Method at a Glance

IPGS combines progressive representation learning with importance-aware compression and transmission. The same ordered representation can be truncated or progressively delivered according to the available storage or bandwidth budget. -->

<!-- ## Resources

- **Paper:** *[Add paper title / DOI / arXiv link]*
- **Project page:** *[Add project-page URL]*
- **Code:** *[Add repository URL]*

---

*IPGS — Importance-Preserving Progressive Gaussian Splatting* -->
