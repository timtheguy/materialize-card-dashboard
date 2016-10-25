# Materialize Card Dashboard
A custom (and straightforward) material design inspired dashboard using [Materialize](https://github.com/Dogfalo/materialize), a CSS framework based on Google's Material Design.

## Demo
__Click [here for the live demo.](https://timtheguy.github.io/materialize-card-dashboard/)__

## Code Snippets

Card panels in Materialize are defined with the following structure. Do not interfere with this structure when templating the cards in index.html:
```html
<div class="card-panel white hoverable">
  <span class="black-text">
    Card text
  </span>
</div>
```

Similarly, the main text area in the dashboard is defined under this markup structure:
```html
<div class="main">
  <div class="row">
    <div class="col s12">
      <div class="card-panel white hoverable" style="height: 100% !important;">
        <span class="black-text">
          Body text
        </span>
      </div>
    </div>
  </div>
</div>
```

## Motivation
Creating a single page application that displays information from cards in a single viewport was not easily designed with the existing Materialize CSS documentation and examples. Designed for single page applications, this sample can be templated into a variety of project settings, such as database platforms that deal with quickly clicking through a variety of entries.
