# gdx-components-less
A bundle of all required less, less-variables, grid configuration, colorSchemes, and mixins to generate flexible CSS according to our frontend styleguide. 


## naming convention
Less files which includes:

* only variable definitions
  * post fixed with var-[bundle name].less
  * e.g.: var-colors.less (contains all color code definition)

* only mixins
  * post fixed with mix-[bundle name].less
  * e.g.: mix-colorSchemeBackgroundColors.less (contains all mixins to generate background colors with colorScheme support)
 
* only CSS class definitions
  * no special post fix required: [bundle name].less
  * e.g.: background-colors.less (contains all class definitions for background colors) 
