## System identification competition

### Input-Output data

This folder contains the necessary data for the system identification task of the competition.

There are eleven CSV files named `data[1-11].csv`, each counting 31 lines (1 header line + 30 data lines) and two columns. 

The first column is the system response and the second one is the actuation signal.

See an example [here](./data1.csv).

### Input sequences

Two input sequences are given in [rdata1.csv](./rdata1.csv) and [rdata2.csv](rdata2.csv).

You need to produce the corresponding response and submit it to kaggle.

### Result

Your results need to be formatted as in the example file [response_sample.csv](./response_sample.csv).

The first column is an ID and the second one is the predicted outputs as explained [here](../sysid_rkhs.ipynb).
