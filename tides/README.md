# Worldwide tide files

Small files the LUNARA-P sky page fetches to work out tides anywhere in the world.

They are cut from **EOT20**, a global empirical ocean tide model:
Hart-Davis, Piccioni, Dettmering, Schwatke, Passaro and Seitz (DGFI-TUM), *EOT20: a global ocean tide model from
multi-mission satellite altimetry*, Earth System Science Data 13, 3869-3884, 2021. Data: doi:10.17882/79489.
Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/).

Changes made to the model: 14 of its 17 constituents are kept; cells are grouped into 5 x 5 degree tiles;
`coast/` holds sea cells within three cells of land at the model's 1/8 degree, `ocean/` every fourth cell each way;
amplitudes are rounded to 0.1 cm and phases to 0.01 degree; 18 cells with an amplitude over 1000 cm are left out.

Heights are about mean sea level. This is a model, not a tide table: do not use it for navigation.
