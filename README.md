# Street Tree Visualization

Visualization of [SF Street Tree Data](https://dev.socrata.com/foundry/data.sfgov.org/2zah-tuvt)

This is an exploritory piece for future work with [Friends of the Urban Forest](http://www.fuf.net/).

Part of the Data Science Group

## Setup
- Python 2.7
- Setup [virtualenv](https://virtualenv.pypa.io/en/stable/)
- Run `pip install -r requirements.txt`

## Ideas
- Map locations
  - Show which ones FuF help with
  - Show density
  - Organize by type
- Planting dates

## Data Questions
- What is `SiteOrder`? Number if multiple trees present
- What is `DBH`? Depth, height
- How is the `PlotSize` designated? All sorts of units and input schemas
- What are `XCoord` and `YCoord` based on? Cal coordinate system
