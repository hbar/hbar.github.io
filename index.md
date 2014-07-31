---
layout: default
title: haroldbot
---

<p>I am an engineer, scientist, and a general maker of things.</p>

<p>I completed my doctorate of science at the <a href='http://www.psfc.mit.edu/'>MIT Plasma Science and Fusion Center</a>
in February 2014 and am currently a postdoc at MIT working on projects related to my doctoral work.</p>

<p>During my Ph.D. at MIT I gained substantial experience with ion-accelerators and their
applications as materials diagnostics.</p>

### Research Experience

- Accelerator-based diagnostic techniques for materials analysis (hardware development,
spectroscopy, beam optics and modeling)
- Fusion and fission reactor design (engineering and conceptual design studies)
- General design, engineering, and integration of scientific equipment

### Engineering Experience

- **Prototyping**: accelerator hardware, instrumentation, mechanical design, PCB design
- **Electrical Eng**.: analog circuit design, PLC controls, DC/RF/pulsed power systems
- **Mechanical Eng**: structural/thermal analysis, FEA, pneumatics, vacuum systems
- **CAD Modeling**: SolidWorks, AutoCAD, QCad, Eagle
- **Scientific Computing**: Python, MATLAB, COMSOL
- **Neutron Transport Modeling**: MCNP
- **Fabrication**: machining, welding, brazing, electrical soldering, carpentry

## Projects
{% for post in site.posts limit:5 %}
  - {{ post.date | date: '%B %Y' }} <span class="separator">~</span> [{{ post.title }}]({{ post.url }})
{% endfor %}
[more projects...](/pages/projects)