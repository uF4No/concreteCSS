README
Author: Antonio Ufano

concreteCSS is a library focused in helping you create a responsive layout for your website.
It's a basic version of Bootstrap or Foundation but without all the classes for navbars, buttons and all other components, this is just focused on the grid, so you can create your own styles for the rest of the components of your web in your own CSS file.

concreteCSS uses rows a 12 columns layout. For example, if you want to create a row with two sidebars, you can use the following structure:
<div class="row">
  <div class="col-2">
    <p>Sidebar 1</p>
  </div>
  <div class="col-8">
    <p>Main</p>
  </div>
  <div class="col-2">
    <p>Sidebar 2</p>
  </div>
</div>

It also has "-m-" classes for the margin between 600px and 768px.

Feel free to use in your projects.
You can also modify this CSS as you need and, send any Pull Request to GitHub :)
