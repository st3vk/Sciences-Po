## Resources
This page shows how to embed resources (images, videos, pdf files) in your pages.

### Image from the web
```
![](https://pbs.twimg.com/profile_images/903658777295163392/afySJpM5_400x400.jpg)
```
![](https://pbs.twimg.com/profile_images/903658777295163392/afySJpM5_400x400.jpg)

### Image from `assets/images/` folder
```
![](assets/images/cover.jpg)
```
![](assets/images/cover.jpg)


### Image size
```
![](https://pbs.twimg.com/profile_images/903658777295163392/afySJpM5_400x400.jpg){:height="50%" width="50%"}
```
![](https://pbs.twimg.com/profile_images/903658777295163392/afySJpM5_400x400.jpg){:height="50%" width="50%"}


## Embed video (from YouTube)
In the code bellow, replace `uWSxzjyMNpU` with your own YouTube video's id (the bit after the last `/` in the videos' address)
```
<div class="aspect-ratio video">
  <iframe src="https://www.youtube.com/embed/uWSxzjyMNpU" frameborder="0" allowfullscreen="True"></iframe>
</div>
```
<div class="aspect-ratio video">
  <iframe src="https://www.youtube.com/embed/uWSxzjyMNpU" frameborder="0" allowfullscreen="True"></iframe>
</div>


## Embed PDF

In the code bellow, change `assets/pdf/a4.pdf` in front of `data` and `href` attributes to the address of your PDF file. If you have uplaoded your PDF files in `assets/pdf` folder then simply change `a4` to the name of your PDF file.
```
<div class="aspect-ratio document">
  <object data="assets/pdf/a4.pdf" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/a4.pdf">here</a> to download the file</p>
  </object>
</div>
```
<div class="aspect-ratio document">
  <object data="assets/pdf/a4.pdf" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/a4.pdf">here</a> to download the file</p>
  </object>
</div>

You can also save and upload your PowerPoints as PDF.
```
<div class="aspect-ratio document">
  <object data="assets/pdf/powerpoint.pdf" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/powerpoint.pdf">here</a> to download the file</p>
  </object>
</div>
```
<div class="aspect-ratio document">
  <object data="assets/pdf/powerpoint.pdf" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/powerpoint.pdf">here</a> to download the file</p>
  </object>
</div>
