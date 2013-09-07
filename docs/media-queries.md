## Breakpoints from uikit

```
@breakpoint-mini-max:             (@breakpoint-small - 1);

@breakpoint-small:                480px;
@breakpoint-small-max:              (@breakpoint-medium - 1);

@breakpoint-medium:               768px;
@breakpoint-medium-max:             (@breakpoint-large - 1);

@breakpoint-large:                960px;
@breakpoint-large-max:              (@breakpoint-xlarge - 1);

@breakpoint-xlarge:               1220px;
```

## Media queries from Foundation

```
$small-screen: 768px;
$medium-screen: 1280px;
$large-screen: 1440px;

$screen: "only screen";
$small: "only screen and (min-width: #{$small-screen})";
$medium: "only screen and (min-width: #{$medium-screen})";
$large: "only screen and (min-width: #{$large-screen})";
$landscape: "only screen and (orientation: landscape)";
$portrait: "only screen and (orientation: portrait)";
```

## Media queries from TheNextWeb

```
Large desktop:
@media (min-width: 1130px)

Small desktop and below:
@media (max-width: 1130px)

small desktop / tablet landscape:
@media (min-width: 1000px) and (max-width: 1130px)

tablet landscape and below:
@media (max-width: 1000px)

Landscape phone to portrait tablet:
@media (max-width: 780px)

Landscape phones and down:
@media (max-width: 480px)

Printer:
@media print

Printer:
@media print and (min-width: 1130px)
```

## Media queries from CSS-Tricks

```
/* Smartphones (portrait and landscape) ----------- */
@media only screen 
and (min-device-width : 320px) 
and (max-device-width : 480px) {
/* Styles */
}

/* Smartphones (landscape) ----------- */
@media only screen 
and (min-width : 321px) {
/* Styles */
}

/* Smartphones (portrait) ----------- */
@media only screen 
and (max-width : 320px) {
/* Styles */
}

/* iPads (portrait and landscape) ----------- */
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) {
/* Styles */
}

/* iPads (landscape) ----------- */
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : landscape) {
/* Styles */
}

/* iPads (portrait) ----------- */
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : portrait) {
/* Styles */
}

/* Desktops and laptops ----------- */
@media only screen 
and (min-width : 1224px) {
/* Styles */
}

/* Large screens ----------- */
@media only screen 
and (min-width : 1824px) {
/* Styles */
}

/* iPhone 4 ----------- */
@media
only screen and (-webkit-min-device-pixel-ratio : 1.5),
only screen and (min-device-pixel-ratio : 1.5) {
/* Styles */
}
```