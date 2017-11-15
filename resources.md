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
<div class="aspect-ratio document">
  <object data="assets/pdf/powerpoint.pdf#zoom=scale" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/powerpoint.pdf">here</a> to download the file</p>
  </object>
</div>

<br>

<!-- change data="" and href="" attributes  -->
<div class="aspect-ratio document">
  <object data="assets/pdf/a4.pdf#zoom=scale" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/a4.pdf">here</a> to download the file</p>
  </object>
</div>
