---
layout: categories
permalink: /
hidden: false
header:
  overlay_color: "#5e616c"
  overlay_filter: 0.3
  overlay_image: /assets/images/tentacle-draft-1.gif
excerpt: >
  Mon portfolio
row1:
  - image_path: /assets/images/GT-fighting-game.png
    alt: "Projets Personnels"
    title: "Projets Personnels"
    excerpt: >
      Projets réalisés dans un cadre personnel, seul ou avec des amis.
    btn_label: "<i class='fas fa-info-circle'></i> En savoir plus"
    btn_class: "btn--primary"
    url: /projets-personnels/

row2:
  - image_path: /assets/images/ecoles.png
    alt: "Projets Scolaires"
    title: "Projets Scolaires"
    excerpt: >
      Projets réalisés dans un cadre scolaire, à Rubika ou au CNED.
    btn_label: "<i class='fas fa-info-circle'></i> En savoir plus"
    btn_class: "btn--primary"
    url: /projets-scolaires/

---

{% include feature_row id="row1" type="left" %}

{% include feature_row id="row2" type="right" %}
