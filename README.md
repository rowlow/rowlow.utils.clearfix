# rowlow.utils.clearfix

A clearfix helper for ROW LOW framework. Clearfixes help you to clear floats in your layout. 

## Settings

```
    $rowlow-clearfix-namespace //Specific module namespace
```

## Mixins

```
    rowlow-clearfix // Add clearfix specification
```

## Usage

### Setup
```
    /* Set module namespace (optional) */
    $rowlow-clearfix-namespace: "namespace-";

    @import "bower_components/rowlow.utils.clearfix/main.scss"
```

### SCSS

```
    .some-element{
        @include rowlow-clearfix;
    }

    .some-element{
        @extend .clearfix;
    }
```

### HTML

```
    <div class="clearfix"></div>
```