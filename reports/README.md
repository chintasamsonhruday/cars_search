# Vehicle history reports

Store full vehicle-history reports by VIN using this structure:

- `reports/<VIN>/goodcar.pdf`
- `reports/<VIN>/carfax.pdf`
- `reports/<VIN>/autocheck.pdf`

Dashboard history fields should only be marked clean when an actual report or clearly attributed source has been reviewed. Unknown items remain `Pending report`.
