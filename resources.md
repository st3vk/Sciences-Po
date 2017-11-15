## Resources
This page shows how to embed resources (images, videos, pdf files) in your pages.

### Small image (from web)

![](https://pbs.twimg.com/profile_images/903658777295163392/afySJpM5_400x400.jpg)

### Large image (from assets folder)

![](assets/images/cover.jpg)

## Video embed

<!-- change src="" attribute  -->
<div class="aspect-ratio video">
  <iframe src="https://www.youtube.com/embed/uWSxzjyMNpU" frameborder="0" allowfullscreen="True"></iframe>
</div>

## PDF embed

<!-- change data="" and href="" attributes  -->
<!-- use class="aspect-ratio powerpoint" to embed PowerPoints -->
<div class="aspect-ratio power-point">
  <object data="assets/pdf/powerpoint.pdf" type="application/pdf">
    <object data="https://docs.google.com/gview?embedded=true&url=https://thegreattransition.github.io/group00/assets/pdf/powerpoint.pdf"></object>
  </object>
</div>

<br>

<!-- change data="" and href="" attributes  -->
<!-- use class="aspect-ratio document" to embed A4 documents -->
<div class="aspect-ratio document">
  <object data="assets/pdf/a4.pdf" type="application/pdf" width="50%">
    <object data="https://docs.google.com/gview?embedded=true&url=https://thegreattransition.github.io/group00/assets/pdf/a4.pdf"></object>
  </object>
</div>
