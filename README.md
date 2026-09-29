# Awesome Motion Graphics & Motion Animation

> A curated, practical catalog of tools, libraries, courses, communities, assets, and references for motion designers, animators, and the developers who ship their work.

Motion graphics is the craft of giving **still design a timeline**. This list covers the whole pipeline: principles and theory, 2D/3D authoring tools, real-time engines, code-driven animation, plugins and scripts, color and finishing, delivery formats, learning resources, communities, and career paths.

Everything here is hand-picked, actively maintained, and free or has a meaningful free tier unless noted. Prices and features move fast — verify anything you'll pay for.

---

## Contents

- [Fundamentals and Theory](#fundamentals-and-theory)
  - [Core Principles](#core-principles)
  - [Easing, Timing, and Feel](#easing-timing-and-feel)
  - [Essentials Books](#essentials-books)
- [2D Motion Design Software](#2d-motion-design-software)
- [3D and CG Software](#3d-and-cg-software)
- [Web and Interactive Animation](#web-and-interactive-animation)
  - [Runtime Formats](#runtime-formats)
  - [JS Libraries](#js-libraries)
  - [3D on the Web](#3d-on-the-web)
  - [Browser-Based Authoring Tools](#browser-based-authoring-tools)
  - [No-Code and Webflow](#no-code-and-webflow)
- [Real-Time and Game Engines](#real-time-and-game-engines)
- [Scripting, Procedural, and Code-Driven Animation](#scripting-procedural-and-code-driven-animation)
- [Open Source and GitHub Repos](#open-source-and-github-repos)
  - [Lottie and dotLottie Runtimes](#lottie-and-dotlottie-runtimes)
  - [Rive Runtimes](#rive-runtimes)
  - [Animation and Tweening Libraries](#animation-and-tweening-libraries)
  - [Scroll and Page Transition Libraries](#scroll-and-page-transition-libraries)
  - [3D Web Runtimes and Toolchains](#3d-web-runtimes-and-toolchains)
  - [Physics, Easing, and Procedural Utilities](#physics-easing-and-procedural-utilities)
  - [Generative Art, Shaders, and Audio Tools](#generative-art-shaders-and-audio-tools)
  - [Text, Fonts, and Type](#text-fonts-and-type)
  - [Video, Encoding, and Analysis](#video-encoding-and-analysis)
  - [Programmatic Video](#programmatic-video)
  - [3D Pipelines, Interchange, and Color Standards](#3d-pipelines-interchange-and-color-standards)
  - [Engines, DCC Source, and Installations](#engines-dcc-source-and-installations)
  - [AI and Generative Video Models](#ai-and-generative-video-models)
  - [Topic Pages and Organizations to Explore](#topic-pages-and-organizations-to-explore)
- [After Effects Plugins and Scripts](#after-effects-plugins-and-scripts)
- [Tracking, Cleanup, and VFX Tools](#tracking-cleanup-and-vfx-tools)
- [Renderers, Compositors, and Finish](#renderers-compositors-and-finish)
- [Color Grading and LUTs](#color-grading-and-luts)
- [Typography and Fonts](#typography-and-fonts)
- [Audio, Music, and Beat Sync](#audio-music-and-beat-sync)
- [Stocks, Templates, and Assets](#stocks-templates-and-assets)
- [Delivery, Codecs, and File Formats](#delivery-codecs-and-file-formats)
- [UI and Product Motion Systems](#ui-and-product-motion-systems)
- [Real-Time Control and Output Protocols](#real-time-control-and-output-protocols)
- [Production Pipeline, Review, and Dailies](#production-pipeline-review-and-dailies)
- [AI Tools for Motion](#ai-tools-for-motion)
- [Specifications, Standards, and Deliverables](#specifications-standards-and-deliverables)
- [Awards, Conferences, and Archives](#awards-conferences-and-archives)
- [Performance and Accessibility](#performance-and-accessibility)
- [Learning: Courses and Schools](#learning-courses-and-schools)
- [Free Courses](#free-courses)
- [YouTube Channels](#youtube-channels)
- [Newsletters, Blogs, and Publications](#newsletters-blogs-and-publications)
- [Inspiration and Showreels](#inspiration-and-showreels)
- [Communities and Forums](#communities-and-forums)
- [Portfolios, Freelance, and Jobs](#portfolios-freelance-and-jobs)
- [Glossary](#glossary)
- [How to Contribute](#how-to-contribute)

---

## Fundamentals and Theory

### Core Principles

The [12 Principles of Animation](https://en.wikipedia.org/wiki/12_principles_of_animation) (Frank Thomas & Ollie Johnston, *The Illusion of Life*, 1981) still drive almost every decision you make on a timeline:

| Principle | One-line takeaway |
| --- | --- |
| Squash and stretch | Volume is preserved — deformation sells the material. |
| Anticipation | Motion needs a wind-up or it reads as teleporting. |
| Staging | One idea per frame; direct the eye. |
| Straight ahead / pose to pose | Flow vs. control — pick deliberately. |
| Follow through and overlapping | Secondary motion = life. |
| Slow in, slow out | Ease at the extremes, linear in the middle. |
| Arc | Natural movement follows curves. |
| Secondary action | Supporting motion enriches the main move. |
| Timing | The number of frames *is* the emotion. |
| Exaggeration | Push past reality or nobody feels it. |
| Solid drawing | Weight, volume, consistent perspective. |
| Appeal | Charm lives in the silhouette and the read. |

Where to internalize them: [animatoronsurvival.com](http://www.animatoronsurvival.com/) (Richard Williams' notes), the [12 Principles breakdown](https://en.wikipedia.org/wiki/12_principles_of_animation), and Dan Roark's *The Animator's Survival Kit* companion material.

Adjacent disciplines worth stealing from: choreography and blocking (dance timing), UI micro-interactions (state transitions), physics simulation (weight and momentum), and cinematography (camera language, focal length, depth of field).

### Easing, Timing, and Feel

- [easings.net](https://easings.net/) — visual comparison of every standard easing curve (cubic-bezier cheat sheet).
- [cubic-bezier.com](https://cubic-bezier.com/) — build curves by dragging, copy CSS `cubic-bezier()` values.
- [Motion Easing Functions (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/easing-function) — spec reference for `linear`, `ease`, `steps()`, spring(), and friends.
- **Rule of thumb:** animation timing by distance. Short moves (100–300 px) take 150–250 ms; large moves (600 px+) take 350–500 ms. UI never exceeds ~400 ms. Overlapping elements stagger by 30–80 ms.
- **Spring physics > bezier** for anything interruptible or gesture-driven; use bezier for scripted, repeatable beats.

### Essentials Books

- *The Animator's Survival Kit* — Richard Williams. The foundation. Frame-count tables for walk, run, weight.
- *The Illusion of Life: Disney Animation* — Frank Thomas, Ollie Johnston. The canonical principles book.
- *Timing for Animation* — Harold Whitaker & John Halas. Pure timing craft.
- *Cartoon Animation* — Preston Blair. Classic, still-valid pose and volume intuition.
- *Design Basics* — David Lacheray (Motion Design School founder). Typography-first motion thinking.
- *The Animator's Workbook* — Tony White. Exercise-driven, excellent for drilling fundamentals.

---

## 2D Motion Design Software

| Tool | Best for | Notes |
| --- | --- | --- |
| [After Effects](https://www.adobe.com/products/aftereffects.html) | The industry standard: broadcast GFX, VFX, compositing, logo animation | Adobe kills your render farm on multicam timelines; learn [Multi-Frame Rendering](https://helpx.adobe.com/after-effects/using/multi-frame-rendering.html) and Sentinel |
| [Cavalry](https://www.cavalry.tools/) | Procedural 2D, data-driven infographics, scale work | Vector + parametric animation system, scriptable, plays nicely with Figma assets |
| [Apple Motion](https://www.apple.com/motion/) | Motion graphics on a budget | Good 3D + particle + replicator tools; FCP integration |
| [Apple Final Cut Pro](https://www.apple.com/final-cut-pro/) | Edit-first motion work | Motion titles + the free [Motion Templates](https://support.apple.com/en-us/HT201065) ecosystem |
| [Adobe Animate](https://www.adobe.com/products/animate.html) | Vector/Bones character animation | Formerly Flash; best-in-class inverse kinematics for rigged vector characters |
| [Toon Boom Harmony](https://www.toonboom.com/products/harmony) | Professional 2D character pipelines | Broadcast and feature-grade; steep price, steep learning |
| [Adobe Illustrator](https://www.adobe.com/products/illustrator.html) | Source vectors, variable-font glyph animation | Watch the [Variable Fonts in Illustrator](https://helpx.adobe.com/illustrator/using/variable-fonts.html) docs |
| [Figma](https://www.figma.com/) | Prototyping motion, design-to-code handoff | Animate here, then rebuild in a real tool; Figma→Lottie/Rive bridges exist |
| [Photoshop](https://www.adobe.com/products/photoshop.html) | Painterly frames, rotoscoping, matte painting | Frame-by-frame source material |
| [Krita](https://krita.org/) | Free frame-by-frame painting | Great for hand-drawn animation; Krita is open source |
| [OpenToonz](https://opentoonz.org/) | Free 2D animation suite | Used on Studio Ghibli films; rigging + compositing included |
| [Tahoma2D](https://tahoma2d.org/) | Free 2D pipeline tool | MDI, columns, clean ops |
| [Natron](https://natrongithub.github.io/) | Free open-source compositor | Node-based; Nuke/Flame-style; AE-ish tracking built in |
| [Silhouette](https://www.silhouette-interact.com/) | Node-based rotoscoping | Bought by Boris FX; roto-first, not a general compositor |

---

## 3D and CG Software

### Modeling, Animation, and Rendering

| Tool | Best for | Notes |
| --- | --- | --- |
| [Blender](https://www.blender.org/) | Free all-in-one 3D: modeling, rigging, animation, sim, render | The single best free tool in this list; grease pencil + geometry nodes for motion designers |
| [Cinema 4D](https://www.maxon.net/cinema-4d) | Broadcast-standard 3D mograph, MoGraph system | Built-in cloner/mocha/cloner matrix; huge template culture |
| [Maya](https://www.autodesk.com/products/maya/) | Feature film, rigging, character animation | Industry standard in film/game pipelines |
| [Houdini](https://www.sidefx.com/products/houdini/) | Procedural everything, FX, simulations | Steepest learning curve here; procedural lifeline for power users |
| [Cavalry 3D](https://www.cavalry.tools/) | 2.5D vector 3D, quick brand layouts | Bridges the 2D/3D gap for identity work |
| [Unreal Engine](https://www.unrealengine.com/) | Real-time GFX, virtual production, broadcast | Sequencer + Motion Design panel; real-time rendering means faster iteration |
| [Spline](https://spline.design/) | Web-native 3D, interactive 3D for the browser | Design + export to glTF/HTML; pairs with React Three Fiber |
| [Substance 3D](https://www.adobe.com/products/substance3d.html) | Texturing, procedural materials | Painter, Designer, Stager |
| [ZBrush](https://www.maxon.net/zbrush) | Digital sculpting, character heads | Pixologic-style sculpting |
| [Marvelous Designer](https://www.marvelousdesigner.com/) | Cloth simulation and costume design | Cloth sim for animation and look-dev |
| [Modo](https://www.foundation3d.com/products/modo) | Modeler with a clean animation/render pipeline | Foundry-owned; used heavily for product viz |
| [Rhino](https://www.rhino3d.com/) | Precision NURBS, product and logo geometry | Excellent logo-to-3D pipelines |
| [Plasticity](https://plasticity.io/) | Sculpting/voxel modeling for concept and blockout | Modern AltTab-era modeling feel |

### Character Animation and Rigging

- [Rigify](https://developer.blender.org/docs/features/animation/rigify/) — Blender's automatic humanoid rig.
- [Auto-Rig Pro](https://www.lucky3d.fr/auto-rig-pro/) — Blender add-on for production-quality rigs.
- [Mixamo](https://www.mixamo.com/) — free auto-rigging and mocap clips (Adobe account required).
- [Rokoko](https://www.rokoko.com/) — mocap suits, phone video mocap, and a Rokoko Studio retarget workflow.
- [DeepMotion](https://www.deepmotion.com/) — video-to-mocap AI with good retargeting into Blender.
- [Cascadeur](https://cascadeur.com/) — physically plausible assisted animation.
- [MotionBuilder](https://www.autodesk.com/products/motionbuilder/) — character and facial animation.
- [Rigs > Reallusion](https://www.reallusion.com/) — Cartoon Animator, iClone; strong character tools.

---

## Web and Interactive Animation

### Runtime Formats

| Format | Use when | Tools |
| --- | --- | --- |
| [Lottie JSON](https://airbnb.io/lottie/) | Vector UI motion: loaders, empty states, icon motion | [bodymovin](https://github.com/bodymovin/bodymovin) (AE export), [lottie-web](https://github.com/airbnb/lottie-web), [lottie-react](https://github.com/LottieFiles/lottie-react) |
| [dotLottie](https://dotlottie.com/) | Lottie plus theming, expressions, state machines, smaller files | [dotLottie docs](https://dotlottie.com/), Lottie Creator |
| [Rive (.riv)](https://rive.app/) | Stateful, interactive, data-bound UI and game animation | [Rive Editor](https://rive.app/), runtimes for web/iOS/Android/Flutter/Unity/Unreal |
| [Animated SVG](https://developer.mozilla.org/en-US/docs/Web/SVG) | Small icon/illustration motion, zero runtime | SVGator, Lottie Creator, plain CSS/SMIL |
| [glTF / GLB](https://www.khronos.org/gltf/) | 3D assets and animated 3D on the web | Blender, Spline, Three.js, modelviewer.dev |
| [AVIF / WebP sequences](https://developers.google.com/speed/webp) | Video-like quality where vector isn't enough | AVIF (`avifenc`), WebP animated |
| Rive + Lottie | Pick by *interaction*, not by file size | Lottie = playback; Rive = state machines, data binding, runtime scripting |

Export/authoring playgrounds: [Lottie Creator](https://creator.lottiefiles.com/), [LottieFiles](https://lottiefiles.com/), [dotLottie Gallery](https://gallery.dotlottie.com/), [Rive Community](https://rive.app/community/files).

### JS Libraries

**General purpose**
- [GSAP](https://gsap.com/) — the industry default for timeline animation on the web. ScrollTrigger, Flip, SplitText (now free under the GreenSock license). Source: [greensock/GSAP](https://github.com/greensock/GSAP).
- [Motion](https://motion.dev/) (formerly Framer Motion / Motion One) — the ergonomic option for React and vanilla. Declarative, tiny, great springs. Source: [motiondivision/motion](https://github.com/motiondivision/motion).
- [anime.js](https://animejs.com/) — lightweight, timeline-first, v4 rewritten from scratch. Source: [juliangarnier/anime](https://github.com/juliangarnier/anime).
- [Popmotion](https://popmotion.io/) — the animation primitives Motion was built on.
- [Tween.js](https://tweenjs.github.io/tween.js/) — small, classic tween engine.
- [Vite + Motion + GSAP template](https://vitejs.dev/) — build tooling that plays nicely with all of the above.

**Scroll and page transitions**
- [Lenis](https://github.com/darkroomengineering/lenis) — the smooth-scroll baseline; pairs with ScrollTrigger.
- [GSAP ScrollTrigger](https://gsap.com/docs/v3/Plugins/ScrollTrigger/) — scrub, pin, snap, timeline-driven scroll scenes.
- [Locomotive Scroll](https://github.com/locomotivemtl/locomotive-scroll) — declarative scroll with smoothing and pinning.
- [Barba](https://barba.js.org/) — DOM transitions between pages while preserving JS state.
- [LottieFiles Player](https://github.com/LottieFiles/lottie-player) — custom element for Lottie with minimal config.
- [Aceternity UI](https://ui.aceternity.com/components) — copy-paste motion UI blocks; excellent for pattern reference.

**SVG, paths, and text**
- [SVG.js](https://svgjs.dev/) — animate SVG attributes cleanly.
- [D3](https://d3js.org/) — data-driven visuals and transitions.
- [Splitting](https://splitting.dev/) / [GSAP SplitText](https://gsap.com/docs/v3/Plugins/SplitText/) — split text into animatable spans.
- [Flubber](https://github.com/veltman/flubber) — smooth shape interpolation between two paths.
- [Rough.js](https://roughjs.com/) — sketchy animated vector lines.
- [P5.js](https://p5js.org/) — generative art and sketch-based animation.
- [Matter.js](https://brm.io/matter-js/) / [Planck.js](https://piqnt.com/planck.js/) — 2D physics for real-feeling secondary motion.
- [Popmotion + Canvas](https://popmotion.io/) — programmatic motion for generative work.

### 3D on the Web

- [Three.js](https://threejs.org/) — the foundation. Huge ecosystem, endless examples. Source: [mrdoob/three.js](https://github.com/mrdoob/three.js).
- [react-three-fiber](https://github.com/pmndrs/react-three-fiber) + [drei](https://github.com/pmndrs/drei) — React renderer and helpers for Three.js; the most productive way to build 3D interfaces.
- [Babylon.js](https://www.babylonjs.com/) — full engine with physics, GUI, and WebGPU support.
- [GLSL Sandbox](https://glslsandbox.com/) / [ShaderToy](https://www.shadertoy.com/) — shader animation playgrounds.
- [Tweakpane](https://tweakpane.org/) — parameter UI for live tuning; the missing piece in most demos.
- [modelviewer.dev](https://modelviewer.dev/) — one-line `<model-viewer>` web component for GLB assets.
- [Spline](https://spline.design/) — design 3D in the browser, embed the result.
- [OGL](https://oframe.github.io/ogl/) — minimal WebGL library for shader-driven motion.

### Browser-Based Authoring Tools

- [SVGator](https://www.svgator.com/) — browser timeline, exports animated SVG/Lottie/GIF/MP4.
- [Jitter](https://jitter.com/) — fast browser motion design with Lottie export; no install.
- [Lottie Creator](https://creator.lottiefiles.com/) — the most capable free browser tool for Lottie/dotLottie, including state machines.
- [LottieLab](https://lottielab.com/) — visual Lottie editing and team handoff.
- [Rive Editor](https://rive.app/) — interactive graphics with state machines, data binding, and scripting.
- [Adobe Express](https://express.adobe.com/) — quick social/brand motion without a timeline.
- [Canva](https://www.canva.com/) — bulk social motion and template-driven video.
- [Kapwing](https://www.kapwing.com/) — web editing, captions, resizing for social.

### No-Code and Webflow

- [Unicorn Studio](https://www.unicorn.studio/) — 3D + interaction scenes embedded anywhere with no code.
- [Webflow](https://webflow.com/) — native interactions, scroll effects, and Rive/Gsap embeds.
- [Framer](https://www.framer.com/) — Motion built in; ship marketing sites with real motion.
- [Spline + Webflow](https://spline.design/) — 3D scenes inside a Webflow page.
- [No Code Supply Co](https://www.nocodesupply.co/) — a huge, well-curated index of no-code animation tools, snippets, and inspiration.
- [Awwwards](https://www.awwwards.com/) and [Godly](https://godly.website/) — judge interaction quality by example.

---

## Real-Time and Game Engines

- [Unreal Engine](https://www.unrealengine.com/) — Unreal has first-class *motion design* features: the Motion Design panel, Composure Sequencer, live GFX, and nDisplay walls for broadcast. Also the cheapest way to iterate on 3D motion.
- [Unity](https://unity.com/) — Timeline, Cinemachine, and Shader Graph for real-time sequences.
- [Godot](https://godotengine.org/) — free, open source, lighter than Unity for real-time work.
- [Webflow Interactions](https://webflow.com/) — a browser-native "engine" for scroll and hover motion.
- [TouchDesigner](https://derivative.ca/) — node-based real-time visuals, projection mapping, and installation work.
- [Notch](https://www.notch.one/) — real-time 3D for live events and broadcast.
- [Disguise](https://www.disguise.one/) — media server driving real-time stage and LED work.
- [Cavalry](https://www.cavalry.tools/) — see 2D section; it functions like a tiny motion engine.

---

## Scripting, Procedural, and Code-Driven Animation

**After Effects scripting**
- [Scripting Guide for After Effects](https://ae-scripting.docsforadobe.dev/) — the community-maintained, genuinely excellent reference.
- [ExtendScript](https://extendscript.docsforadobe.dev/) — the language itself; ES3-ish, no modules, always fun.
- [aerender](https://helpx.adobe.com/after-effects/using/command-line-rendering.html) — batch render from the command line; essential for render farms and CI.
- [Expressions](https://ae-expressions.docsforadobe.dev/) — the docs for AE's expression engine; `wiggle`, `loopOut`, `linear()`.
- Recommended: [aescripts](https://aescripts.com/) (code-based tools), [AEJuice](https://aejuice.com/) (free plugin/script index), [Creative COW forums](https://forums.creativecow.net/) for troubleshooting.

**Python for animation**
- [Blender Python API](https://docs.blender.org/api/current/) — procedural modeling, animation, rendering from scripts.
- [bpy](https://pypi.org/project/bpy/) — pip-installable Blender as a Python module; pipeline automation.
- [Manim](https://www.manim.community/) — programmatic math and technical animation, used for lectures and explainers.
- [moviepy](https://zulko.github.io/moviepy/) — Python video editing and compositing.
- [decord](https://github.com/dmlc/decord) / [PyAV](https://pyav.org/) — fast video reading for ML and frame pipelines.

**Programmatic video**
- [Remotion](https://www.remotion.dev/) — React components that render to video; version-controlled, data-driven motion.
- [FFmpeg](https://ffmpeg.org/) — the Swiss army knife for encoding, scaling, trimming, frame extraction.
- [Motion Canvas](https://motioncanvas.io/) — TypeScript-based programmatic animation for video and the web; a Motion+Remotion hybrid. Underrated.

**Procedural pipelines**
- [Geometry Nodes](https://docs.blender.org/manual/en/latest/modeling/geometry_nodes/index.html) — Blender's node-based modeling/scatter/simulation system.
- [Gaea](https://helpx.adobe.com/gaea/gaea.html) — procedural terrain for large environment motion.
- [Houdini Engine](https://www.sidefx.com/products/houdini-engine/) — run Houdini sims inside Maya, Blender, or Unity.

---

## Open Source and GitHub Repos

Everything in this section was verified to exist at the time of writing. Motion work is unusually well served by open source: the render formats, the web runtimes, the video tooling, and the interchange specs are all open, which means you can read the source of the thing that is rendering your animation.

A caveat worth internalizing: **check the license before shipping**. MIT/BSD/Apache are fine commercially; GPL and AGPL impose obligations; the Blender, OpenUSD, OpenEXR, OpenTimelineIO, and OCF ecosystems are mostly Apache-2.0/MIT but individual add-ons vary.

### Lottie and dotLottie Runtimes

- [airbnb/lottie-web](https://github.com/airbnb/lottie-web) — the reference web player. Read its renderer source when a Lottie will not play correctly in Safari or on a low-end Android.
- [bodymovin/bodymovin](https://github.com/bodymovin/bodymovin) — the After Effects exporter itself, including the SVG/canvas renderer path and the feature-support matrix that explains what will and will not export.
- [LottieFiles/lottie-react](https://github.com/LottieFiles/lottie-react) — the React wrapper most products use.
- [LottieFiles/lottie-player](https://github.com/LottieFiles/lottie-player) — a web component: drop `<lottie-player>` on a page with no build step.
- [LottieFiles/dotlottie-web](https://github.com/LottieFiles/dotlottie-web) — the dotLottie WASM player with theming, expressions, and state machines.
- [airbnb/lottie-ios](https://github.com/airbnb/lottie-ios) and [airbnb/lottie-android](https://github.com/airbnb/lottie-android) — native runtimes; the Android one has the best docs on choosing a render mode per device.

### Rive Runtimes

- [rive-app/rive-wasm](https://github.com/rive-app/rive-wasm) — the web runtime; where you will look first when a state machine misbehaves.
- [rive-app/rive-react](https://github.com/rive-app/rive-react) — React bindings, including the `useStateMachineInput` hook.
- [rive-app/rive-cpp](https://github.com/rive-app/rive-cpp) — portable C++ runtime, used by the mobile SDKs and Unity.
- [rive-app/rive-flutter](https://github.com/rive-app/rive-flutter) and [rive-app/rive-android](https://github.com/rive-app/rive-android) — platform runtimes.
- [Shopify/react-native-skia](https://github.com/Shopify/react-native-skia) — not a Rive tool, but the strongest alternative for drawing complex animated UI natively.

### Animation and Tweening Libraries

- [greensock/GSAP](https://github.com/greensock/GSAP) — the workhorse. Read the internals of the stagger and the ticker if you ever need to debug frame-timing issues.
- [motiondivision/motion](https://github.com/motiondivision/motion) — Motion One and Framer Motion in one repo; the spring implementation is worth reading.
- [juliangarnier/anime](https://github.com/juliangarnier/anime) — anime.js v4; small, dependency-free, timeline-first.
- [tweenjs/tween.js](https://github.com/tweenjs/tween.js) — the classic, still the right answer for sequencing long chains with callbacks.
- [popmotion/popmotion](https://github.com/popmotion/popmotion) — the animation primitives library Motion grew out of.
- [rough-stuff/rough](https://github.com/rough-stuff/rough) — sketchy animated vector graphics.
- [svgdotjs/svg.js](https://github.com/svgdotjs/svg.js) — small, clean SVG manipulation.
- [animate-css/animate.css](https://github.com/animate-css/animate.css) — named animation utilities; useful as a vocabulary reference even if you never ship it.

### Scroll and Page Transition Libraries

- [darkroomengineering/lenis](https://github.com/darkroomengineering/lenis) — the current smooth-scroll standard; pairs with ScrollTrigger.
- [locomotivemtl/locomotive-scroll](https://github.com/locomotivemtl/locomotive-scroll) — declarative scrolling with smoothing, pinning, and scroll-triggered classes.
- [barbajs/barba](https://github.com/barbajs/barba) — persistent DOM across page transitions so in-page animation state survives navigation.

### 3D Web Runtimes and Toolchains

- [mrdoob/three.js](https://github.com/mrdoob/three.js) — the ecosystem root. The examples directory remains the best free course in WebGL.
- [pmndrs/react-three-fiber](https://github.com/pmndrs/react-three-fiber) — React reconciler for three.js.
- [pmndrs/drei](https://github.com/pmndrs/drei) — the helper library that saves you from rewriting camera, loader, and material utilities.
- [pmndrs/three-stdlib](https://github.com/pmndrs/three-stdlib) — ports of three.js example utilities as maintained modules.
- [pmndrs/cannon-es](https://github.com/pmndrs/cannon-es) and [pmndrs/maath](https://github.com/pmndrs/maath) — physics and easing/curve math helpers from the same maintainers.
- [BabylonJS/Babylon.js](https://github.com/BabylonJS/Babylon.js) — the batteries-included alternative: physics, GUI, XR, and a node material editor in one package.
- [google/model-viewer](https://github.com/google/model-viewer) — a single-element `<model-viewer>` with AR support.
- [gkjohnson/three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) — bounding volume hierarchy acceleration; the difference between 60fps and 6fps on heavy scenes.
- [toji/gl-matrix](https://github.com/toji/gl-matrix) — the matrix and vector math every WebGL library depends on.

### Physics, Easing, and Procedural Utilities

- [liabru/matter-js](https://github.com/liabru/matter-js) — 2D rigid body physics in JavaScript; good for secondary motion and springy UI.
- [piqnt/planck.js](https://github.com/piqnt/planck.js) — a 2D physics port of Box2D; more stable and closer to Box2D semantics.
- [d3/d3-ease](https://github.com/d3/d3-ease) — the reference easing function set, written as small readable source.
- [erich666/GraphicsGems](https://github.com/erich666/GraphicsGems) — the companion code for *Graphics Gems*; includes interpolation, easing, and motion-blur maths that is still directly usable.

### Generative Art, Shaders, and Audio Tools

- [processing/p5.js](https://github.com/processing/p5.js) — the friendly entry point for generative motion and data-driven animation.
- [d3/d3](https://github.com/d3/d3) — data-driven visuals with transitions built in.
- [gka/chroma.js](https://github.com/gka/chroma.js) — color manipulation: scales, gradients, contrast, palettes.
- [Tonejs/Tone.js](https://github.com/Tonejs/Tone.js) — a full Web Audio framework: scheduling, synthesis, and the transport you need for audio-driven animation.
- [goldfire/howler.js](https://github.com/goldfire/howler.js) — lightweight audio playback with a Web Audio path and an HTML5 fallback.
- [katspaugh/wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) — waveform rendering and audio-region scrubbing.
- [MTG/essentia.js](https://github.com/MTG/essentia.js) — real-time audio feature extraction: onset, tempo, spectral analysis. This is how you build beat-reactive visuals in the browser.
- [tonaljs/tonal](https://github.com/tonaljs/tonal) — music theory in JavaScript: chord and key detection, useful for harmonically-aware visual work.

### Text, Fonts, and Type

- [google/fonts](https://github.com/google/fonts) — every Google font, including the variable originals.
- [fonttools/fonttools](https://github.com/fonttools/fonttools) — the Python toolkit for subsetting, renaming, and inspecting font binaries.
- [harfbuzz/harfbuzzjs](https://github.com/harfbuzz/harfbuzzjs) — text shaping compiled to WebAssembly; how browsers handle complex scripts.
- [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) — parse fonts and turn glyph outlines into SVG paths for custom kinetic type.
- [foliojs/fontkit](https://github.com/foliojs/fontkit) — the font engine behind PDFKit and many Node text pipelines.
- [googlefonts/fontbakery](https://github.com/googlefonts/fontbakery) — the linter Google uses to check font quality; useful even if you are not shipping to Google Fonts.

### Video, Encoding, and Analysis

- [FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg) — the reference implementation of essentially every codec you will deliver in.
- [ffmpegwasm/ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm) — FFmpeg compiled to WebAssembly; client-side transcoding and thumbnail extraction.
- [yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp) — the reference tool for pulling reference footage and metadata; check the rights on whatever you download.
- [obsproject/obs-studio](https://github.com/obsproject/obs-studio) — a compositor and mixer you already have; an excellent scratchpad for testing overlays and transitions.
- [PyAV-Org/PyAV](https://github.com/PyAV-Org/PyAV) — Python bindings over FFmpeg; clean frame-accurate decoding and encoding.
- [image-rs/image](https://github.com/image-rs/image) — a fast, safe image codec library for frame sequences.
- [opencv/opencv](https://github.com/opencv/opencv) — optical flow, feature tracking, and background subtraction; the motion-analysis side of computer vision.
- [Breakthrough/PySceneDetect](https://github.com/Breakthrough/PySceneDetect) — automatic shot detection; handy when scrubbing long rushes.

### Programmatic Video

- [remotion-dev/remotion](https://github.com/remotion-dev/remotion) — React components rendered to video. Real production use: templated social video, data-driven report animations, and version-controlled animation.
- [motion-canvas/motion-canvas](https://github.com/motion-canvas/motion-canvas) — TypeScript animation system with a canvas renderer, generative-art roots, and a real-time preview server.
- [ManimCommunity/manim](https://github.com/ManimCommunity/manim) — the Python engine for explanatory and mathematical animation; the LaTeX integration alone is worth the install.
- [Zulko/moviepy](https://github.com/Zulko/moviepy) — Python video editing as code; useful for batch renders and quick prototypes.

### 3D Pipelines, Interchange, and Color Standards

- [AcademySoftwareFoundation/OpenTimelineIO](https://github.com/AcademySoftwareFoundation/OpenTimelineIO) — a vendor-neutral timeline interchange format. Read the spec if you are building any tool that reads or writes a cut.
- [AcademySoftwareFoundation/OpenColorIO](https://github.com/AcademySoftwareFoundation/OpenColorIO) — the color management standard behind most film and commercial pipelines; the ACES-oriented configs are the model to follow.
- [AcademySoftwareFoundation/OpenEXR](https://github.com/AcademySoftwareFoundation/OpenEXR) — high dynamic range image format with deep/half float, tiles, and multi-channel support.
- [AcademySoftwareFoundation/OpenFX](https://github.com/AcademySoftwareFoundation/OpenFX) — the open standard for visual effects plug-in APIs (OFX); relevant if you write plug-ins.
- [AcademySoftwareFoundation/OpenShadingLanguage](https://github.com/AcademySoftwareFoundation/OpenShadingLanguage) — the portable shading language used by several renderers; the compiler and reference implementation live here.
- [PixarAnimationStudios/OpenUSD](https://github.com/PixarAnimationStudios/OpenUSD) — Universal Scene Description, the interchange format for large-scale 3D pipelines.
- [alembic/alembic](https://github.com/alembic/alembic) — geometry cache interchange for simulation and crowd workflows.
- [KhronosGroup/glTF-Sample-Assets](https://github.com/KhronosGroup/glTF-Sample-Assets) — the reference asset library; the fastest way to learn what each glTF feature looks like.
- [KhronosGroup/glTF-Validator](https://github.com/KhronosGroup/glTF-Validator) — validate and diagnose exported GLB files before they reach a client.
- [KhronosGroup/glslang](https://github.com/KhronosGroup/glslang) — reference shader compiler; the validator is the fastest way to debug a broken GLSL file.
- [assimp/assimp](https://github.com/assimp/assimp) — import dozens of mesh and scene formats into one pipeline.

### Engines, DCC Source, and Installations

- [blender/blender](https://github.com/blender/blender) — the full source of the free toolchain; the `scripts/` tree teaches Blender's own add-on conventions.
- [DLR-RM/BlenderProc](https://github.com/DLR-RM/BlenderProc) — procedural dataset and render generation with Blender; used for synthetic training data and large-scale asset generation.
- [NatronGitHub/Natron](https://github.com/NatronGitHub/Natron) — the open-source node compositor, and the reference implementation for the OpenFX standard.
- [godotengine/godot](https://github.com/godotengine/godot) — a free real-time engine; a lighter way to prototype interactive 3D motion than Unreal.
- [EpicGamesExt](https://github.com/EpicGamesExt) — the Unreal marketplace publisher account; filter for Sequencer, GFX, and NDI tools.
- [NVlabs/instant-ngp](https://github.com/NVlabs/instant-ngp) — neural rendering; not everyday motion, but it defines the visual ceiling of real-time.
- [KhronosGroup/OpenXR-SDK](https://github.com/KhronosGroup/OpenXR-SDK) — the standard for motion in XR, and the spec to read when a piece needs to work in a headset.

### AI and Generative Video Models

Treat these as b-roll generators and pre-visualization tools, not as a substitute for animation craft.

- [comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI) — node-based diffusion workflows; the practical way to script image and video generation.
- [lllyasviel/ControlNet](https://github.com/lllyasviel/ControlNet) — condition generation on pose, depth, and line art, which is how you get repeatable character motion.
- [KwaiVGI/LivePortrait](https://github.com/KwaiVGI/LivePortrait) — portrait animation from a single source image and a driving video.
- [Lightricks/LTX-Video](https://github.com/Lightricks/LTX-Video) — open video generation model.
- [Tencent-Hunyuan/HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) — open video generation model.

### Topic Pages and Organizations to Explore

- Topics: [motion-graphics](https://github.com/topics/motion-graphics), [motion-design](https://github.com/topics/motion-design), [after-effects](https://github.com/topics/after-effects), [lottie](https://github.com/topics/lottie), [rive](https://github.com/topics/rive), [gsap](https://github.com/topics/gsap), [threejs](https://github.com/topics/threejs), [webgl](https://github.com/topics/webgl), [shader](https://github.com/topics/shader), [creative-coding](https://github.com/topics/creative-coding), [kinetic-typography](https://github.com/topics/kinetic-typography), [blender](https://github.com/topics/blender).
- Organizations worth watching for commits: [LottieFiles](https://github.com/LottieFiles), [rive-app](https://github.com/rive-app), [greensock](https://github.com/greensock), [motiondivision](https://github.com/motiondivision), [aescripts](https://github.com/aescripts), [AdobeDocs](https://github.com/AdobeDocs), [AE-Community](https://github.com/AE-Community), [ffmpegwasm](https://github.com/ffmpegwasm).
- Browser docs worth reading in full: [MDN Web Animations API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API), [MDN SVG animation with SMIL](https://developer.mozilla.org/en-US/docs/Web/SVG/Guides/SVG_animation_with_SMIL), [web.dev animations guide](https://web.dev/articles/animations-guide).

---

## After Effects Plugins and Scripts

### Free and Near-Free (Install First)

- [Adobe's third-party plugin list](https://helpx.adobe.com/after-effects/using/plug-ins.html) — the official, MFR-compatible plugins (FXFactory pack, RE:Vision, Boris, Rowbyte, Neat Video).
- [Mister Horse Animation Composer](https://misterhorse.com/) — the free easing/preset panel most motion designers run; huge starter library.
- [AEJuice free plugins](https://aejuice.com/free-plugins) — a huge curated index of free plugins and scripts.
- [Flow](https://aescripts.com/flow/) — simple, clean curve editor for keyframes.
- [Overlord](http://aescripts.com/overlord/) — send layers between Illustrator and AE as live vectors.
- [Bodymovin](https://github.com/bodymovin/bodymovin) — official Lottie exporter.
- [aescripts catalogue](https://aescripts.com/) — hundreds of code-driven tools: expressions, rigs, mograph utilities, batch exporters.

### Paid Essentials

- [Mt. Mograph Motion](https://aescripts.com/mt-mograph-motion/) — keyframe accelerators, curve graphs, alignment helpers, color tools. Arguably the highest-leverage subscription in AE.
- [Boris FX Continuum / Sapphire](https://www.borisfx.com/) — the deep effects library; Sapphire for premium looks, Continuum for utility.
- [Mocha Pro](https://www.borisfx.com/products/mocha/) — planar tracking, roto, stabilization, 3D camera solve.
- [Silhouette](https://www.borisfx.com/products/silhouette/) — next-gen roto.
- [Deep Glow](https://deepglow.com/) — volumetric light/glow; the best-looking glow money can buy.
- [RE:Vision Effects](https://www.revisionfx.com/) — Twixtor, RSMB (Really Smart Motion Blur), Flicker, Deflicker, Phoenix, Persistence, Staby.
- [Trapcode Particular](https://www.maxon.net/) — industry-standard particle system.
- [Magic Bullet](https://www.maxon.net/en/red-giant) — grade, color, and finishing.
- [OptiFlow](https://www.maxon.net/en/red-giant) — next-gen motion tracking.
- [King Pin Tracker](https://www.maxon.net/en/red-giant) — fast, AE-native surface tracking for everyday work.
- [Motion Bro](https://motionbro.net/) — preset and transition library for AE/Premiere; excellent when the clock is ticking.
- [Video Copilot](https://www.videocopilot.net/) — Element 3D, Saber, Fire of Babylon; a school unto itself.
- [Rowbyte](https://rowbyte.com/) — Plexus (great particle/3D starter), Aura, TV Distortion Bundle.
- [Auto-Trace bitmap](https://www.videocopilot.net/) — stylise raster footage into vector animation.
- [Rubberhose](https://aescripts.com/rubberhose/) — the famous arm-waving system.
- [AstroSeismic](https://cutpile.com/) — a rig manager for After Effects character animation.

### Bundles and Directories

- [AE Plugins](https://www.aeplugins.com/) — browsable directory of After Effects and FxPlug plugins.
- [Adobe Partner Finder](https://helpx.adobe.com/after-effects/using/plug-ins.html) — certified developers.
- [Motion Array Plugin Finder](https://motionarray.com/) — filters and reviews across the plugin ecosystem.

---

## Tracking, Cleanup, and VFX Tools

- [Mocha Pro](https://www.borisfx.com/products/mocha/) — planar tracking; tracks surfaces through changing light, motion blur, and occlusion.
- [Silhouette](https://www.borisfx.com/products/silhouette/) — roto and paint.
- [PFTrack](https://www.foundry.com/products) — The Foundry's tracker; rock solid.
- [SynthEyes](https://www.syntheyes.net/) — budget-friendly planar tracking.
- [Cleanup](https://www.innospace.io/products/cleanup) or [Neat Video](https://www.neatvideo.com/) — temporal denoise and dust-bust.
- [RE:Vision Effects](https://www.revisionfx.com/) — Twixtor (slow motion), RSMB (motion blur), Flicker, Deflicker.
- [Deep Glow](https://deepglow.com/), [Optical Glow](https://www.maxon.net/en/red-giant) — physically motivated bloom.
- [RealFlow](https://www.maxon.net/) — fluid and particle simulation for hero shots.
- [Katana](https://www.foundry.com/products) — production-grade compositing in Resolve.

---

## Renderers, Compositors, and Finish

**Render engines**
- [Redshift](https://www.maxon.net/redshift) — GPU renderer for C4D and Blender; the broadcast motion default.
- [Octane Render](https://octanerender.com/) — path-traced GPU rendering.
- [Corona](https://corona-renderer.com/) — fast, architectural-leaning, now 3ds Max/Maya/C4D.
- [V-Ray](https://www.v-ray.com/) — physically accurate, used across archviz and product.
- [Arnold](https://www.arnoldrenderer.com/) — physically based path tracer from Solid Angle, used on most feature films.
- [Karma](https://www.maxon.net/cinema-4d) — Maxon's production renderer in C4D.
- [Cycles](https://docs.blender.org/manual/en/latest/render/cycles/index.html) — Blender's path tracer.
- [LuxCore](https://luxcorerenderer.org/) — open-source, spectral, physically correct.

**Compositing and finishing**
- [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) — free edition includes Fusion, Fairlight, and a full grading suite. The most capable free post stack in existence.
- [Fusion](https://www.blackmagicdesign.com/products/davinciresolve/fusion) — node-based compositing, free and scriptable with Python.
- [Nuke](https://www.foundry.com/products/nuke) — the film/TV standard for compositing and tracking.
- [Silhouette](https://www.borisfx.com/products/silhouette/) — see above.
- [Remotion](https://www.remotion.dev/) — program-composited video from code.
- [Premiere Pro](https://www.adobe.com/products/premiere.html) — the editor; pair with Essential Graphics for simple GFX.
- [DaVinci Color page](https://www.blackmagicdesign.com/products/davinciresolve/color) — grading, and a genuinely great place to finish motion work.

---

## Color Grading and LUTs

- [DaVinci Resolve Color](https://www.blackmagicdesign.com/products/davinciresolve/color) — free, node-based, industry-proven.
- [ACES](https://www.acescentral.com/) — the Academy Color Encoding System; standard for film and high-end motion work.
- [OpenColorIO](https://opencolorio.readthedocs.io/en/latest/) — open-source color management, the standard under the hood.
- [colour-science.org](https://www.colour-science.org/) — Python library for color science and conversion.
- [LUTify.me](https://lutify.me/) — free LUT pack of every major film look.
- [Creative Bloop](https://creativebloop.com/luts/) — curated free LUT packs.
- [Ground Control](https://groundcontrol.fun/) — free LUTs with a focus on experimental looks.
- [Fix the Photo](https://fixthephoto.com/) — free and paid LUTs, clean explanations.
- [Rocket Stock](https://rocketstock.com/free-luts/) — classic free LUT bundle.
- [Color Grading Central](https://colorgradingcentral.com/) — grading fundamentals and DaVinci training.

---

## Typography and Fonts

**Font foundries and libraries**
- [Google Fonts](https://fonts.google.com/) — free, open, variable families.
- [Fontshare](https://www.fontshare.com/) — free quality fonts from the Indian Type Foundry.
- [Font in Use](https://fontsinuse.com/) — see real type in the wild; great for kinetic type references.
- [Typewolf](https://typewolf.com/) — tasteful type pairing and pairing advice.
- [Fontspring](https://fontspring.com/) — independent foundry marketplace.
- [Glyphs](https://glyphsapp.com/) — macOS font editor; great for variable font and animated glyph work.

**Type-specific motion**
- [Adobe Variable Fonts](https://helpx.adobe.com/illustrator/using/variable-fonts.html) — animate the `wght` and `wdth` axes for real type motion in Illustrator, AE, or the web.
- [Fontshare variable fonts](https://www.fontshare.com/) — variable families built for display motion.
- [Kinetic typography references](https://www.behance.net/galleries/typography/motion-graphics) — always worth a scroll.
- [Type Animation with LottieFiles](https://lottiefiles.com/blog/) — text animation as Lottie for web onboarding.

---

## Audio, Music, and Beat Sync

**Music libraries (license-cleared)**
- [Epidemic Sound](https://www.epidemicsound.com/) — the default for commercial video work.
- [Artlist](https://artlist.io/) — music + SFX with a universal license.
- [Soundstripe](https://soundstripe.com/), [Musicbed](https://www.musicbed.com/), [PremiumBeat](https://www.premiumbeat.com/), [Splice](https://splice.com/) (SFX-focused).
**Free and indie-friendly music**
- [Incompetech](https://incompetech.com/music/), [FreePD](https://freepd.com/), [Pixabay Music](https://pixabay.com/music/), [Uppbeat](https://uppbeat.io/), [YouTube Audio Library](https://www.youtube.com/audiolibrary).

**SFX**
- [Freesound](https://freesound.org/), [Zapsplat](https://www.zapsplat.com/), [BBC Sound Effects](https://sound-effects.bbcrewind.co.uk/) (personal use), [Soundsnap](https://soundsnap.com/).

**Beat and music tooling**
- Ableton Live / Logic / Reaper for spotting beats and building a comp against a track.
- In AE, mark beats manually, then use `linear()` and expressions to snap keyframes to markers — or use a beat-detection script from [AEJuice](https://aejuice.com/) and [aescripts](https://aescripts.com/).
- [Beatport](https://www.beatport.com/) and [SongBPM](https://www.songbpm.com/) for tempo data when licensing stems.
- Loudness matters: deliver broadcast at roughly **-24 LKFS** integrated, streaming around **-14 LUFS** (check the current [Spotify/YouTube normalization specs](https://www.youtube.com/watch?v=jfKfPfyJRdk) before mastering).

---

## Stocks, Templates, and Assets

**Stocks and footage**
- [Mixkit](https://mixkit.co/) — free, no attribution, motion-background friendly.
- [Pexels Videos](https://www.pexels.com/videos/) and [Coverr](https://coverr.co/) — free stock video.
- [Videvo](https://www.videvo.net/), [Storyblocks](https://www.storyblocks.com/), [Artgrid](https://artgrid.io/), [Envato Elements](https://elements.envato.com/), [Motion Array](https://motionarray.com/), [Pond5](https://www.pond5.com/).
- [FootageCouch](https://footagecouch.com/) — free HD clips, good for backgrounds.

**Motion templates**
- [Motion Array](https://motionarray.com/) — huge template and preset library, free + premium.
- [MotionElements](https://www.motionelements.com/) — After Effects templates, many free.
- [Envato Elements](https://elements.envato.com/video-templates) — Premiere/AE templates.
- [VideoHive](https://videohive.net/) — AE templates with a strong character-animation scene.
- [PremiumBeat](https://www.premiumbeat.com/) — stock + templates.
- [RocketStock](https://rocketstock.com/) — free AE templates and plugins.

**Animated assets, icons, illustrations**
- [LottieFiles](https://lottiefiles.com/free-animations) — thousands of free Lottie animations; best source for production-ready UI motion.
- [dotLottie Gallery](https://gallery.dotlottie.com/) — themed, interactive examples.
- [Icons8](https://icons8.com/animated-icons) — animated icons in Lottie and GIF.
- [Blush](https://blush.design/) — animated illustration packs you can customize.
- [Storyset](https://storyset.com/) by Freepik — animated illustrations with color customization.
- [unDraw](https://undraw.coil.io/illustration) — SVG illustrations (color-customizable), animate the SVGs.
- [ManyPixels](https://manypixels.co/gallery) — animated illustration galleries.
- [Haikei](https://haikei.app/) — SVG background generators to animate.
- [Lottie Animations by Airbnb](https://airbnb.io/lottie/) — reference-quality UI motion.
- [Fake3D](https://fake3d.com/) and [3Dicons](https://3dicons.org/) — 3D icon packs to spin and float.

**Audio-reactive visual sets**
- [AudioViz](https://www.audiomotion.app/) and [Visualiser Motion templates](https://motionarray.com/) — reference and templates for audio-reactive UI.

---

## Delivery, Codecs, and File Formats

**Raster video**
- **Me/mastering:** ProRes 422 / 4444 (with alpha), DNxHR, or lossless. Apple's ProRes tiers, explained in the [Final Cut Pro documentation](https://support.apple.com/final-cut-pro).
- **Delivery/streaming:** H.264/H.265 in MP4, WebM/AV1 for web. Check [Can I Use](https://caniuse.com/video) for support.
- **Motion work with alpha:** ProRes 4444, or PNG/EXR sequences. [Adobe's transparent-media guide](https://helpx.adobe.com/premiere-pro/using/alpha-channels.html) covers the workflow.
- **Image sequences:** PNG (lossless, alpha), EXR (linear/HDR, compositing).

**Vector and interactive**
- **Lottie JSON** — the default for UI motion. Watch the [Lottie format docs](https://lottiefiles.com/what-is-lottie/) and keep files small.
- **dotLottie** — adds theming, expressions, and state machines; smaller at runtime. See [the dotLottie spec](https://dotlottie.com/).
- **Rive (.riv)** — binary, stateful, data-bindable; requires the Rive runtime.
- **Animated SVG** — great for small, self-contained icons.

**Encoding and delivery tooling**
- [FFmpeg](https://ffmpeg.org/) — the definitive encoder. Command cookbook in the [FFmpeg Wiki](https://trac.ffmpeg.org/wiki).
- [Shutter Encoder](https://www.shutterencoder.com/) — friendly FFmpeg GUI.
- [HandBrake](https://handbrake.fr/) — straightforward H.264/H.265 encoding.
- [Adobe Media Encoder](https://www.adobe.com/products/media-encoder.html) — queues and watch folders straight from AE/Premiere.
- [Lossless APP](https://losslessapp.com/) — fast, modern conversion app.

**Motion-specific optimization**
- Lottie: enable "Optimize" in Bodymovin, strip unused keyframes, convert expressions to keyframes, watch for unsupported effects (blend modes beyond Normal, some filters, masks with dynamic paths are partial).
- Check with [LottieFiles' linter](https://lottiefiles.com/) and test on a low-end phone before shipping.
- dotLottie supports theming (swap colors/strings without re-exporting) — use it for themes and dark mode.

---

## UI and Product Motion Systems

If your work lives inside a product, the governing system is almost always already written. Read it before you design anything.

- [Material Design 3 — Motion](https://m3.material.io/styles/motion/overview) — the most explicit, tokenized motion spec in existence: duration tokens, easing sets, and transition patterns.
- [Apple Human Interface Guidelines — Motion](https://developer.apple.com/design/human-interface-guidelines/motion) — the shortest, most opinionated guidance in the industry. Read the "reduce motion" section before shipping anything.
- [Fluent 2 — Motion](https://fluent2.microsoft.design/motion) — Microsoft's design system motion tokens for web and Windows.
- [Carbon Design System — Motion](https://carbondesignsystem.com/elements/motion/overview/) — IBM's motion tokens with practical easing and duration values.
- [Shopify Polaris](https://polaris.shopify.com/) and [GitHub Primer](https://primer.style/product/motion/) — component libraries with motion baked into their components.
- [Motion UIs (Framer's take)](https://www.framer.com/motion/) — a useful practitioner-level overview of state-driven interface motion.

What every one of them agrees on: durations scale with distance, transitions should feel causal, and nothing decorative should auto-play forever. When a brand asks for a "custom" feel, the fastest route is usually a well-tuned token system rather than bespoke curves.

---

## Real-Time Control and Output Protocols

The moment your motion has to react to a person, a sensor, or another machine, you are in control-protocol territory.

- [NDI](https://ndi.video/) — the de facto standard for low-latency video over IP. Studio workflows, live IMAG, and multi-machine rendering feeds.
- [SRT](https://www.srt.org/) — Secure Reliable Transport; contribution-quality video over lossy networks for remote review and playout.
- [WebRTC](https://w3c.github.io/webrtc-pc/) — browser-native low-latency peer connections; use it when motion must react to a live camera or mic.
- [OSC](https://opensoundcontrol.org/) — Open Sound Control: the classic control protocol for TouchDesigner, Max/MSP, and Blender add-ons. Sends floats and strings at wire speed.
- [MIDI](https://www.midi.org/) — still the most reliable way to sync motion to hardware: lighting desks, controllers, and DAWs.
- **DMX512 and Art-Net** — the stage-lighting standards. If your motion runs on a set, these are the outputs, and knowing the channel map is part of the job.
- **OSC → TouchDesigner/Blender/Notch** — the classic control chain: a visualizer or a phone app sends OSC, the realtime engine reacts on the next frame.

---

## Production Pipeline, Review, and Dailies

- [Kitsu](https://www.kitsu.cloud/) / [CG-wire](https://www.cg-wire.com/) — open-source production tracking: shot statuses, dailies review, and versioning for animation and VFX teams.
- [Frame.io](https://frame.io/) — the default review platform; timecoded comments that resolve to frames rather than vague timestamps.
- Version control for `.aep`, `.c4d`, and `.blend` files: Git with [Git-LFS](https://git-lfs.com/), or a DCC-aware tool. Never email a project file.
- A sane handoff bundle: source project, render queue settings, fonts (licensed and licensed-for-embedding), texture and asset manifest, plugin list with versions, and a reference video at the exact delivery spec.

---

## AI Tools for Motion

Use these for pre-visualization, style exploration, and cleanup acceleration — with the usual care about licensing and provenance.

- [Runway](https://www.runwayml.com/) — text- and image-to-video, plus rotoscoping and background removal.
- [Luma Dream Machine](https://lumalabs.ai/) — video generation with strong camera control.
- [Pika](https://pika.art/) — short, stylizable generations and edits.
- [Adobe Firefly](https://firefly.adobe.com/) — commercially safer-trained generation, and it lives inside the Adobe apps you already use.
- [Topaz](https://www.topazlabs.com/) — upscaling, frame interpolation, and denoise; the practical tool for making a rough render presentable.
- [Resolve's built-in tools](https://www.blackmagicdesign.com/products/davinciresolve) — DaVinci's neural engine does interpolation, denoise, and upscale for free.

---

## Specifications, Standards, and Deliverables

- [EBU R 128](https://tech.ebu.ch/docs/tech/tech3343.pdf) — the loudness standard (-23 LUFS, true peak ceiling) for broadcast delivery. Learn it once; it saves arguments.
- [loudness.io](https://loudness.io/) — the friendly front end for R 128 metering and normalization.
- [SMPTE](https://www.smpte.org/) — timecode, frame rates, and interchange standards.
- [CTA](https://www.ctas.org/) — US caption and accessibility requirements; relevant if you deliver for broadcast or public spaces.
- [ATSC / safe areas](https://www.atsc.org/) — action-safe and title-safe regions. In motion graphics these matter because titles must survive overscan on every downstream device.
- [MDN Web Animations API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API) and [caniuse.com](https://caniuse.com/) — check support before committing to a technique.
- Frame rates: decide 24, 25, 30, 50, or 60 at the project level and never mix them inside one comp. Most broadcast and social delivery is 25/30; slow-motion workflows want 60 with shutter control.
- Deliver a spec sheet with every master: resolution, aspect ratio, frame rate, color space, loudness, codec, bit depth, alpha or no alpha.

---

## Awards, Conferences, and Archives

**Awards** — a finished piece is portfolio material with a citation attached.
- [AICP Awards](https://www.aicp.org/) — the commercial craft standard.
- [Annie Awards](https://www.annieawards.com/) — animation categories.
- [D&AD](https://www.dandad.org/) — design craft, including motion and digital craft categories.
- [Cannes Lions](https://www.canneslions.com/) — the advertising world's top shelf; shortlisted work is an excellent study reference.

**Conferences and festivals**
- OFFF Barcelona — the motion design festival; talks and showreels from the community that made this craft what it is.
- [Annecy](https://www.annecyfestival.com/) — animation at the highest level; watch the shorts for reference.
- [SIGGRAPH](https://www.siggraph.org/) — the technical conference; the Advances in Real-Time Rendering course is world class.
- Blend Conference — motion, VFX, and games animation in one room.
- [TouchDesigner](https://derivative.ca/) and [Resolume](https://resolume.com/) community events — the realtime side of the industry.

**Archives**
- [Prelinger Archives](https://archive.org/details/prelinger) — tens of thousands of industrial, educational, and title-sequence films, public domain. Arguably the richest motion reference library that exists.
- [Internet Archive](https://archive.org/) — films, magazines, and design ephemera.
- Public library title-design collections and national film institute archives — worth knowing that broadcast design history predates the web.

---

## Performance and Accessibility

- **Measure the real thing:** [web.dev/vitals](https://web.dev/articles/vitals) — LCP, INP, CLS all matter, but INP is where animation lives.
- **Respect reduced motion:** `prefers-reduced-motion: reduce` — treat it as a first-class mode. [MDN reference](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion).
- **Accessibility baseline:** [WCAG 2.2](https://www.w3.org/TR/WCAG22/) — including 2.3.3 Animation from Interactions and 2.2.2 Pause, Stop, Hide. Decorative motion that auto-plays for more than 5 seconds needs a pause control.
- **Budgets of thumb:** keep a hero Lottie under ~200 KB, one-frame-of-scroll-triggered work under 4 MB total JS, and prefer transform/opacity over animating layout properties.
- [Chrome performance docs](https://developer.chrome.com/docs/devtools/performance/) for finding dropped frames.
- Use `will-change` sparingly, promote layers deliberately, and kill unnecessary `will-change` after the animation.

---

## Learning: Courses and Schools

**Schools with structured programs**
- [School of Motion](https://www.schoolofmotion.com/courses) — the best-known online motion design school; Adobe and Maxon certified; design bootcamp, 3D, character, and broadcast tracks.
- [Motion Design School](https://motiondesign.school/) — 2D, 3D, frame-by-frame, AI, and rigging; huge course catalog and a strong community.
- [Domestash](https://domestash.com/) — trick-based, opinionated After Effects and Cinema 4D training.
- [CG Cookie](https://cgcookie.com/) — huge, practical AE/C4D library; "Orphan Planets" and advanced exercises.
- [Ripple Training](https://rippletraining.com/) — long-form, project-based motion design courses.
- [Animation Mentor](https://animationmentor.com/) — character animation and rigging (2D and 3D).
- [Gnomon](https://www.gnomon.net/) — Hollywood-grade CG education.
- [iRebel? Motion Content](https://motioncontent.com/) — practical Adobe training.
- [Motion Magic](https://www.motionmagic.com/) — broadcast and broadcast-adjacent motion design.
- [Tuts+ / Envato Tuts](https://tutsplus.com/) — free written and video tutorials across creative tools.
- [LinkedIn Learning](https://www.linkedin.com/learning/) — solid After Effects and motion fundamentals courses.
- [Udemy](https://www.udemy.com/) — variable quality, but cheap; look for recent, project-based courses.
- [Skillshare](https://www.skillshare.com/) — motion design and creative coding classes.

**University and formal programs**
- [Parsons (NYU) — Motion Graphics](https://courses.newschool.edu/courses/PSAM5440) — graduate motion design in NYC.
- [SCAD — Motion Media Design](https://catalog.scad.edu/courses/mome/mome.pdf) — full motion media curriculum.
- [Royal College of Art](https://www.rca.ac.uk/), [Gobelins Paris](https://www.gobelins.fr/) (GOBELINS — many Vimeo staff-pick animators are alumni), [California Institute of the Arts](https://calarts.edu/), [School of Visual Arts](https://sva.edu/).

**Certification**
- Adobe Certified Expert / Professional ([certification](https://training.adobe.com/certification)) — After Effects, Premiere.
- Maxon Certified ([Maxon Academy](https://www.maxon.net/)) — Cinema 4D, Redshift.

**Technical and graphics fundamentals** — required if you want to go beyond a timeline.
- [Learn OpenGL](https://learnopengl.com/) — the best free modern OpenGL course; shading, transformations, and the math you keep re-learning.
- [The Book of Shaders](https://thebookofshaders.com/) — GLSL taught through live interactive examples. The fastest way to stop treating shaders as magic.
- [WebGL Fundamentals](https://webglfundamentals.org/) — WebGL explained properly, with diagrams.
- [Three.js Learning Journey](https://threejs.org/manual/#en/introduction) — the official manual, plus a huge set of annotated examples.
- [Graphics Gems](https://github.com/erich666/GraphicsGems) — the code behind the classic book; still the clearest source on interpolation and easing maths.

### Free Courses

- [School of Motion — free courses and tools](https://www.schoolofmotion.com/free) — The Path to MoGraph, Level Up, plus free AE/C4D tools and the 500 Studios and Motion Design Hiring Guide ebooks.
- [Motion Design School — free lessons](https://motiondesign.school/) — free lessons and monthly competitions.
- [Adobe tutorials](https://helpx.adobe.com/after-effects/tutorials.html) — official, free, and genuinely good.
- [Blender.org — free manual and courses](https://www.blender.org/support/) and the [Blender Guru](https://www.youtube.com/@BlenderGuru) channel.
- [LottieFiles Academy](https://lottiefiles.com/blog/) — free articles on Lottie best practices.
- [Rive docs](https://rive.app/docs) and [Rive Academy](https://rive.app/community/files) — free tutorials and community files to remix.
- [Creative COW blog and articles](https://blogs.creativecow.net/) — free technique articles going back over a decade.
- [Animatron](https://animatron.com/) — free browser-based rigging and animation; great for experimenting without a license.

---

## YouTube Channels

- [School of Motion](https://www.youtube.com/@schoolofmotion) — motion design fundamentals from working professionals.
- [Ben Marriott](https://www.youtube.com/@BenMarriott) — free After Effects tutorials, expressions, workflow. Consistently excellent and free.
- [Jake in Motion](https://www.youtube.com/@JakeinMotion) — long-form After Effects breakdowns and challenges.
- [Roberto Jaime](https://www.youtube.com/@RobertoJaime) — playful experimental AE animation.
- [Grant Sinclair](https://www.youtube.com/@grantsinclair) — character animation fundamentals.
- [Blender Guru](https://www.youtube.com/@BlenderGuru) — Blender for everyone.
- [Loop Learning](https://www.youtube.com/@LoopLearning) — practical Adobe tutorial workflows.
- [Adobe Creative Cloud](https://www.youtube.com/@AdobeCreativeCloud) — official feature walkthroughs.
- [Rive](https://www.youtube.com/@RiveApp) and [Cavalry](https://www.cavalry.tools/) — official channels for the newer interactive tools.

---

## Newsletters, Blogs, and Publications

- [Motionographer](https://motionographer.com/) — the longest-running motion design publication; interviews, jobs, and industry news.
- [Frame.io Blog](https://blog.frame.io/) — production craft, editing, and VFX; the correlation-to-composition series is excellent.
- [Animation World Network](https://www.awn.com/) — animation industry news and technique.
- [Cartoon Brew](https://www.cartoonbrew.com/) — animation news and technique.
- [School of Motion Blog](https://www.schoolofmotion.com/blog/) — practical articles and breakdowns.
- [Motion Design School Blog](https://motiondesign.school/) — project breakdowns and workflow articles.
- [Adobe Blog — After Effects](https://blog.adobe.com/en/topics/after-effects) — feature releases and technique.
- [LottieFiles Blog](https://lottiefiles.com/blog/) — the best technical writing on Lottie performance and format.
- [Rive Blog](https://rive.app/blog) — interactive graphics engineering, including data binding and performance.
- [Spline Blog](https://spline.design/) — 3D for the web.
- [Motionographer Newsletter] — subscribe via [Motionographer](https://motionographer.com/) or on Substack.
- [A List Apart](https://alistapart.com/) — long-form web craft; great intersection of motion and interface.

---

## Inspiration and Showreels

**Galleries and showcases**
- [Behance — Motion Graphics](https://www.behance.net/galleries/Motion/Motion-Graphics) — the largest curated motion gallery; filter by appreciation count to see proven work.
- [Behance — Motion Design](https://www.behance.net/search/projects/motion%20graphics) — search-based discovery.
- [ArtStation — Motion Design](https://www.artstation.com/marketplace?query=motion%20design) — 3D-forward work.
- [Vimeo — Staff Picks](https://vimeo.com/staffpicks) — curation over volume.
- [Vimeo — Best Motion Design channel](https://vimeo.com/channels/bestmotiondesign) — community-curated showreels.
- [Motionographer Showreel](https://motionographer.com/showreel) — a curated reel of the year's best.
- [School of Motion — 500 Studios ebook](https://www.schoolofmotion.com/free) — a free, 500-page compendium of motion studios across 41 countries.
- [Pinterest](https://www.pinterest.com/search/pins/?q=motion%20graphics) and [Are.na](https://www.are.na/) — moodboard-grade reference building.

**Motion-specific inspiration**
- [Mr. Tomato](https://mr-tomato.com/) — curated broadcast design reference.
- [Logo Lounger](https://www.logolounge.com/), [Brand New](https://www.underconsideration.com/brandnew/), [BP&O](https://bpo.co.uk/) — brand identity case studies that often include motion systems.
- Broadcast design: [LowerThirds.com](https://lowerthird.com/), [Motion Graphic Design on Behance — Broadcast](https://www.behance.net/search/projects=broadcast%20graphics), [Cable/Network package breakdowns].

**Showreel practice**
- Keep showreels under 60 seconds, cut to the beat, lead with your strongest 3 seconds, and never show unfinished work.
- Reel format guides: [Motionographer](https://motionographer.com/), [School of Motion's Reel Guide](https://www.schoolofmotion.com/blog).

---

## Communities and Forums

- [Creative COW Forums](https://forums.creativecow.net/) — the longest-running After Effects/Post community; search before asking.
- [Adobe Community](https://community.adobe.com/) — official AE, Premiere, and Creative Cloud forums.
- [Reddit: r/AfterEffects](https://www.reddit.com/r/AfterEffects/), [r/aetutorials](https://www.reddit.com/r/aetutorials/), [r/blender](https://www.reddit.com/r/blender/), [r/animation](https://www.reddit.com/r/animation/), [r/motiongraphics](https://www.reddit.com/r/motiongraphics/).
- [Blender Stack Exchange](https://blender.stackexchange.com/) — rigorous Q&A for Blender.
- [Blender Artists](https://www.blenderartists.org/) — forum and challenges.
- [Motion Design Discord servers](https://discord.com/) — search for After Effects, Lottie, and Rive communities; LottieFiles and Rive both run active Discords.
- [Motionographer community + newsletter](https://motionographer.com/) — industry discussion and job board.
- [School of Motion community](https://www.schoolofmotion.com/community) — critique and feedback from working designers.
- [LottieFiles Community](https://lottiefiles.com/community) and [Rive Community](https://rive.app/community/files) — share files, get feedback, find collaborators.
- Discos: search Discord for current After Effects, Lottie, and Rive servers — they open and close, so verify invite links before sharing them.

---

## Portfolios, Freelance, and Jobs

**Where to host work**
- [Behance](https://www.behance.net/) — the standard motion portfolio host.
- [ArtStation](https://www.artstation.com/) — 3D motion portfolio and marketplace.
- [Vimeo](https://vimeo.com/) — better playback and player customization than most hosts.
- [Instagram](https://www.instagram.com/) — motion work does not compress well, but it drives discovery.
- [Dribbble](https://dribbble.com/) — small loops and UI motion; great for interaction roles.
- [Contra](https://contra.com/) — freelance profiles with motion-friendly portfolios.

**Finding work**
- [Upwork](https://www.upwork.com/) — the biggest freelance marketplace; filter for motion design.
- [Fiverr](https://www.fiverr.com/) — fixed-price motion gigs; good for quick turnarounds.
- [Motionographer job board](https://motionographer.com/) — industry jobs and freelance calls.
- [ProductionHUB](https://www.productionhub.com/) — broadcast, post, and creative production roles.
- [AIGA](https://www.aiga.org/) and [Design Jobs Board](https://www.designjobsboard.com/) — graphic and motion design roles.
- [Work with Indies](https://workwithindies.com/) — studio roles at indie game and animation companies.
- [Animation Guild](https://www.animationguild.org/) — union information and staffing for animation.
- [LinkedIn](https://www.linkedin.com/) — still the highest-signal channel for studio roles.

**Pricing and career**
- Read the [Motion Design Hiring Guide](https://www.schoolofmotion.com/free) (free, built from 13,287 job listings) for real salary bands and role definitions.
- Motion design contracts usually bill by project, by day rate, or by animated second. Always define revisions, source-file delivery, and usage/licensing terms in writing.
- [Motionographer's freelance and pricing discussion](https://motionographer.com/) — community threads on rates.

---

## Glossary

A short map of the vocabulary you will meet across these links.

- **MoGraph** — "motion graphics," coined in the title design community; also the name of Cinema 4D's built-in 3D mograph system.
- **Keyframing** — setting a value at a point in time and letting the software interpolate; **linear** interpolation vs. **bezier/eased** interpolation is the core of feel.
- **Graph editor** — the curve view where you shape speed directly; the shape of the curve *is* the character of the motion.
- **Anticipation** — a wind-up before the main action.
- **Follow through / overlap** — motion that continues after the action stops, or secondary elements that lag the primary.
- **In-betweens / on-ones / on-twos** — animation timing: the drawing you see every frame, every two frames, or only on the key moments. On-twos is the classic 2D feel.
- **Rigging** — building the control system (bones, IK, controllers) that makes a character animatable.
- **IK / FK** — inverse kinematics (handles drive limbs) vs. forward kinematics (joints chain forward).
- **Rotoscoping** — tracing over live-action frames.
- **Roto / roto-brushing** — creating and refining mattes.
- **Planar tracking** — following a flat surface through a shot, so you can composite onto it.
- **Matte** — a mask or alpha that controls what shows through.
- **Alpha channel** — the transparency channel; essential for motion elements delivered over live action.
- **Comp / precomp** — composition, AE's nested scene container.
- **Null object** — an invisible controller layer used to drive other layers.
- **Shape layer** — a vector layer (paths, strokes, fills) that scales without quality loss.
- **Motion blur** — the streaking of fast-moving elements; either real (renderer) or fake (shutter angle in AE).
- **Parallax** — depth from moving layers at different rates; a cheap way to make 2D feel 3D.
- **Loop / seamless loop** — an animation whose end matches its start; requires matching easing on the first and last keyframes.
- **Bounce / stagger** — overlapping secondary motion; offsetting in time, not just in space.
- **Ease in / ease out / ease in-out** — decelerating into a move, accelerating out, or both.
- **Spring** — physics-based motion that can be interrupted and re-targeted; feels alive because it settles.
- **Overshoot** — going past the target and settling back; the standard way to add life.
- **Antialiasing (render at 2x+)** — rendering large and downscaling for smooth edges.
- **Audio wave / beat mapping** — placing keyframes to musical beats.
- **Motion system** — a documented set of reusable animation rules (durations, easings, transitions) applied across a brand or product.
- **DotLottie** — a container format adding theming, expressions, and state machines to Lottie.
- **State machine** — an animation system where motion is a set of named states with transition logic, not a single timeline.

### Timeline and Interpolation

- **Interpolation** — how a value between two keyframes is computed: linear, bezier, or stepped.
- **Bezier handles** — the control points that shape an F-curve. Where they sit is the single biggest lever on feel.
- **Linear interpolation** — constant speed. Correct for continuous rotations and scrolling; almost always wrong for anything that starts or ends.
- **Time remapping** — retiming a shot on a rate graph, including the classic 50% slow-motion trick of blending consecutive frames.
- **Value graph / speed graph** — AE's two graph views; the speed graph shows velocity so you can see where a move accelerates.
- **Temporal anti-aliasing** — blending between rendered frames; how motion blur works under the hood.
- **Offset / stagger** — the per-element delay in a sequence; the difference between a sequence and a chorus.
- **Loop** — for a seamless loop, the last keyframe must mirror the first, including identical easing on both sides.
- **Cycle modifier** — repeats a keyframe range N times without duplicating keyframes.

### Layers and Compositing

- **Adjustment layer** — affects everything below it in the comp; the cleanest way to apply a grade or a grain pass.
- **Null object** — an invisible controller. Parent to it, drive it with one expression, move the whole rig.
- **Collapse transformations** — converts a 3D layer to 2D while keeping its 3D appearance; a common performance and shading fix.
- **Track matte** — one layer defines the visible area of another: add, subtract, or luminance.
- **Luma matte** — brightness drives the reveal, not alpha; classic for organic text reveals.
- **Alpha matte / garbage matte** — a rough solid shape that hides unwanted footage edges.
- **Shape layer** — a vector layer with paths, strokes, and fills; resolution independent and mask-animatable.
- **Trim Paths** — the shape-layer animator that draws a stroke on or off.
- **Repeater** — duplicates a shape layer along its path with per-copy offsets.
- **Merge paths / boolean ops** — add, subtract, intersect, and exclude shape paths.
- **Pick whip** — the spiral connector for parenting in 3D.
- **Expressions** — JavaScript-lite attached to properties; the fastest way to add controlled procedural motion.

### Rendering and Finishing

- **Proxy** — a low-resolution stand-in for smooth editing. Pre-render proxies before you touch a 4K timeline.
- **Pre-render / RAM preview** — caching frames for realtime playback; the single biggest quality-of-life feature in AE.
- **Multiframe rendering** — rendering multiple frames per pass; the AE setting that makes long timelines viable.
- **Motion blur** — blur proportional to per-frame movement. Shutter angle (180° = 0.5 frame exposure) is the control that sets the look.
- **Depth of field / bokeh** — selective focus; fakes 2D/3D separation as well as lens realism.
- **Chromatic aberration** — fringing from channel separation; a cheap, convincing lens cue.
- **Halftone** — dot or line screen approximation of an image; retro print motion without the retro job.
- **Glow / bloom** — light bleeding from bright areas; ideally physically based rather than a blurred copy.
- **Cache** — precomputed simulation or frame data (particle systems, tracking, dynamics); cache it or rebuild it every render.
- **Bit depth** — 8-bit for delivery, 16-bit for grading and heavy compositing; avoid 8-bit for large luminance ranges.
- **Gamma vs linear** — gamma-encoded display space versus linear light. Mixing them incorrectly is why glows and blends look muddy.
- **LUT** — a lookup table that maps one color space to another. Creative LUTs are a look, not a technical correction.
- **CDL** — ASC CDL, a parametric grade (slope, offset, power, saturation) that is portable across pipelines.
- **ACES** — the Academy Color Encoding System; a working space plus transforms, so renders from different tools match.

### Camera and 3D

- **Key light / fill / rim** — the three-point lighting setup; almost every readable motion shot needs at least two.
- **Camera solve** — deriving camera position and rotation from tracked data.
- **Stabilization** — removing unintended camera shake so you can add intentional movement.
- **Match move** — re-creating a shot's camera move on synthetic elements.
- **Parallax** — layers moving at different rates to fake depth; the oldest trick in motion design.
- **Occlusion** — one element passing in front of another; getting it wrong instantly breaks depth.
- **Frustum / camera limits** — the visible volume from a 3D camera; work outside it and layers disappear.

### Format and Delivery Terms

- **DotLottie** — a single-file container around Lottie with theming, expressions, and state machines.
- **State machine** — named states with defined transitions, driven by inputs or application state.
- **Data binding** — driving animation values from live application data instead of fixed keyframes.
- **Skeleton animation** — mesh deformation layered on top of a rig or 2D mesh; the clean way to bend vector illustration.
- **Inverse kinematics (IK)** — the end effector drives the joint chain; used for feet, hands, and tails.
- **Forward kinematics (FK)** — each joint inherits its parent's motion; the backbone of most walk cycles.
- **Onion skin / ghosting** — drawing or viewing previous and next frames to judge spacing.
- **Spacing vs timing** — spacing is where the poses land, timing is how long each pose holds. Change one and you change the weight.
- **Contact and passing poses** — the animation vocabulary for believable weight transfer.
- **Cloth sim / dynamics** — simulated secondary motion: cloth, hair, ropes, debris.
- **Motion system** — a documented set of durations, easings, and transitions that makes motion consistent across a product or brand.
- **Sound design** — the foley, ambience, and score that make motion feel physical. Underrated relative to its impact.
- **Beat sync** — aligning transitions and accents to the music grid; in real-time engines this comes from onset detection ([essentia.js](https://github.com/MTG/essentia.js) does this in the browser).

---

## How to Contribute

This list is meant to grow. When suggesting an addition:

1. **Verify it works.** Confirm the link loads, the tool is maintained, and the free tier is genuinely usable.
2. **Explain why it earns a place.** One line on what it does better than its neighbors is more valuable than a bare link.
3. **Prefer primary sources.** Official docs and vendor pages over listicles and affiliate blogs.
4. **Flag the license.** For assets, templates, fonts, and music, note whether it is free for commercial use.
5. **Keep it curated over exhaustive.** Ten well-chosen tools beat a hundred unranked ones.

### Suggested Contribution Format

```
- [Tool Name](https://link) — one sentence on what it is best at and who should use it.
```

### Contributing

Open a pull request with your addition or correction. For larger changes, open an issue first so we can discuss fit before you spend time writing.

---

## License

Documentation and curation in this repository are released under
[CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain).
Third-party tools, fonts, templates, and assets linked here remain under their
own licenses — always check before shipping commercially.
