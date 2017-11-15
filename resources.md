## Resources
This page shows how to embed resources (images, videos, pdf files) in your pages.

### Small image (from web)

![](https://pbs.twimg.com/profile_images/903658777295163392/afySJpM5_400x400.jpg)

### Large image (from assets folder)

![](assets/images/cover.jpg)

## Video embed

<!-- change src="" attribute  -->
<div class="aspect-ratio">
  <iframe src="https://www.youtube.com/embed/uWSxzjyMNpU" frameborder="0" allowfullscreen="True"></iframe>
</div>

## PDF embed

<!-- change data="" and href="" attributes  -->
<!-- change height="" if needed  -->
<object data="assets/pdf/sample-pdf.pdf" type="application/pdf" width="100%" height="600px">
  <p>This browser does not support PDFs. Please download the PDF from <a href="assets/pdf/sample-pdf.pdf">here</a>!</p>
</object>
