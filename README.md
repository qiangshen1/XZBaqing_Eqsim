# 2026 Baqing *M*<sub>S</sub> 7.0 Earthquake: Source Rupture Model and Animation

[![Earthquake](https://img.shields.io/badge/Event-Baqing%20Earthquake-blue)](https://github.com/qiangshen1/XZBaqing_Eqsim)
[![Date](https://img.shields.io/badge/Date-2026--10--22-lightgrey)](https://github.com/qiangshen1/XZBaqing_Eqsim)
[![Model](https://img.shields.io/badge/Model-SRF-orange)](Baqing-Spatial_hyb.srf)

This repository shares a **finite-fault earthquake source rupture model** and its **rupture-evolution animation** for the 22 October 2026 *M*<sub>S</sub> 7.0 Baqing earthquake in Xizang (Tibet), China. These materials are provided for scientific visualization and research communication related to physics-based earthquake ground-motion simulation.

## Earthquake overview

| Parameter | Value |
| :--- | :--- |
| Event | 2026 Baqing earthquake, Xizang (Tibet), China |
| Origin time | 2026-10-22 22:33, China Standard Time (UTC+08:00) |
| Epicenter | 32.40° N, 93.79° E |
| Reported magnitude | *M*<sub>S</sub> 7.0 |
| Reported focal depth | 10 km |
| Regional setting | Qiangtang terrane, central-northern Tibetan Plateau |

The earthquake was predominantly a normal-faulting event in an extensional tectonic setting. Its source rupture characteristics and their effects on seismic-wave propagation are subjects of ongoing research. Event parameters above refer to the reported earthquake, **not necessarily to the precise origin, magnitude, or geometric parameters encoded in the SRF file**.

## Repository contents

| File | Description |
| :--- | :--- |
| [`Baqing-Spatial_hyb.srf`](Baqing-Spatial_hyb.srf) | Finite-fault rupture model in SRF format. |
| [`Baqing-Spatial_hyb_rupture_movie_sound.mp4`](Baqing-Spatial_hyb_rupture_movie_sound.mp4) | Animation illustrating the spatiotemporal evolution of the rupture model (with audio). |
| [`README.md`](README.md) | Project overview, files, and visualization links. |

## Rupture animation

**▶ [Watch the rupture-evolution animation (MP4)](Baqing-Spatial_hyb_rupture_movie_sound.mp4)**

If the GitHub file page does not play the video inline, select **View raw** or **Download raw file**, then open it in a video player.

The animation is a visualization of the **modeled rupture process**. It is not an observed ground-motion recording, nor is it a direct map of simulated PGA, PGV, or seismic intensity.

## Source rupture model

**⬇ [View / download the source model (SRF)](Baqing-Spatial_hyb.srf)**

The `.srf` extension denotes a source-rupture file used in finite-fault earthquake simulation workflows. Consult the file header and the conventions of your SRF-compatible modeling tools before using it. In particular, check the fault geometry, coordinate reference, units, time sampling, and compatibility with your selected solver. The file is provided **as-is**; no input configuration for a particular wave-propagation solver is included in this repository.

## Research scope and status

This repository currently contains a **rupture model and its visualization**, rather than a complete numerical ground-motion simulation dataset. Related research investigates source rupture, three-dimensional seismic-wave propagation, and the influence of complex topography on earthquake ground motions in the Baqing region.

The materials should be treated as **research products subject to refinement**. Quantitative source-model parameters and any scientific conclusions should be established from the underlying model and the associated research publication, rather than inferred from the animation alone.

## Use and attribution

When using these resources in academic work, please acknowledge this repository:

> Qiang, S. (2026). *2026 Baqing MS 7.0 earthquake: source rupture model and animation*. GitHub repository: https://github.com/qiangshen1/XZBaqing_Eqsim

A formal paper citation can be added when the related study becomes available. No separate reuse license is specified here; permission for redistribution or derivatives should not be assumed solely from public GitHub access.

---

**Project page:** https://github.com/qiangshen1/XZBaqing_Eqsim  
**Researcher's homepage:** https://qiangshen1.github.io/
