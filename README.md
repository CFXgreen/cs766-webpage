# CS 766 Docs

Please do not modify the CSS file without permission from the creator of this repository.

## Custom CSS Class and Tag Documentation

### Navigation Tabs

To add the navigation tabs, use the li (list) tag and a (anchor) tag

```HTML
<li><a href="#your id here">Your script here</a></li>
```

### Paragraph

Everytime you create a p (paragraph) tag, there will be a margin added to the bottom. Therefore, if you have double p (paragraph) tag, spacing will be added automatically.

### Header

For the header, use h2 tag. Color and margin will be added for you automatically when you use the h2 tag.

### Section Class

Section class is added everytime you create a new section (i.e. Introduction section, motivation section, etc). Your section class should be accompanied with a div tag.

```HTML
<div id="your id here" class="section">
  Your script here
</div>
```

### Center Video

The center video class is to center a video. It should be accompanied with a div tag (i.e. you should enclose your video class or any video tag class with the div tag).

```HTML
<div class="center-video">
  <video></video>
</div>
```

or

```HTML
<div class="center-video">
  <iframe>Youtube generated video</iframe> 
</div>
```

### Center Image

The center image class is to center an image (width and height should be modified on your own). This class should be accompanied with a div tag.

```HTML
<div class="center-image">
  <img src="" alt="" />
</div>
```
