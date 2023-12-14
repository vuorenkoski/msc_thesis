# Implementing graph algorithms on quantum annealer

MSc thesis, Lauri Vuorenkoski

This repository includes performance measurement programs used in MSc thesis.

## Setup

Create file "api_token.py" file having one line containing your api-key to D-Wave leap:

```
token = 'xxxxx'
```

Install dependencies:

```
pip install dwave-ocean-sdk matplotlib networkx
```

## Run measurements

Programs:
- All pairs shortest path: measure_apsp.py
- Graph isomorphism: measure_gi.py
- Community detection: measure_cd.py

First set variables sizes, solvers, num_reads_sel and graph_types according to your intended measurement. After that, run the program:


```
python ./measure_apsp.py
```
