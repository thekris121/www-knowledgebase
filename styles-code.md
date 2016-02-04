```sass
/// Makes an element visually hidden, but still accessible to keyboards and assistive devices.
/// @link http://snook.ca/archives/html_and_css/hiding-content-for-accessibility Hiding Content for Accessibility
@mixin element-invisible {
  position: absolute !important;
  width: 1px;
  height: 1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
}
```

