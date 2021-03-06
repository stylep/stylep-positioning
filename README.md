# stylep-positioning
<img src=https://avatars1.githubusercontent.com/u/16121328?v=3&s=200 title=stylep-positioning align=right height=95>

Everything you need to get started making a new style pattern.

## Install
You can install using the [spm](https://github.com/stylep/stylep) command or install using npm and the project title.

``` shell
spm install positioning
```

## Usage
``` css
/* positioning.css */

@import “stylep-positioning”;

.class {

  /* Button Design Pattern */
  @extend %positioning;

  /* Customize your positioning */
  @mixin positioning param, param;

  /* or roll your own */

  /* add something custom in here */
}
```

## Patterns
Placeholder selectors that contain common styles for structure and basic behavior.

#### `@extend %positioning-inline;`
Describe what this pattern does.

## Styles
Customizable presets that give your pattern a specific style-set.

### positioning-solid
Describe the visual look and feel of this style.

##### Options

* `$param: default-value` Describe what this does

##### Example
```css
/* describe in english what this following statement really means in detail */
@mixin positioning-solid default-value;
```

## License
This project is licensed under the MIT [license](LICENSE).
