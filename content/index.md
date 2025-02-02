title = "Welcome to Bartholomew"
description = "The Micro-CMS for Wagi"

[extra]
date = "Aug. 30, 2021"
author = "Matt Butcher"
author_page = "/author/butcher"
---
It might be hard to spell, but fortunately you won't have to spell it that often.

Bartholomew is a Micro-CMS for hosting Markdown content on a WebAssembly server.
It can run on any [Wagi-compliant runtime](https://github.com/deislabs/wagi), including
Wagi, Hippo, and Wagi.Net.


<div class="card mb-3" >
  <div class="row g-0">
    <div class="col-md-4">
      <img src="/static/markdown.png" class="img-fluid rounded-start text-center" alt="Markdown logo">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Content Is Markdown</h5>
        <p class="card-text">Write your content in Markdown, the simple text-based markup language.
Just drop your content somewhere in the `content/` folder, and you're ready to go.</p>
        <p class="card-text"><small class="text-muted">Learn More</small></p>
      </div>
    </div>
  </div>
</div>

<div class="card mb-3">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="/static/handlebars.png" class="img-fluid rounded-start text-center" alt="Handlebars logo">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Templates are Handlebars</h5>
        <p class="card-text">Handlebars is a popular template format similar to Mustache. All of the templates
are fully customizable. You can take a look in the `templates/` directory to start
customizing the look and feel of this site.</p>
        <p class="card-text"><small class="text-muted">Learn More</small></p>
      </div>
    </div>
  </div>
</div>

<div class="card mb-3" >
  <div class="row g-0">
    <div class="col-md-4">
      <img src="/static/bootstrap.png" class="img-fluid rounded-start text-center" alt="bootstrap logo">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Defaults to Twitter Bootstrap</h5>
        <p class="card-text">The theme that ships with Bartholomew is just a simple [Twitter Bootstrap](https://getbootstrap.com/) theme.</p>
        <p class="card-text"><small class="text-muted">Learn More</small></p>
      </div>
    </div>
  </div>
</div>

<div class="card mb-3" >
  <div class="row g-0">
    <div class="col-md-4">
      <img src="/static/toml.png" class="img-fluid rounded-start text-center" alt="TOML logo">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Simple TOML Config Files</h5>
        <p class="card-text">Configuration files are in `config`, and are simple TOML files. Probably the only one
you need is `config/site.toml`.
</p>
        <p class="card-text"><small class="text-muted">Learn More</small></p>
      </div>
    </div>
  </div>
</div>


## Getting Started

To get started, edit this page. While Bartholomew doesn't make a lot of assumptions about
your site, it _does_ assume that requests to the root (`/`) should be directed to
`index.md`.