![Numerus NuWebKit](https://github.com/rmsalter/NuWebKit/blob/main/nuwebkit-logo.png)

**Numerus NuWebKit** is a browser-based simulator designed for cellular, agent-based, and dynamical systems modeling, analysis, and simulation. Integrated into the Numerus ecosystem, the platform allows users to build and run computational models directly in a web browser. It provides accessible preset models that require no initial programming, while also featuring an AI window that enables users to modify existing frameworks or construct custom models from scratch. It is commonly used in educational and research environments to teach system dynamics and mathematical modeling concepts.

**NuWebKit Features**`
* Supports Agent-based (ABM), Spatial and System Dynamic (SD) modeling paradigms.
* Entirely Web-browser based. No installation required.
* References familiar Netlogo "patch" and "turtle" (ABM, Spatial); and "stock" and "flow" (SD) models.
* State variables are all double-buffered, insuring that state transitions are concurrent.
* Built-in execution rules, which simplify programming, can be overridden when necessary.
* Data can be downloaded into comma-separated-value (CSV) files.
* All applications can include on-board documentation.
* Includes programmable presets that capture parameter settings and SD model specifications. Presets are stored in the browser and return with every session.
* The Designer application lets you build your own applications in the Web browser.
* The RAM (runtime alterable model) feature, seen on previous Numerus platforms, allow controlled design changes to be made at runtime and captured in presets.
* Extensive user guides and tutorials are provided to assist programmers.
* An eclectic and growing Model Library, along with its source code, is maintained to provide design ideas.
* Presets and user-defined projects are downloadable for local storage and sharing, and are easily re-launched.
* SD models can be built either as stand-alone projects, or as presets of a hosting app, using a simplified code that reduces programming complexity.
* AI integration can be used to build SD models from plain-language user prompts. AI integration for ABM and Spatial models will soon be available.
* Models can take advantage of Sensitivity Analysis and Stochastic multi-run analytical tools.
* The Remote Operation feature, available shortly, can make any simulation operate as a "virtual" package under the control of the R statistical platform, Python or any platform supporting internet sockets.
 

Visit the [NuWebKit client-side example models repository](https://nuwebkit.models.numerus.app/). Some are general audience examples of models as webapps, while others are demonstrations for specific audiences.

Compose your own agent-based, spatial and system dynamics models. 
Click to access the Designer authoring site, with access to source code from the model library available for reference:
![nuwebkit-designer-logo.png](https://nuwebkit.models.numerus.app/common/designer/index1.html) 

**Numerus Documents**

* NuWebKit is documented in [Salter R and Getz WM (2026), *AI-enabled, user-modifiable, systems simulation web apps*, Front. Syst. Biol. 6:1964116. doi: 10.3389/fsysb.2026.1964116](https://www.frontiersin.org/journals/systems-biology/articles/10.3389/fsysb.2026.1964116/full).
* Additional documentation for NuWebKit can be found at [wiki.numerusinc.com](https://wiki.numerusinc.com/index.php/Main_Page).
* See also:
    * [The Numerus Midas SIRS App](https://www.numerusinc.com/midas/), a complete lesson in classic epidemiology.
    * [*Teaching dynamical systems modeling, analysis and simulation using a Lotka-Volterra Predation Narrative and a Numerus WebKit App*](https://ecoevorxiv.org/repository/view/15696/), companion to the [Numerus Webkit Dynamic Systems Simulator for Population Biology 1](https://nuwebkit.models.numerus.app/dynsslvpp/)

**User Guides and Tutorials for Designer and DynSS Programming**

* Programming ABMs and Cellular Automata is described in [NL API User Manual: Building Patch and Agent Models](https://nuwebkit.models.numerus.app/common/doc/).
* Programming system-dynamics models is described in [SD API User Manual: Building Stock-and-Flow Models](https://nuwebkit.models.numerus.app/common/doc/sd/).
* The NuML modeling language used by the DynSS apps is described in the [NuML User Manual](https://nuwebkit.models.numerus.app/common/doc/numl/).


