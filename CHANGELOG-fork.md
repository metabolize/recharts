## 1.0.1-metabolize.3

### feature

- Allow specifying endpoints on ReferenceLine to draw an arbitrary line
  segment.

## 1.0.1-metabolize.2

### feature

- Allow reference areas which extend past the canvas bounds

  Adds an `ifOverflow` prop which supports four values:
    - `ifOverflow="discard"` (default) – If the reference item falls partly
       outside the canvas, don't display it. This is the old default.
    - `ifOverflow="extendDomain"` – If the reference item falls partly
      outside the canvas, extend the domain so it fits. This is the old
      `alwaysShow` behavior.
    - `ifOverflow="clip"` – If the reference item falls partly outside the
      canvas, clip it to the canvas.
    - `ifOverflow="keep"` – If the reference item falls partly outside the
      canvas, draw it anyway.

  The `alwaysShow` prop is deprecated.


## 1.0.0-beta.10.metabolize.2 (Jul 3, 2018)

### fix

- Fix tooltips that disappear while mouse still over a scatter point
  (merged upstream in 1.0.0)
