# Awesome-3D-Scene-Design-Virtual-Photography

## Top 3D Scene Design & Virtual Photography Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Virtual Camera Control, In-Game Photography & Self-Hosted Rendering Pipelines*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Scene Design & Virtual Photography**. These tools help artists, designers, and virtual photographers compose 3D scenes, control virtual cameras, and produce photorealistic stills or cinematic captures—ranging from dedicated staging and rendering suites to in-game photo mode frameworks and open-source renderers.



**Examples** include Adobe Substance 3D Stager, KeyShot, Marmoset Toolbag, Blender, Cinema 4D, V-Ray, Autodesk VRED, Lumion, Maxwell Render, and CADRays (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription fees, and controlling the virtual camera pipeline. The open-source landscape is anchored by **Blender** (the complete free suite with Cycles/EEVEE and depth-of-field camera simulation), with **CADRays** offering GPU-accelerated photorealistic rendering, and specialized virtual photography tools like **Director's Suite** and **PhotoMode (Unity)** enabling in-game camera control and capture.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global 3D rendering and visualization software market is estimated at **$4.3B to $8.2B**, expanding rapidly at a 13–21% CAGR fueled by real-time rendering, virtual production, and digital twins. The sector exhibits **moderate fragmentation**: while mega-cap software conglomerates (Adobe, Autodesk, Dassault Systèmes) dominate enterprise CAD, DCC, and authoring pipelines, independent engines and visualization specialists (Chaos, Luxion, Maxon) alongside mature open-source tools (Blender) maintain strong competitive footholds across niche verticals.

## SaaS/Hosted Platforms

| Product | Company Valuation / Revenue | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Substance 3D Stager](https://www.adobe.com/products/substance3d/apps/stager.html)** | **~$190B+ Market Cap** (~$21.5B Rev) | Scene assembly and virtual photography studio with lighting, materials, and camera controls. | **$49.99/mo** (billed annually at $599.88/yr) or **$59.99/mo** (month-to-month) for Substance 3D Collection; **$100/mo/seat** for Teams. | **30-day free trial** with full access to the Substance 3D Collection apps and 30 asset downloads/month. No permanent free tier. |
| **[Autodesk VRED](https://www.autodesk.com/products/vred/)** | **~$55B Market Cap** (~$5.5B Rev) | Automotive and product visualization software with advanced virtual camera and staging tools. | **$465/month** or **$3,730/year** (VRED Design single-user subscription); **~$7,117/year** (VRED Core). | **30-day free trial** of full functionality for non-commercial evaluation only (no extensions). No permanent free tier. |
| **[Cinema 4D](https://www.maxon.net/)** | **~$1.05B (€995M Rev)** *(Parent: Nemetschek)* | Professional 3D suite with Redshift GPU renderer, camera tools, and scene staging. | **$69.91/month** (billed annually at $839/yr) or **$109/month** (month-to-month); includes integrated Redshift and 5 Team Render nodes. | **14-day free trial** via Maxon App with full commercial toolset access. No permanent free tier. |
| **[KeyShot](https://www.keyshot.com/)** | **~$150M+ Valuation** (~$25M ARR, Luxion) | Real-time ray tracing renderer with camera, lighting, and material controls for product visualization. | **$108.25/month** (billed annually at $1,299/yr, KeyShot Studio Pro); **$133.25/month** ($1,599/yr, Studio Business). | **14-day free trial** of KeyShot Studio, restricted to 1 trial per machine per year; file saving and render queues disabled, outputs watermarked. No permanent free tier. |
| **[V-Ray (Chaos)](https://www.chaos.com/)** | **~$130M+ Est. ARR** *(PE: TA Associates)* | Industry-standard photorealistic renderer with physical camera controls (f-stop, shutter, ISO). | **$44.90/month** (billed annually at $538.80/yr) or **$84.90/month** (V-Ray Solo); **$62.90/mo** ($754.80/yr) for Premium. | **30-day free trial** with full access to Chaos Cloud and all V-Ray integrations. No permanent free tier. |
| **[Lumion](https://lumion.com/)** | **~€25M ARR** *(PE: Seven2 / Act-3D)* | Architectural rendering software with real-time visualization, camera effects, and a large asset library. | **$96/month** (billed annually at $1,149/yr, Pro Named-user); **$125/month** ($1,499/yr, Pro Floating). | **14-day free trial** (Lumion Pro Trial) with full feature access and reduced content library size, limited to 1 trial per PC. No permanent free tier. |
| **[Maxwell Render (Next Limit)](https://www.nextlimit.com/)** | **~$15M–$20M Est. Rev** *(Next Limit)* | Physically based renderer known for unbiased, photorealistic output and physical camera model. | **$995** one-time perpetual license (Standard node-locked); **$245** per additional Render Node. | **30-day demo trial** with node-locked license; exports watermarked and output resolution capped at 1280x1024. No permanent free tier. |
| **[Marmoset Toolbag](https://marmoset.co/)** | **~$2M–$3M Est. Rev** *(Marmoset LLC)* | Real-time rendering suite with camera, lighting, and presentation tools for virtual photography. | **$18.99/month** (monthly subscription) or **$399** one-time perpetual license for Individuals; **$49.99/mo/seat** or **$1,299** perpetual for Studios. | **30-day free trial** for personal evaluation (1 trial per user) with full rendering capabilities. No permanent free tier. |



## Open-Source GitHub Projects



- **[Blender](https://github.com/blender/blender)** [![GitHub Stars](https://img.shields.io/github/stars/blender/blender?style=social&color=white)](https://github.com/blender/blender/stargazers)  

  **The complete open-source 3D suite with professional virtual camera tools.** **Fully free, no feature restrictions.** Includes **Cycles** (path-traced photorealistic renderer) and **EEVEE** (real-time rasterizer with **Depth of Field** simulation using f-stop, bokeh shape, and focus distance controls) . **Strengths**: physical camera model with f-stop, shutter, and ISO; bokeh shape control (disk through octagon); post-process and sample-based DOF methods; capable of professional virtual photography . **Trade-offs**: steeper learning curve than dedicated staging tools; requires scene setup. Best for virtual photographers wanting a complete, free alternative to Cinema 4D or KeyShot with full camera control.



- **[CADRays](https://github.com/Open-Cascade-SAS/CADRays)** [![GitHub Stars](https://img.shields.io/github/stars/Open-Cascade-SAS/CADRays?style=social&color=white)](https://github.com/Open-Cascade-SAS/CADRays/stargazers)  

  **The GPU-accelerated photorealistic renderer for CAD and product visualization.** MIT licensed. Based on Open CASCADE Technology (OCCT), it uses **GPU path tracing** with progressive rendering—the viewport is the final render, providing immediate feedback for adjusting materials, lights, and camera . **Features**: physical camera model (perspective and orthographic), double-layered material system, STEP/IGES/BREP/OBJ/PLY/STL import . **Strengths**: runs on AMD, NVIDIA, and integrated Intel GPUs; interactive frame rates during scene setup. Best for product designers and engineers wanting photorealistic virtual photography of CAD models without commercial rendering licenses.



- **[Director's Suite (RDR2)](https://github.com/videotechuk/DirectorsSuite)** [![GitHub Stars](https://img.shields.io/github/stars/videotechuk/DirectorsSuite?style=social&color=white)](https://github.com/videotechuk/DirectorsSuite/stargazers)  

  **The in-game virtual photography and scene editor for Red Dead Redemption 2.** Full **Photo Mode** with tabs for Camera, World, Character, Lighting, Post, Effects, and Scene Editor . **Features**: free-fly/orbit camera, **real DOF**, time & weather control, 38 photo filters, lossless/HDR screenshots, **super-resolution capture**, up to 300 cameras with modes and transitions . **Scene Editor (Beta)**: place ~16,950 prop archetypes and spawn ~1,980 ped models with validated scenarios . Best for virtual photographers and cinematics creators working within RDR2 who want a full camera and scene control suite.



- **[PhotoMode (Unity)](https://github.com/timskapp/PhotoMode)**   

  **The virtual photography system for Unity projects.** Open-source framework for creating in-game screenshots and photographic effects—free-fly camera, depth of field, filters, and composition guides . **Status**: community forks have added Unity 6 and latest Cinemachine support (some effects still in progress) . Best for Unity developers wanting to add a photo mode to their games without building camera and capture systems from scratch.



### Additional Strong Open-Source Options



- **Mitsuba** — Physically based renderer with a research-grade physical camera model. GPL-3.0 licensed. Best for researchers and technical artists needing an academically rigorous renderer with full camera simulation .

- **LuxCoreRender** — Unbiased physically based renderer with Blender integration. Best for photorealistic virtual photography with a free, open-source engine .

- **ArmorPaint** — Open-source PBR texture painting suite (now at 1.0 with ray tracing support). Best for texturing assets destined for Blender or CADRays virtual photography scenes .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Blender is the only fully featured, permanently free option in this category**: no feature restrictions, professional camera controls (f-stop, bokeh, DOF), and capable of production-quality virtual photography . Dedicated tools like Stager and KeyShot offer faster workflows but require ongoing payment.

- **Virtual photography is a distinct discipline**: dedicated tools like Director's Suite and PhotoMode focus on in-game camera control and capture, while Blender and CADRays focus on rendering from-scratch scenes. Choose based on whether you're photographing existing game worlds or composing new scenes.

- **SaaS pricing is per-seat and annualized**: KeyShot at $1,299/year, Cinema 4D at €859.77/year, and VRED at $3,730/year represent ongoing commitments. Model your usage before committing.

- **Maxwell Render's pricing is from legacy documentation**: the $995 standard license figure is from Next Limit's wiki, which may not reflect current promotions or regional pricing. Verify on the official site before purchasing .



---



**Made for virtual photographers, 3D artists, product designers, and visualization specialists.**  

Let's make 3D scene design and virtual photography more open, camera-aware, and accessible.
