# 3Blue1Brown × Jane Street: the polyhedral puzzle

Work on the polyhedral puzzle posed in the 3Blue1Brown / Jane Street collaboration.

## Layout

- `README.md` — problem statement, approach, and results (to be written)

## Setup

```
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

## Puzzle Problem Statement
Andy the Ant randomly walks on the patches of a soccer ball (20 white hexagons and 12 colored pentagons, with each hexagon bordering 3 hexagons and 3 pentagons, and each pentagon bordering 5 hexagons).

Andy is equally likely to move to any bordering patch (including the one he came from).

If Andy starts a random journey from a pentagon, how many moves does it take on average for him to return to his starting point?
