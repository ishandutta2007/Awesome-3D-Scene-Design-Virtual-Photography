# Awesome-3D-Scene-Design-Virtual-Photography

# Top 3D Scene Design & Virtual Photography Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Virtual Camera Control, In-Game Photography & Self-Hosted Rendering Pipelines*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Scene Design & Virtual Photography**. These tools help artists, designers, and virtual photographers compose 3D scenes, control virtual cameras, and produce photorealistic stills or cinematic captures—ranging from dedicated staging and rendering suites to in-game photo mode frameworks and open-source renderers.

**Examples** include Adobe Substance 3D Stager, KeyShot, Marmoset Toolbag, Blender, Cinema 4D, V-Ray, Autodesk VRED, Lumion, Maxwell Render, and CADRays (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription fees, and controlling the virtual camera pipeline. The open-source landscape is anchored by **Blender** (the complete free suite with Cycles/EEVEE and depth-of-field camera simulation), with **CADRays** offering GPU-accelerated photorealistic rendering, and specialized virtual photography tools like **Director's Suite** and **PhotoMode (Unity)** enabling in-game camera control and capture.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Adobe Substance 3D Stager](https://www.adobe.com/products/substance3d/apps/stager.html)** | Scene assembly and virtual photography studio with lighting, materials, and camera controls. | **Substance 3D Collection**: **S$80.41/mo** (incl. GST) for individuals; **S$167/mo** per license for teams (excl. GST, annual billed monthly) . | **30-day free trial** of the full Collection. No permanent free tier. |
| **[KeyShot](https://www.keyshot.com/)** | Real-time ray tracing renderer with camera, lighting, and material controls for product visualization. | **Professional**: **$108.25/month** (billed annually at $1,299). **Business**: **$133.25/month** ($1,599/year) for seat management . | No free tier. Free trial available. |
| **[Marmoset Toolbag](https://marmoset.co/)** | Real-time rendering suite with camera, lighting, and presentation tools for virtual photography. | **Perpetual** or **Subscription** licenses. **Individual perpetual** available; Studio and Academic tiers eligible for volume discounts (5–15% off for 5+ seats) . | **30-day free trial** for personal evaluation (one per individual) . No permanent free tier. |
| **[Cinema 4D](https://www.maxon.net/)** | Professional 3D suite with Redshift GPU renderer, camera tools, and scene staging. | **€859.77/year** per license (billed annually), includes Redshift and 5 Team Render nodes . | **14-day free trial** via Maxon App. No permanent free tier. |
| **[V-Ray (Chaos)](https://www.chaos.com/)** | Industry-standard photorealistic renderer with physical camera controls (f-stop, shutter, ISO). | **V-Ray Solo**: **$540/year**. **Premium**: **$718.80/year**. **ArchViz Collection**: **$838.80/year** . | **30-day free trial** available . No permanent free tier. |
| **[Autodesk VRED](https://www.autodesk.com/products/vred/)** | Automotive and product visualization software with advanced virtual camera and staging tools. | **VRED Design**: **$465/month** or **$3,730/year** . **VRED Core** (renewal): ~**$7,117/year** . | No free tier. Trial available via Autodesk. |
| **[Lumion](https://lumion.com/)** | Architectural rendering software with real-time visualization, camera effects, and a large asset library. | **Pro (Named-user)**: **$96/month** ($1,149/year). **Pro Floating**: **$125/month** ($1,499/year) . | No free tier. **14-day refund** window. Free onboarding session included . |
| **[Maxwell Render (Next Limit)](https://www.nextlimit.com/)** | Physically based renderer known for unbiased, photorealistic output and physical camera model. | **Standard License**: **$995** (new purchase). **Render Node**: **$245** each . | No free tier. Educational licenses available at **$170** . |

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
