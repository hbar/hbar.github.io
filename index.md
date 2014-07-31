---
layout: default
title: haroldbot
---

<p>I am an engineer, scientist, and a general maker of things.</p>

<p>I completed my doctorate of science at the <a href='http://www.psfc.mit.edu/'>MIT Plasma Science and Fusion Center</a>
in February 2014 and am currently a postdoc at MIT working on projects related to my doctoral work.</p>

<p>During my Ph.D. at MIT I gained substantial experience with ion-accelerators and their
applications as materials diagnostics.</p>

<p>For my doctoral research I developed a novel in-situ ion-accelerator-based diagnostic technique for
studying plasma-materials interactions in the Alcator C-Mod tokamak at MIT. This is the first
diagnostic to provide in-situ spatially-resolved measurements of the effects of plasma-materials
interactions in a fusion reactor and has important implications for magnetic fusion energy science.
Through this project, I also developed a strong background in accelerator engineering and particle
beam modeling. I rebuilt and upgraded a radio frequency quadrupole accelerator, including its control
and power systems. In addition, I developed my own ion beam dynamics simulation tools for modelin
ion beams in the complex fields of a tokamak.</p>

### Projects
{% for post in site.posts limit: 5 %}
- {{ post.date | date_to_string }} <span class="separator">~</span> [{{ post.title }}]({{ post.url }})
{% endfor %}