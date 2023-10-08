# school_spike_sorting_marseille_2023

Here a collection of notebook to discover many ascpect of spikeinterface.
It is a mix between tutorial, short practice and handson.


## Upgrade your spikeinterface

You will need to update your spikeinterface package with the source installation.

```
conda activate si_env
pip install --upgrade git+https://github.com/SpikeInterface/spikeinterface.git@main
```

or

```
conda activate si_env
pip install --upgrade https://github.com/SpikeInterface/spikeinterface/archive/main.zip
```


## other link

Dataset can be download here in this drive:

https://docs.google.com/document/d/16Vn5fUkTFp6gmHykJItJZEsdvoLe-OmkXgEHhO3Yliw/edit?usp=sharing




## program


 1. **Monday 9/11** Afternoon session : lecture and demo (14:00 - 17:30)

    * 14:00 - 15:15 What you always wanted to know about Spike sorting PY
    * 15:15 - 15:45 Overview on the wonderful world of SpikeInterface SG
    * Break to properly learn our nicknames (15min)
    * 16:00 -  17:30 Deep interactive demo SG
	


  2. **Tuesday 10/11** Morning session : guided hands-on (9:30 - 13:00)

    * 9:30 - 10.10 Read data / describe probe / launching a sorter (40min) SG
    * 10:10 - 10:40 Preprocessing (filtrage/destriping/artifact removal/referencing) (30min) PY
    * 10:40 - 11:10 Post processing /quality metrics : remove bad units (30min)
    * Break for starting social interaction
    * 11:30 - 12:10 Visualization the many way of SpikeInterface (40min) SG
    * 12:10 - 12:30 Motion correction principle (20min) PY
    * 12:30 - 12:50 Which sorter to choose: make a benchmark (20min)  PY


3. **Tuesday 10/11** Afternoon session : less guided hands-on (14:00 - 17:30)

    * 14:00 - 15:00 Demo : open platform cloud sorting (dandi)  with open dataset SG
    * 15:00 - 16:00 Hands on with provided dataset
    * Break to decide where to go for a drink
    * 16:15 - 17:30 Hands on your own dataset.
