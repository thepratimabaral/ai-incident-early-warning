# AI Incident Early Warning

Can we spot early warning signs of AI incidents, the same way we spot early warning signs of a crop
disease outbreak?

In my earlier projects I predicted Turcicum Leaf Blight in maize from weather data. Here I want to use
the same kind of thinking on real AI incidents: what kinds of incidents are growing, in which sectors,
and what conditions come before them.

Work in progress.

## Data

[AI Incident Database](https://incidentdatabase.ai) weekly snapshot (CSV). The data is not uploaded
here. To get it:

1. Download the newest snapshot from https://incidentdatabase.ai/research/snapshots/
2. Put it in `data/` and unzip it: `tar -xjf backup-*.tar.bz2`

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```
