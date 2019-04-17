# SASS Color palette

An easy to use function for generating css for colors.

<h3>Usage</h3>

<pre>
// Colors map
// Insert this in _variables.scss
$color-palettes: (
    grey: (
        light    : #dedede,
        base     : #656565,
        dark     : #181818
        ),
    social: (
        gplus     : #DD4B39,
        facebook  : #3C5A99,
        twitter   : #28AAE1,
        pinterest : #CB222A,
        instagram : #d10869,
        linkedin  : #0084bf,
        youtube   : #EE3124,
        medium    : #292929
    )
);

// Usage in app files
.selector {
    background: palette(grey, light);
    color: palette(social, facebook);
}
</pre>

<h3>Result</h3>

<pre>
.selector {
    background: #dedede;
    color: #3C5A99;
}
</pre>
