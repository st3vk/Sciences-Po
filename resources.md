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
<!-- change height="" if needed  -->
<div class="aspect-ratio power-point">
  <object data="assets/pdf/powerpoint.pdf" type="application/pdf">
    <object data="https://docs.google.com/gview?embedded=true&url=https://thegreattransition.github.io/group00/assets/pdf/powerpoint.pdf"></object>
  </object>
</div>

<div class="aspect-ratio document">
  <object data="assets/pdf/a4.pdf" type="application/pdf" width="50%">
    <object data="https://docs.google.com/gview?embedded=true&url=https://thegreattransition.github.io/group00/assets/pdf/a4.pdf"></object>
  </object>
</div>

<!-- <object data="assets/pdf/sample-pdf.pdf" type="application/pdf" width="100%" height="600px">
  <p>This browser does not support PDFs. Please download the PDF from <a href="assets/pdf/sample-pdf.pdf">here</a>!</p>
</object> -->
