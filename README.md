# Open Worldline Instantons

Mathematica notebooks used for open-worldline-instanton calculations.

## Contents

### `instanton_definitions_in_4D_for_QED_and_GR.nb`

General definitions and numerical routines for worldline-instanton calculations in QED and gravity.

### `instanton_inflation.nb`

Example calculations illustrating how to find instantons, choose contours in the complex proper-time plane, and reproduce the results presented in:

P. Semren and G. Torgrimsson,

*"Scattered wave functions and worldline instantons for particle production in curved spacetime"*

(to appear)

## Usage

The examples automatically load the definitions from

`instanton_definitions_in_4D_for_QED_and_GR.nb`

using

```Mathematica
NotebookEvaluate[
  FileNameJoin[
    {NotebookDirectory[],
     "instanton_definitions_in_4D_for_QED_and_GR.nb"}
  ]
]
```

Both notebooks should therefore be placed in the same directory.
