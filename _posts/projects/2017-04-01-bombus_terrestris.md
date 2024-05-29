---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Jekyll, Pineapple"

project:
  title: "Bombus terrestris"
  subfilo: "Hexapoda"
  orden: "Hymenoptera"
  familia: "Apidae"
  logo: "/assets/images/projects/bombus_terrestris/logo.png"

agency:
  distribucion: "Chile, Argentina"
  estatuto: "Introducido"
  conservacion: "En Peligro"

images:
  - image:
    url: "/assets/images/projects/bombus_terrestris/image1.JPG"
    alt: "Obrera del abejorro europeo forrajeando flores de lupino"

---
<div class="image-container">
  <img src="{{ site.baseurl }}{{ page.images[0].image.url }}" alt="{{ page.images[0].image.alt }}">
  <p class="image-description">{{ page.images[0].image.alt }}</p>
</div>

<p><i>Bombus terrestris </i>, también llamado abejorro europeo, es una especie introducida de Europa para la polinización de los cultivos como el tomate o el arándano. Se naturalizó en Chile e invadió la casi totalidad del país. </p>
