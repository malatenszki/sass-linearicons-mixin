# sass-linearicons-mixin
If You want to use Linearicons with sass, you need this mixin

# First Step

Install the Node module using NPM

'npm install linearicons'

Change the path to the module.

# Second Step - Enjoy


If You want to use Home icon on after element, with margin

.custom-selector {
  @include linearIcons(home, after, 0 5px);
}


If You want to use Star icon on before element, without margin

.secondary-custom-selector {
  
  @include linearIcons(star);
}