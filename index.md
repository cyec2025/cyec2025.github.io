---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: splash
header:
  overlay_color: "#0f0"
  overlay_filter: "0.5"
  overlay_image: /assets/images/chimera_wide3.png
excerpt: "Coding and creativity over the years"
intro:
  - excerpt: 'For detailed portfolio by year or type of project, use the upper right navigation menu. Featured collections:'
feature_row:
  - image_path: /assets/images/chimera-stackedsquare.png
    alt: "Chimera Factory"
    title: "Yekko on itch.io"
    excerpt: "Chimera Factory, Simpleton, and other game jam creations"
    url: "https://yyekko.itch.io"
    btn_label: "Visit"
    btn_class: "btn--success"
  - image_path: /assets/images/Metroil2shot.png
    alt: "ToadKid"
    title: "ToadKid on Scratch"
    excerpt: "Years of games and other code on scratch.mit.edu"
    url: "https://scratch.mit.edu/users/toadkid/"
    btn_label: "Visit"
    btn_class: "btn--info"
  - image_path: /assets/images/Problem14-7.png
    title: "Python Repository"
    excerpt: "CYeC's python for games, class assignments, and math fun"
    url: "https://github.com/cyec2025/cyec_python"
    btn_label: "Visit"
    btn_class: "btn--warning"
---
{% include feature_row id="intro" type="center" %}
{% include feature_row %}
