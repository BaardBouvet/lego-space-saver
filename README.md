# Calculates minimum required Lego parts for your sets using sesam.io

Update the ``my-sets`` embedded dataset to contain the quantity of sets you own and download a csv file with minimum required parts you need in order to build any of your sets (but not all of them at once).

```
"entities": [
  {
    "Quantity": 1,
    "Set_Number": "7634-1"
  }, {
    "Quantity": 2,
    "Set_Number": "6682-1"
  }
]
```

You can download a CSV of required parts from ```<your-instance>/api/publishers/my-required-parts-endpoint``` with the total quantity you have, the max quantity you will need and which set that drives the max quantity.

_id | category | color | quantity_max | quantity_pct | quantity_total | rebrickable-parts:name | set_count | set_name | set_number
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
rebrickable-parts:2456-rebrickable-colors:70 | Bricks | Reddish Brown | 4 | 0.8 | 5 | Brick 2 x 6 | 2 | Pirate Tank | 7753-1
rebrickable-parts:2465-rebrickable-colors:71 | Bricks | Light Bluish Gray | 2 | 0.333333333333333 | 6 | Brick 1 x 16 | 3 | Cement Mixer | 7990-1

