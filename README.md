# ogstosgf
Tool for converting raw OGS game JSONs to SGFs, modified for use in [ogs-data-analysis-tools](https://github.com/gyu-eun-lee/ogs-data-analysis-tools).

I made this to slightly tweak the output behavior from the [original tool](https://github.com/lightvector/ogstosgf) to better suit my needs.
Not looking to merge at the moment because I'm not sure the new behavior is as originally intended.

## Usage:
1. Input: directory `./ogsjsons` containing raw OGS game JSONs in format found at endpoint https://online-go.com/api/v1/games/<game_id>
2. `python3 ogstosgf.py ogsjsons/`
3. Output: SGF files in directory `./ogsjsons'
