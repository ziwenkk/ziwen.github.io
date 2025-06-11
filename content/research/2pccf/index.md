---
title: "Two-point correlation function"
date: 2025-06-05

summary: The Description of the Two-Point Correlation Function and My Research

image:
    caption: '[**Image credit**](https://www.sdss4.org/science/)'

authors:
  - admin
  - Ziwen Zhang

tags: ["Two-Point Correlation", "Cosmic Structures", "Galaxy Distribution", "Cosmology", "Astronomy"]

---

## 1. The Universe's Matter Distribution is Not Uniform: Introducing Overdensity

The distribution of matter in the Universe is not uniform. Instead, we observe structures on large scales such as galaxy filaments, clusters, and voids. These structures vary in scale from a few hundred thousand to billions of light years. To quantify this non-uniform distribution, the concept of **overdensity** is used. Overdensity measures the deviation of the density of matter in a specific region relative to the average density of the Universe, defined as:

{{< math >}}
$$
\delta(\mathbf{r}) = \frac{n(\mathbf{r}) - \bar{n}}{\bar{n}}
$$
{{< /math >}}

Where:

- \(n(\mathbf{r})\) is the density at position \(\mathbf{r}\),
- \(\bar{n}\) is the average density of the Universe.

If \(\delta(\mathbf{r}) > 0\), the region is considered an "overdense" region; otherwise, it is considered "underdense."

---

## 2. The Redshift-Space Two-Point Correlation Function

To describe the structure of galaxy distributions, the **two-point correlation function** (2PCF) was introduced. This statistical tool quantifies the spatial correlations between pairs of galaxies, specifically their separation distances, and helps us understand how galaxies are distributed in the Universe.

The classic definition of the two-point correlation function, introduced by **Davis and Peebles** in 1983, is:

{{< math >}}
$$
\xi(r) = \frac{GD(r)}{GR(r)} - 1
$$
{{< /math >}}

Where:

- \(GD(r)\) is the number of observed galaxy pairs at a separation distance \(r\),
- \(GR(r)\) represents the number of pairs between galaxies and random points at a separation distance \(r\).
- \(\xi(r)\) is the redshift-space two-point correlation function.

---

## 3. Projected Two-Point Correlation Function

Due to the redshift distortion effects, the two-point correlation function in redshift space may not be accurate. Hence, the **projected two-point correlation function** is used. This is simply the integration of the two-point correlation function \(\xi(r_p, \pi)\) along the line of sight. This gives the projected two-point correlation function \(w_p(r_p)\), which is defined as:

\[
w_p(r_p) = \int_-\infty^\infty \xi(r_p, \pi) d\pi
\]

Where:

- \(\pi\) is the separation parallel to the line of sight,

This method helps to mitigate the redshift distortion effects and provides a more accurate galaxy clustering measurements.

---

## 4. Information in the Projected Two-Point Correlation Function at Small and Large Scales

### 4.1 Information at Small Scales

At **small scales**, the projected two-point correlation function primarily reflects the **local density** around galaxies and the **strength of interactions** between galaxies. Small scales correspond to distances within the halo virial radius (one-halo term). On these scales, galaxies could be influenced by the member galaxies in clusters or groups, leading to stronger interactions.

### 4.2 Information at Large Scales

At **large scales**, the projected two-point correlation function provides insight into the distribution of galaxies within **large-scale structures** such as galaxy filaments and clusters.

- **Halo Bias**

- **Halo Assembly Bias**: 

- **Large-Scale Structure**: By calculating the projected two-point correlation function at large scales, we can uncover how galaxies organize into **large-scale structures**, such as filaments and voids. This helps us understand the formation and evolution of cosmic structures over time.

---

## Summary

The **projected two-point correlation function** provides an essential tool for studying the spatial distribution of galaxies. By analyzing the projected 2PCF, we can obtain insights into:

- **Small Scales**: Reflecting the local density and interaction strength between galaxies in dense environments like clusters.
- **Large Scales**: Offering insights into **halo bias**, **halo assembly bias**, and the large-scale structure of the universe.

This function is crucial in cosmology, as it allows researchers to study the universe's large-scale structure and galaxy clustering patterns, even with limited observational data.

---

<script defer src="https://cdn.commento.io/js/commento.js"></script>
<div id="commento"></div>

---
