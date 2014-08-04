---
layout: default
title: haroldbot
---

<p>I am an engineer, a scientist, an adventurer, an artist, and a maker of many things.</p>

<p> I am interested in energy technology, among many other things, and have been working on nuclear fusion energy research as a student and as a researcher at MIT. I completed my doctorate at the <a href='http://www.psfc.mit.edu/'>MIT Plasma Science and Fusion Center</a> in February 2014 and am currently a postdoc working on projects related to my doctoral work. I'm always interestded in exciting new projects and am looking forward to places that my life and my career take me next</p>.

### Current Research Topics

- Accelerator-based diagnostic techniques for materials analysis (hardware development, beam optics, X-ray/gamma ray
spectroscopy, and computational modeling)
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
