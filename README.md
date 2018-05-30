# Bassless
{less} port of the Basscss toolkit

- Original repo: https://github.com/basscss/basscss
- Docs: http://basscss.com/

## Usage
- Import the basscss.less file in your project
- Customize some vars to fit your needs
- Optional add some or all addons

```less
// Get some basic styles/resets
@import "modules/basic";

// get the base toolkit
@import "src/basscss";

// add all addons
@import "addons/index";

// or e.g. only the responsive margins
@import "addons/responsive-margin/index";

// customize some vars, see vars.less for all available variables
@border-width: 2px;
@breakpoint-xs: 400px;
@breakpoint-sm: 600px;
@breakpoint-md: 960px;
@breakpoint-lg: 1280px;

// build something awesome
```

## Differences to the original toolkit
- There are more breakpoints available (xxs, xs, sm, md, lg, xl)
- There are more "space" vars available used for margin/padding stuff (@space-1 ... @space-6)
- The hide module uses the same breakpoints
