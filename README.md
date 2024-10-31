# Section editing on mobile VE

```
quarto render report.ipynb --to html
scp report.html stat1011.eqiad.wmnet:/home/bearloga/section-editing-experiment.html
ssh stat1011.eqiad.wmnet
mv section-editing-experiment.html /srv/published/notebooks/editing/
```
